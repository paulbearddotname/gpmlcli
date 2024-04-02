# GoPro Media Library CLI

`gpmlcli` is a tool for uploading and downloading GoPro videos to and from the GoPro Media Library.

## Install

    sudo install gpmlcli /usr/local/bin/

## Help

    $ gpmlcli -h
    gpmlcli version 1.0.0
    Copyright (c) 2025 Paul Beard.
    Website: paulbeard.name

    gpmlcli is a tool for uploading and downloading GoPro videos to and from the GoPro Media Library.

    Usage: gpmlcli [-h] COMMAND

    Commands:
    login EMAIL PASSWORD
    logout
    list [-c]
    find [-c] SRC...
    rename FROM TO
    delete NAME
    upload SRC...
    download NAME...

    Options:
    -h show this help
    -c format columns
