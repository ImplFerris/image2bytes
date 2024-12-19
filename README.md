## Image2Bytes

Image2Bytes is a fork of [image2cpp](https://github.com/javl/image2cpp) developed by the [Jasper van Loenen](https://github.com/javl). The original codebase generates arudino and cpp code. This repo is meant to be used mainly for rust version of it. 

A simple tool for converting images into byte arrays (or byte arrays back into images), designed for use with monochrome displays like OLEDs. You can also input a byte array to reconstruct the image, which can be useful for debugging or working with images when only the byte array form is available.

Did you find this tool useful? Please support the original repository:
[https://github.com/javl/image2cpp](https://github.com/javl/image2cpp)

### Running the tool
You don't need any special dependencies / internet connection; all the necessary parts sit in a single .html file. So just open this index.html page in a (recent) browser to run the tool.

Or you can use the online version at https://implferris.github.io/image2bytes

### Example Rust code
//TODO: Link to the tutorial

### Screen types
It was created with a 128x64 pixel monochrome OLED display in mind, but it is designed to work with most similar displays. Some export settings may need adjustment depending on your specific display, and these are explained within the tool.

### Credits to Original Repo Authors
Initial code by [javl](https://github.com/javl) with aditional code by (in alphabetical order):
* [akumpf](https://github.com/akumpf)
* [Daniyal Warraich](https://github.com/daniyalw)
* [davidalim](https://github.com/davidalim)
* [dotcypress](https://github.com/dotcypress)
* [Harry48225](https://github.com/harry48225)
* [hurricaneJoef](https://github.com/hurricaneJoef)
* [jochenderwae](https://github.com/jochenderwae)
* [plewka](https://github.com/plewka)
* [Sebski123](https://github.com/Sebski123)
* [whoisnian](https://github.com/whoisnian)
* [wiredolphin](https://github.com/wiredolphin).

The example sketch is based on code by [Adafruit](https://github.com/adafruit). Dithering code from [stellar-L3N-etag](https://github.com/reece15/stellar-L3N-etag).

### License

`image2bytes` is released under GPL v3. This means you can use the project in any way you want (use, adapt, distribute, etc.) as long as you share any changes and link back to this repository.

This project is a derivative of [`image2cpp`](https://github.com/javl/image2cpp), originally created by [javl](https://github.com/javl) and released under GPL v3. Significant changes and adaptations have been made to create `image2bytes`. For more information, refer to the [LICENSE.md](LICENSE.md) file.
