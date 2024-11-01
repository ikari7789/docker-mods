# YaRSS2 Plugin - Docker mod for deluge

This mod adds [YaRSS2 Plugin](https://bitbucket.org/ikari7789/deluge-yarss-plugin) to Deluge, to be downloaded/updated during container start.

In deluge docker arguments, set an environment variable `DOCKER_MODS=ikari7789/docker-mods:deluge-yarss-plugin`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=ikari7789/docker-mods:deluge-yarss-plugin|linuxserver/mods:deluge-mod2`
