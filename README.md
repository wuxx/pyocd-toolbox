# pyocd-toolbox
## 使用说明
相比openocd，pyocd烧录更为灵活，可根据芯片的pack包（pack包一般为芯片厂家提供，内有芯片信息和烧录算法）即可烧录，举例如下：
```
F:\oss\pyocd-toolbox>pyocd.exe flash --erase chip --target ch32f103c8 --pack  ./Keil.WCH32F1xx_DFP.1.0.1.pack  ./flash_image.bin
```

## 参考资料
- https://github.com/RT-Thread-Studio/sdk-debugger-pyocd