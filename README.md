UTC Demo
========

This is a uApp demo of Ubuntu Touch.

#Howto Build

    $ mkdir ../build
    $ cd ../build
    $ click chroot -a armhf -f ubuntu-sdk-15.04 run cmake ../utc-demo
    $ click chroot -a armhf -f ubuntu-sdk-15.04 run make DESTDIR=./deploy install
    $ click build ./deploy


