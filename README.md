# Fedora Flatpak Docs

This repository documentation for packaging and using Flatpak in Fedora.

## Local preview

This repo includes scripts to build and preview the contents of this repository.

**NOTE**: Please note that if you reference pages from other repositories, such links will be broken in this local preview as it only builds this repository. If you want to rebuild the whole Fedora Docs site, please see [the Fedora Docs build repository](https://pagure.io/fedora-docs/docs-fp-o/) for instructions.

Both scripts use docker, so please make sure you have it installed on your system. Please see below for instructions.

To build and preview the site, run:

```
$ ./build.sh && ./preview.sh
```

The result will be available at http://localhost:8080. `build.sh` can then be run repeatedly to update the content as you edit it.

### Installing docker on Fedora

```
$ sudo dnf install docker
$ sudo systemctl start docker && sudo systemctl enable docker
```
