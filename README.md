# ffmpeg-python-docker

Lightweight docker image containing ffmpeg and python.

The image is based on [jrottenberg/ffmpeg](https://github.com/jrottenberg/ffmpeg). All images, including the `onbuild` versions, have an alpine base.

Versioning mirrors the python official docker images and contains ffmpeg-4.0.

The `python3-dev` package is included in all images excluding `slim` versions.
