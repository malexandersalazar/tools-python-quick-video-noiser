# Quick video noiser tool

![alt text](/img/speckle.png "Quick video noiser tool")

 A Python tool based on ffmpeg and OpenCV to add noise to videos quickly.

## Installation

### ffmpeg

Download FFmpeg from their [download page](https://ffmpeg.org/download.html) and then add ffmpeg to the PATH environment variable.

### Quick video noiser tool

Just copy the `qvn.py` script located in the dist folder.

## Getting Started

To use the script we only have to indicate the path of the video that we want to process.

> python qvn.py W:\lyra-iorek.mp4

You can also set the noise type as a parameter: `saltpepper` or `speckle` (default).

> python qvn.py W:\lyra-iorek.mp4 saltpepper

![alt text](/img/saltpepper.png "Quick video noiser tool")

## Dependencies

* python (== 3.8.15)
* cv2 (== 4.6.0)
* numpy (== 1.23.5)

## License

This project is licenced under the [MIT License][1].

[1]: https://opensource.org/licenses/mit-license.html "The MIT License | Open Source Initiative"