![Build application](https://github.com/allnes/pp_2021_autumn/workflows/Build%20application/badge.svg?branch=master)

# Parallel Programming Course

The following parallel programming technologies are considered in practice:
  * `MPI`
  * `OpenMP`
  * `TBB`

## Rules for submissions
1. You are not supposed to trigger CI jobs by frequent updates of your pull request. First you should test you work locally with all the scripts (code style)
    * Respect others time and don't slow down the job queue
2. Carefully check if the program can hang

## 1. Set up your environment
### Static analysis of project
  * **Windows (MSVC)**:
  
  Unsupported operating system!
  
  * **Linux (`gcc` and `clang`)**:
  ```
  sudo apt install cppcheck
  ```
  * **MacOS (apple clang)**:
  ```
  brew install cppcheck
  ```

### Code style analysis
Please, follow [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html).

```
pip install cpplint # (Python3)
```

### Parallel programming technologies
### `MPI`
  * **Windows (MSVC)**
  * Rectangular method: In mathematics, the midpoint rule, also known as the midpoint Riemann sum or midpoint method, is a method of estimating the integral of a function or the area under a curve by dividing the area into rectangles of equal width.

### `OpenMP`
  
  * `OpenMP` is included into `gcc` and `msvc`, but some components should be installed additionally
  * Digital image enhancement: This tool is designed to enhance images by adjusting contrast through the utilization of the histogram equalization algorithm. This algorithm employs a cumulative intensity histogram to map the original image's intensities, resulting in an image with equalized intensity levels.

### `TBB`
  * **Windows (`MSVC`)**: 
  * Shell sort batcher: Shell sort is a generalized version of the insertion sort algorithm. It first sorts elements that are far apart from each other and successively reduces the interval between the elements to be sorted.
