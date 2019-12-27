# TensorFlow Magic Wand demo for M5StickC

M5StickC port of [magic wand demo](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/lite/micro/examples/magic_wand). 

M5StickC is an ESP32-based module with TFT LCD and analog MEMS microphone.  
This port uses Arduino-based [M5StickC library](https://github.com/m5stack/M5StickC) on [PlatformIO](https://platformio.org/). I have tested this on my [M5StickC](https://docs.m5stack.com/#/en/core/m5stickc). Earier production lots of M5StickC have an accelerometer sensor diffrent from my module (SH200Q instead of MPU6886) and would not work with code on this repository.

Most of the source files on this repository are derived from TensorFlow repository using   
```make -f tensorflow/lite/micro/tools/make/Makefile TARGET=esp generate_magic_wand_esp_project```  
excepting `accelerometer_handler.cc`, `output_handler.cc`, and `main.cpp`.

Visit [my blog entry](https://blog.boochow.com/article/m5stack-tflite-magic-wand.html) for details and demonstration video. (Sorry the article is in Japanese)
