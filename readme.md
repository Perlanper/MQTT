# Setup
## Build image:
* Naviagte to ```source/build_tools```
* run ```docker build -t cpp_env .```

## Start Container:
* Navigate to root
* run ```docker run -v .:/home -it -w /home```

## Build Application
* run Cmake ```cmake -B build -S source```
* run ```make``` in build directory