# Cut Graph

This C++ project framework is used to help students to implement cut graph algorithms. It contains a simple opengl viewer.

## Dependencies
 
1. `MeshLib`, a mesh library based on halfedge data structure.
2. `freeglut`, a free-software/open-source alternative to the OpenGL Utility Toolkit (GLUT) library.

## Directory Structure

``` txt
include           -- The header files of cut graph algorithm.
src               -- The source files of cut graph algorithm. 
CMakeLists.txt    -- CMake configuration file.
```

## Configuration

### Windows

1. Install [CMake](https://cmake.org/download/).

2. Download the source code of the C++ framework.
> E.x. I create a folder `projects` in `C:/`, then unzip the source code there.

3. Configure and generate the project for Visual Studio.

> ``` bash
> cd CCGHomework
> mkdir build
> cd build
> cmake ..
> ```
> *One can also finish this step using CMake GUI.*

4. Open the \*.sln using Visual Studio, and complie the solution.

5. Finish your code in your IDE.

6. Run the executable program.
> E.x. 
> ``` bash
> cd bin
> ./CutGraph.exe ../data/torus.m
> ./CutGraph.exe ../data/eight.m
> ```
> If you can see the following results, then it means that you have finished the cut graph algorithm. 
> 
> ![Cut graph of torus](../resources/torus_cut_graph.png) ![Cut graph of eight](../resources/eight_cut_graph.png)

### Linux & Mac

1. Build and compile the code.

> ``` bash
> cd CCGHomework
> mkdir build
> cd build
> cmake ..
> make && make install
> ```

2. Run the executable program.

> ``` bash
> cd ../bin/
> ./CutGraph ../data/torus.m
> ./CutGraph ../data/eight.m 
> ```
