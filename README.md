[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/cui8tracks.svg)](https://hub.docker.com/r/rubygem/cui8tracks/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/cui8tracks.svg)](https://hub.docker.com/r/rubygem/cui8tracks/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/cui8tracks.svg)](https://hub.docker.com/r/rubygem/cui8tracks/)
[![Gem Downloads](https://img.shields.io/gem/dt/cui8tracks.svg)](https://rubygems.org/gems/cui8tracks/)
# cui8tracks

Auto-Generated Docker image for cui8tracks to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/cui8tracks`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/cui8tracks`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/cui8tracks`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/cui8tracks/)
