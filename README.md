# STM32F10x-Template with the CMake

### Version requirements
* Use the offical STM32F10x_StdPeriph_Driver V3.5
* Use the FreeRTOS V8.2.3
* Use CMake less than V3.1

### Dependencies
```
arm-none-eabi-gcc
arm-none-eabi-gdb
stlink
```

### How to Install
1. make a directory in the project directory
```shell
  1. mkdir build
  2. cd build
```

2. cmake the project directory CMakeList.txt
```shell
  cmake ..
```

3. Build the Source
```shell
  make
```

### If you wang to clean the all Build file , you can
```shell
  make clean-all
```

### If you install the st-link V1/V2/V2.1, you can
```shell
  make flash
```
