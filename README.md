# About

[innosetup-idp-docker](https://github.com/adriespo/innosetup-idp-docker) is a fork of the Docker Image [amake/innosetup-docker](https://github.com/amake/innosetup-docker). I wanted to fork this image to install and use [Inno Download Plugin](https://github.com/andykimpe/inno-download-plugin) in addition to [Inno Setup 6](https://jrsoftware.org/isinfo.php).

Because Inno Download Plugin has not a "silent install" option and amake/innosetup-docker is based on a X Server without display I inserted the needed files (idp.dll, idp.iss and default.iss) directly in the image.  

Therefore it is possibile to use in the.iss file all the IDP directives; for more info see the directory [examples](https://github.com/andykimpe/inno-download-plugin/tree/master/examples) in andykimpe/inno-download-plugin.

The Docker image is at https://hub.docker.com/r/adriespo/innosetup-idp.

Follow the same usage of https://github.com/amake/innosetup-docker/blob/latest/README.md.

