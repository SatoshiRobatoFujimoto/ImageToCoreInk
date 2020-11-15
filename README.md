# ImageToCoreInk
Image Converter for M5Stack CoreInk.
The converter will automatically convert a full-color image to a dithered image.

See [this thread](https://twitter.com/ksasao/status/1327586531960258560).


![Sample Image](https://pbs.twimg.com/media/Em1xMhXVgAIwkhM?format=jpg&name=large)

## Download
- [win10-x86](https://github.com/ksasao/ImageToCoreInk/releases/download/v0.0.2/ImageToCoreInk_0.0.2_win10-x64.zip)
- [osx-x64](https://github.com/ksasao/ImageToCoreInk/releases/download/v0.0.2/ImageToCoreInk_0.0.2_osx-x64.zip)
- [linux-x64](https://github.com/ksasao/ImageToCoreInk/releases/download/v0.0.2/ImageToCoreInk_0.0.2_linux-x64.zip)

## Usage
1. Convert image file(s) to header file.
```
ImageToCoreInk [image_file|image_folder]
```
Full color image (.PNG, .JPG, ...) will automatically be converted to dithered image.

2. Include the header file to your Arduino project.
- [example](https://github.com/ksasao/ImageToCoreInk/blob/main/sample/arduino/sample_image/sample_image.ino)
