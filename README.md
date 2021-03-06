# Fresh Ubuntu Box [![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)

> Customization of fresh Linux installs, using Ubuntu and derivatives

---

## What is this?

My set of customization scripts for setting a fresh Linux box to my preferences.
This is a collection of scripts that flexibly allowing setting up a few
different machine configurations, written specifically to handle a variety of
resource constraints.

This workflow has been tested on [Amazon's EC2 Ubuntu
instances](https://aws.amazon.com/marketplace/pp/B00JV9JBDS), my [Acer
Chromebook 11 C740-C4PE](http://www.acer.com/ac/en/US/content/model/NX.EF2AA.002)
(running [Ubuntu 14.04 Trusty Tahr](http://releases.ubuntu.com/14.04/) with the
[Xfce desktop](http://www.xfce.org/), installed via
[Crouton](https://github.com/dnschneid/crouton)), a dual-booting [MacBook Pro
2010 (7,1)](https://support.apple.com/kb/sp583?locale=en_US) (running [Ubuntu
14.04 Trusty Tahr](http://releases.ubuntu.com/14.04/) with the [Unity
desktop](https://unity.ubuntu.com/), installed via
[rEFIt](http://refit.sourceforge.net/)), and a [ThinkPad X1 Carbon 2018,
(6th-generation)](https://www.lenovo.com/us/en/laptops/thinkpad/thinkpad-x/ThinkPad-X1-Carbon-6th-Gen/p/20KH002HUS)
(running [Ubuntu 18.04](http://releases.ubuntu.com/18.04/) then [Ubuntu 20.04](https://releases.ubuntu.com/20.04/))

---

## How do I use this?

1. `sudo apt-get update && sudo apt-get upgrade`
2. `sudo apt-get install build-essential git`
3. `git clone https://github.com/nhejazi/ubuntu-fresh.git ~/ubuntu-fresh`
4. `cd ~/ubuntu-fresh`
4. `sudo . ./core.sh`
5. `sudo . ./langs.sh`
6. `sudo . ./tools.sh`
7. `. ./nosudo.sh`

---

## Package Libraries

* __[nhejazi/myPkgLib](https://github.com/nhejazi/myPkgLib)__ - a working list
    of packages to be used alongside the core software in this repo.

---

## License

&copy; 2016-2020 [Nima Hejazi](https://nimahejazi.org)

The contents of this repository are distributed under the MIT license. See file
`LICENSE` for details.
