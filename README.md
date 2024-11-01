# ltConfg Plugin - Docker mod for deluge

This mod adds [ltConfig Plugin](https://github.com/ikari7789/deluge-ltConfig) to Deluge, to be downloaded/updated during container start.

In deluge docker arguments, set an environment variable `DOCKER_MODS=ikari7789/docker-mods:deluge-ltConfig-plugin`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=ikari7789/docker-mods:deluge-ltConfig-plugin|linuxserver/mods:deluge-mod2`
