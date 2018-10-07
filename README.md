## Pre-requisites:

- Ipopt and CppAd:
    - [Working solution](https://github.com/udacity/CarND-MPC-Project/issues/34#issuecomment-412305069)  
    - (original, segfaults) [Ipopt and CppAd](https://github.com/udacity/CarND-MPC-Quizzes/blob/master/install_Ipopt_CppAD.md)
    - (also segfaults) [Alternative for Ipopt](https://github.com/udacity/CarND-MPC-Project/issues/22#issuecomment-379532837)


## Build
- `#>` `git submodule update --init --recursive`
- `#>` `mkdir build && cd build && cmake .. -DGIT_SUBMODULE=ON && make`
- `#>` `./MindTheLine`
