# rpi-img-server

Takes a picture every minute using [loranbriggs/go-camera](https://github.com/loranbriggs/go-camera), then serves it to `localhost:9999/img GET`using [hoisie/web](https://github.com/hoisie/web).

Note that this projext uses [gb](https://getgb.io) ([constabulary/gb](https://github.com/constabulary/gb)), so all the dependencies are contained here. The build artifact(s) can be found in the bin directory.

This project is built with the Raspberry Pi camera module in mind (tested on a Pi Zero). It probably won't work on any other platform without modification.
