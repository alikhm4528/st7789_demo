This is a simple demo for ST7789 on stm32f103c8t6(blue-pill)
To build the project simply run following commands

```
mkdir build
cd build
cmake ..
make -j4
```

To program blue-pill using openocd, use following command

```
sudo openocd -f interface/stlink.cfg -f target/stm32f1x.cfg -c "program ST7789_demo_f103c8.elf verify reset exit"
```
good luck!

