<img src="https://github.com/aksnzhy/xLearn/raw/master/img/xlearn_logo.png" width = "400"/>    

[![Hex.pm](https://img.shields.io/hexpm/l/plug.svg)](./LICENCE)
![Project Status](https://img.shields.io/badge/version-0.1.0-green.svg)
[![Travis](https://img.shields.io/travis/rust-lang/rust.svg)]()

## What is xLearn?

xLearn is a ***high performance***, ***easy-to-use***, and ***scalable*** machine learning package, 
which can be used to solve large-scale classification and regression problems. If you are the user 
of liblinear, libfm, or libffm, now the xLearn is your another better choice.

### Performance 

<img src="https://github.com/aksnzhy/xLearn/raw/master/img/speed.png" width = "800"/>   

xLearn is developed by high-performance C++ code with careful design and optimizations. Our system is designed to 
maximize the CPU and memory utilizations, provide cache-aware computation, and support lock-free learning. By 
combining these insights, xLearn is 5x - 13x faster compared to the similar learning systems.

### Ease-of-use

<img src="https://github.com/aksnzhy/xLearn/raw/master/img/code.png" width = "600"/>   

xLearn does not rely on any third-party library, and hence users can just clone the code and compile it by using cmake. 
Also, xLearn supports very simple python API for users.

### Scalability

<img src="https://github.com/aksnzhy/xLearn/raw/master/img/scalability.png" width = "650"/>   

xLearn can be used for solving large-scale machine learning problems. First, xLearn supports on-disk training, which can handle 
very large data (TB) by using the disk on a single machine. Moreover. xLearn support distributed training, which scales beyond billions
of example across many machines. 
