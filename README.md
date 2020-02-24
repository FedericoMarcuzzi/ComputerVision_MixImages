# ComputerVision_MixImages
Given two images, the program combines them based on the threshold used (C++ and OpenCV)

First assignment for the *Computer Vision* [course](https://www.dsi.unive.it/~bergamasco/courses/computer_vision_2017_2018.html) of *Università Ca' Foscari Venezia*, academic year 2017/2018


Install OpenCV:

```console
$ git clone --depth 1 https://github.com/opencv/opencv.git
$ cd opencv
$ mkdir build
$ cd build

$ cmake ../ -DCMAKE_BUILD_TYPE="Release"
$ make -j 2

$ make install
```


How to build 'opencv_miximages':

```console
$ mkdir build
$ cd build
$ cmake ../ -DOpenCV_DIR="<insert the path of your opencv/build directory>"
$ make
```


How to run 'opencv_miximages':

```console
$ cd build
$ make run
```

or, alternatively:

```console
$ make install
$ cd dist/bin
```
and run the generated executable


Federico Marcuzzi, 2020


