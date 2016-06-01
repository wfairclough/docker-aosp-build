# docker-aosp-build
A preconfigured container for building AOSP on any Linux machine

Create an AOSP root direction: `mkdir ~/aosp-root`

Create link to AOSP source tree you want to build `ln -s /path/to/aosp/tree ~/aosp-root/aosp`

Run `utils/aosp` to pull the container and attach to the bash
