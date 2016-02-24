# otb-mpitoy
Example of an MPI-ized OTB pipeline

The pipeline shown resamples an input image and write the result using the otbSimpleParallelTiffWriter.

The application can be runned on multiple processing nodes with mpi.
mpirun -np 2 otbMPIToy inputImage.tif resampledImage.tif
