## Relay Chat

Ronsor Relay Chat System, or RRCS, is a new federated network of servers that all have the goal to bring a simple, modern chat network.
RRCS was inspired by IRC, and various modern (and proprietary) chat systems, such as Discord.

RRCS is written in 100% standard Tcl 8.5+. Tcl is not very large and worth installing for this project.

### Features

RRCS has all the standard features of a chat service:

    * Chat rooms and moderators
    * Support for bans
    * Channel topics
    * No registration required.
    
RRCS also allows the `ENCAP` command, allowing `ENCAP`sulation of "out of band" data, such as voice, video, and images.

### How do I use RRCS

The simplest way to use RRCS right now is to use the IRC gateway: http://kiwiirc.com/client/irc.openstar.pw/#ronsor
The default chat client is quite limited right now.

You can setup your own server if you'd like. Please see https://github.com/ronsor/relaychat.

### What license is the default RRCS implementation

RRCS is under the MIT License. Copyright (C) 2014, 2015, 2016, 2017 Ronsor-OpenStar Developments and Ronsor.
