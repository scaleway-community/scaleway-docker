Official Docker image on Online Labs
====================================

Scripts to build the official Docker image on Online Labs

This image depends on [the official Ubuntu image](https://github.com/online-labs/image-ubuntu).

---

Commands
--------

    # build the image in a rootfs directory
    $ make rootfs
    
    # build a tarball of the image
    $ make rootfs.tar
    
    # push the image on s3
    $ make publish_on_s3.tar
    
    # write the image to /dev/nbd1
    $ make install_on_disk

Related projects
----------------

- https://github.com/online-labs/image-tools (Main project for building images on Online Labs)
- https://github.com/online-labs/image-builder (Old repository with full history)
- https://github.com/online-labs/ocs-scripts (Common scripts for distributions)

Links
-----

- [Community: Docker Support](https://community.cloud.online.net/t/official-docker-support/374?u=manfred)
- [Community: Getting started with Docker on C1 (armhf)](https://community.cloud.online.net/t/getting-started-docker-on-c1-armhf/383?u=manfred)
- [Online Labs Blog - Docker on C1](https://blog.cloud.online.net/2014/10/27/docker-on-c1/)