# TensorFlow Magic Wand demo for M5Stack

M5Stack port of [magic wand demo](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/lite/micro/examples/magic_wand). 

Most of the source files on this repository are derived from TensorFlow repository using   
```make -f tensorflow/lite/micro/tools/make/Makefile TARGET=esp generate_magic_wand_esp_project```  
excepting `accelerometer_handler.cc`, `output_handler.cc`, and `main.cpp`.

Visit [my blog entry](https://blog.boochow.com/article/m5stack-tflite-magic-wand.html) for details and demonstration video. (Sorry the article is in Japanese)
