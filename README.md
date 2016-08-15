Watch Me
========

This just runs `maven clean test` whenever a watched file changes. It will let
you know when the tests start failing using `notify-send` (the ubuntu
notification system). You will also get informed the _first_ time the build
starts passing again.

Synopsis
--------

```bash
watch_me src
```

You can pass any number of files and globs are also supported.

Requirements
------------

This requires `notify-send` and `inotifywait`. These are available in
`libnotify-bin` and `inotify-tools`. Use the following command to install them:

```bash
sudo apt-get install libnotify-bin inotify-tools
```
