ubuntu docker image
=============================

A slim ubuntu image for docker


releases/tags
----------------------------

Currently only most recent LTS releases _precise_ and _trusty_ are supported.
The build depends on upstream official ubuntu and gets triggered on every upstream change.

packages
-----------------------------

* vim
* curl
* net-tools
* git
* locales

settings
-----------------------------

* en_US.utf8 locale


notes
----------------------------

the image is created in one layer and all temporary files are removed in order to keep it 
low in size

roadmap
----------------------------

no further plans, subject to change at any time.
