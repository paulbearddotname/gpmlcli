# GoPro Media Library CLI

`gpmlcli` is a tool for uploading, and downloading GoPro videos to, and from the GoPro Media Library.

## Install

    sudo install gpmlcli /usr/local/bin/

## Help

    $ gpmlcli -h
    gpmlcli version 1.1.0
    Copyright (c) 2025 Paul Beard.
    Website: paulbeard.name

    gpmlcli is a tool for uploading, and downloading GoPro videos to, and from the GoPro Media Library.

    Usage: gpmlcli [-h] COMMAND

    Commands:
    login EMAIL PASSWORD
    logout
    list [-c]
    find [-c] SRC...
    rename FROM TO
    delete NAME
    upload   [-v] [-P PARALLEL] SRC...
    download [-v] [-P PARALLEL] [-C CHANGE_DIRECTORY] [NAME...]

    Options:
    -h show this help
    -c format columns
    -v verbose
    -P parallel
    -C change directory

    Examples:
    Upload all missing videos from Downloads directory. Four at a time.
    gpmlcli   upload -P 4    ~/Downloads
    Upload a particular video, and show progress meter.
    gpmlcli   upload         GH011234.MP4
    Download all missing videos to Downloads directory. Four at a time.
    gpmlcli download -P 4 -C ~/Downloads
    Download a particular video to the current directory.
    gpmlcli download         GH011234.MP4
