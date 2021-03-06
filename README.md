Name
====

showman-samples - Sample screenplay files for generating OpenResty's [public videos](https://www.youtube.com/channel/UCXVmwF-UCScv2ftsGoMqxhw) using [OpenResty Showman](https://openresty.com/en/showman/)

Table of Contents
=================

* [Name](#name)
* [Description](#description)
    * [OpenResty Edge](#openresty-edge)
    * [OpenResty Tutorials](#openresty-tutorials)
    * [OpenResty Showman](#openresty-showman)
* [Author](#author)
* [Copyright & Licenses](#copyright--licenses)

Description
===========

This repository holds many sample screenplay files written in the [Nav language](https://doc.openresty.com/en/navlang/) (or navlang) and the narrative language. These screenplay
documents are used to generate our public [Youtube videos](https://www.youtube.com/channel/UCXVmwF-UCScv2ftsGoMqxhw) using our [OpenResty Showman](https://openresty.com/en/showman/) product.

The `.nav` files are written in [navlang](https://doc.openresty.com/en/navlang/).

The `.nar` files are wrtiten in the `Narrative` language.

The first-level directory names correspond to our Youtube channel's playlists:

OpenResty Edge
--------------

[OpenResty-Edge/](OpenResty-Edge/) is for our [OpenResty Edge](https://www.youtube.com/playlist?list=PLlR4WakbzQp3blQY5pLBHhNzR2EsEWiJK) YouTube playlist.

The samples under this directory mostly interact with complex web applications and web pages. But they may still contain some terminal or command-line interactions.

It contains the following screenplay files:

* Screenplay [edge-new-proxy.nav](OpenResty-Edge/edge-new-proxy.nav) is for video [Set up a Simplest Reverse Proxy and Load Balancer with OpenResty Edge](https://youtu.be/fgtiOYrdsE4).
* Screenplay [edge-cache-rules.nav](OpenResty-Edge/edge-cache-rules.nav) is for video [Enable HTTP Cache in OpenResty Edge](https://youtu.be/g8H0HYM3AdM).
* Screenplay [edge-cache-purge.nav](OpenResty-Edge/edge-cache-purge.nav) is for video [Purge HTTP Cache in OpenResty Edge](https://youtu.be/9Dy43JXaxKQ).
* Screenplay [edge-upload-ssl-certs.nav](OpenResty-Edge/edge-upload-ssl-certs.nav) is for video [Upload SSL Certificates for HTTPS Sites in OpenResty Edge](https://youtu.be/DV-uPZ-I5og).
* Screenplay [edge-lets-encrypt.nav](OpenResty-Edge/edge-lets-encrypt.nav) is for video [Issue Free SSL Certificates via Let's Encrypt in OpenResty Edge](https://youtu.be/OBrJlaAPv1k).
* Screenplay [edge-http-to-https.nav](OpenResty-Edge/edge-http-to-https.nav) is for video [Enforce the use of SSL in websites via OpenResty Edge](https://youtu.be/H1T-019IK2k).
* Screenplay [edge-lang-redirect.nav](OpenResty-Edge/edge-lang-redirect.nav) is for video [Redirect to different URIs Based on Clients' Language Settings (OpenResty Edge)](https://youtu.be/Z7zeYz2zDbQ).
* Screenplay [edge-upstream-host.nav](OpenResty-Edge/edge-upstream-host.nav) is for video [Set Different Host Headers for Upstream Requests in OpenResty Edge](https://youtu.be/NIlOrqi-I8U).
* Screenplay [edge-config-release.nav](OpenResty-Edge/edge-config-release.nav) is for video [Gateway Config's Version Control & Release Management in OpenResty Edge](https://youtu.be/XkPlx9If6sI).

OpenResty Tutorials
-------------------

[OpenResty-Tutorials/](OpenResty-Tutorials/) is for our [OpenResty Tutorials](https://www.youtube.com/playlist?list=PLlR4WakbzQp0iUvHwJeBcG5MKWgGa_ahU) YouTube playlist.

The samples under this directory mostly interact with the terminal or command-line, including interations with complex terminal applications like `less` and `vim`.

It contains the following screenplay files:

* Screenplay [or-hello-world.nav](OpenResty-Tutorials/or-hello-world.nav) is for video [Hello World HTTP Example in OpenResty/Nginx](https://youtu.be/eSfYLvVQMxw).
* Screenplay [or-lua-module.nav](OpenResty-Tutorials/or-lua-module.nav) is for video [Write Your Own Lua Modules in OpenResty/Nginx Applications](https://youtu.be/vfYxOMl5LVY).
* Screenplay [resty-cmd.nav](OpenResty-Tutorials/resty-cmd.nav) is for video [OpenResty's resty Command-Line Utility Demo](https://youtu.be/L1c7aw4mSOo).
* Screenplay [centos8-or-install.nav](OpenResty-Tutorials/centos8-or-install.nav) is for video [Install OpenResty on CentOS 8 via dnf](https://youtu.be/B5lfAZunxfc).
* Screenplay [data-share.nav](OpenResty-Tutorials/data-share.nav) is for video [Share Data Across Requests Served by OpenResty](https://youtu.be/AVR5Ft6FXTo).
* Screenplay [restydoc.nav](OpenResty-Tutorials/restydoc.nav) is for video [Lookup OpenResty Documentation on Terminal with restydoc](https://youtu.be/_PjpdUEeKeM).
* Screenplay [time-lua.nav](OpenResty-Tutorials/time-lua.nav) is for video [Measure Execution Time of Lua Code Correctly in OpenResty](https://youtu.be/VkRYW_qLoME).
* Screenplay [luajit-bytecode.nav](OpenResty-Tutorials/luajit-bytecode.nav) is for video [Precompile Lua Modules into LuaJIT Bytecode to Speedup OpenResty Startup](https://youtu.be/EP7c0BM2yNo).
* Screenplay [stream-resp.nav](OpenResty-Tutorials/stream-resp.nav) is for video [Streaming HTTP Response Output in OpenResty](https://youtu.be/4VQP7eKq4oA).
* Screenplay [ubuntu20-or-install.nav](OpenResty-Tutorials/ubuntu20-or-install.nav) is for video [Install OpenResty on Ubuntu 20.04 via apt-get](https://youtu.be/Hu68mQDKXCo).

[Back to TOC](#table-of-contents)

OpenResty Showman
-----------------

[OpenResty-Showman/](OpenResty-Showman/) is for our [OpenResty Showman](https://www.youtube.com/playlist?list=PLlR4WakbzQp14ovGVZCtTKdfX3u4u7PNR) YouTube playlist.

Most of the samples under this directory use the `Narrative` language to add narrative voices and subtitles to manually-recorded videos. Some use [navlang](https://doc.openresty.com/en/navlang/) to do automated terminal or command-line interactions instead.

It contains the following screenplay files:

* Screenplay [showman-google.nar](OpenResty-Showman/showman-google.nar) is for video [How to Auto-Generate Demo Videos for Google Search from Screenplay Docs (via OpenResty Showman)](https://youtu.be/i_n53z_zE3A).
* Screenplay [showman-baidu.nar](OpenResty-Showman/showman-baidu.nar) is for video [Auto-Generate Demo Videos for Baidu Search from Screenplay Documents (in Chinese)](https://youtu.be/y_g6B4aRc5o).
* Screenplay [ordemo.nav](OpenResty-Showman/ordemo.nav) is for video [How We Generate Videos from Screenplay Files](https://youtu.be/oew5RYUPMYY).

[Back to TOC](#table-of-contents)

Author
======

The [OpenResty Inc.](https://openresty.com/en/) Team.

[Back to TOC](#table-of-contents)

Copyright & Licenses
====================

Copyright (C) 2020-2021 OpenResty Inc. All rights reserved.

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/)

[Back to TOC](#table-of-contents)
