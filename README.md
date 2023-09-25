# amp-cli-signed-binaries-repo

A repo for CLI binaries which need to be built and/or signed specially.

Specifically:

* ARM binaries typically need to be built on an ARM machine or they will not work.
* MacOS binaries need to be built and signed on a Mac

This project contains CLI artifacts built and signed appropriately and injected into the release build.
