# A simple path tracer using NVIDIA OptiX
## Overview
This little code is started by combining ``optixPathTracer`` and ``optixMeshViewer`` projects from OptiX SDK. OptiX provides a simple and neat way to implement ray tracing algorithm on GPU with CUDA. 

Due to the limitaion of APIs, so far I haven't figured out the way to split rays recursively. Currently the code is pure path tracing without any ray splitting. The ray branching is equivalently implemented by Russian Roulette. 


