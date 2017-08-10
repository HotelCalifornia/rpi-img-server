# rpi-img-server

Takes a picture every minute using loranbriggs/go-camera, then serves it to `localhost:9999/img GET`using hoisie/web.

Note that this projext uses [gb](https://getgb.io) (constabulary/gb), so all the dependencies are contained here. The build artifact(s) can be found in the bin directory
