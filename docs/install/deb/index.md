---
layout: default
title: Install (dep)
---

# Install (dep)

 1. Add repo

        $ (. /etc/lsb-release ; curl http://dl.rockstack.org/deb/rock-release-${DISTRIB_CODENAME}.deb -o rock-release.deb )
        $ sudo dpkg -i rock-release.deb
        $ sudo apt-get update

 1. Install `rock` and runtimes

        $ sudo apt-get install -y \
            rock \
            rock-devtools \
            rock-runtime-node04 \
            rock-runtime-node06 \
            rock-runtime-node08 \
            rock-runtime-perl516 \
            rock-runtime-php54 \
            rock-runtime-python27 \
            rock-runtime-python33 \
            rock-runtime-ruby18 \
            rock-runtime-ruby19

 1. Continue to [getting started](/docs/) page
