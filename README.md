# docker-android-sdk

Dockerfile for building android projects. It currently
support api27.

## Usage

Grab from docker cloud with: `docker pull narfman0/docker-android-sdk`

Run with `docker run -d narfman0/docker-android-sdk`

### Notes

* I am personally using this in conjunction with a jenkins node. I use
`adb connect <hostname>` before each job, so the node doesn't have to
know much about the emulator.

## License

Copyright 2018 Jon Robison

See LICENSE for details
