ELMSLN Developer
================

This is a meta-repo for developers that downloads all the repositories you
need to be an ELMSLN developer and manage multiple learning networks from
one package.

###Here’s what you need ahead of time to make this useful
1. Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads) (ensure you are on the latest version 4.0.8+)
2. Install [Vagrant](http://www.vagrantup.com/downloads.html) (you'll need Vagrant 1.5+ so that it supports VagrantCloud)
3. Install [git](http://git-scm.com/downloads) (recommended)

To clone this correctly, run the following command:

`git clone --recursive https://github.com/elmsln/elmsln-developer.git`

This structure is broken out into three major directory trees:

1. *github* - the elmsln major project repository from github
  * https://github.com/elmsln/elmsln

2.  *instances* - Each deployment of ELMSLN can be managed from this repo:
   It also comes with the following two instances:
  * example config - https://github.com/elmsln/elmsln-config-example
  * vagrant config - https://github.com/elmsln/elmsln-config-vagrant

3. *vagrant* - the supported vagrant package for elmsln is included in the main ELMSLN repo
  * https://github.com/elmsln/elmsln/

Now go read the install instructions for https://github.com/elmsln/elmsln/wiki/Vagrant:-Step-by-Step-setup and make sure things are setup to do that and start working :)

It is recommended that in your actual deployments on server that you map
the github directory to an alternate remote in-house, preferably one per
server in your dev-staging-production workflow.

LICENSE
=======
ELMSLN is a collection of many, many projects, all individually licensed, all open source. The myiad of License files is why this section is added to avoid confusion.

* ELMSLN code on github (and not referenced or pulled in from other sources) is GPLv3.
* ELMS contributed modules from drupal.org are GPLv2 due to licensing requirements of the drupal.org community.
* Drupal and Drupal contributed modules and themes are GPLv2 due to licensing requirements of the drupal.org community.
* Piwik is GPLv3 via it's original repo (https://github.com/piwik/piwik)
* CKEditor 4.x is GPLv3
* Other included libraries are their respective LICENSE.txt files included local to those pieces of code

