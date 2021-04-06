# Docker mod to fix VAAPI

This mod fixes VAAPI devices initializing correctly allowing hardware acceleration.
See: https://github.com/linuxserver/docker-emby/issues/41

In emby docker arguments, set an environment variable `DOCKER_MODS=jbouhd/docker-mods:docker-emby-fix-vaapi`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=jbouhd/docker-mods:docker-emby-fix-vaapi|linuxserver/mods:docker-emby-mod2`