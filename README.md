# HDR+ Implementation
Please see: http://timothybrooks.com/tech/hdr-plus

To compile, follow these steps:
1. Install Halide from http://halide-lang.org/ (recomended version from 2016/10/22)
2. Set `HALIDE_ROOT_DIR` in CMakeLists.txt to the Halide directory path.
3. From the project root directory, run the following commands:
```
mkdir build
cd build
sudo apt-get install libjpg-dev libpng-dev dcraw libimage-exiftool-perl
cmake ..
make
```
