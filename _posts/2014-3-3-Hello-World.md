---
layout: post
title: R and Python in fresh Linux install
published: true
---

Installing R Studio, setting up Anaconda and your environments in a fresh Linux install.


I recently did a fresh install of linux for the _nth_ time. Remember to always backup your precious files! History of my linux use is, as predictable, a slow Windows 7 PC. Now I cannot imagine going back to Windows anymore.


> Linux Mint Cinnamon --- Linux Mint MATE --- MX Linux Fluxbox


Here I followed the natural transition from a full fleged Linux distro with huge games and office included to lighter one (MATE) and now to one of the lightest Fluxbox. Fluxbox doesn't come with any junk apps and doesn't even care about basic customization - a total no nonsense, light, fast OS. I recommend following a similar transition to get to know the operations and to ease into Linux if you are coming from Windows - you gradually even pick up a lot of basic terminal coding along the way. The downside of a new OS, however, is how much time it takes to get back all your packages so your old codes work perfectly fine.


Here I list out the first steps to get your Linux system up and running quickly as I have had to replicate most of these process in the n fresh installs I have done so far. 

### For R Studio

While installing R and R-Studio couldn't be more [simpler](https://www.rstudio.com/products/rstudio/download-server/debian-ubuntu/), Linux doesn't come pre-installed with several dependencies and system packages. So below are a bunch of dependencies you may need to install (through the terminal) which I got through non-zero exits error while installing R packages. Please note that your linux system may be different and may need different dependencies.


_- sudo apt-get install libcurl4-openssl-dev
- sudo apt install libudunits2-dev
- sudo apt install libssl-dev
- sudo apt install libprotobuf-dev
- sudo apt install libjq-dev
- sudo apt install libfontconfig1-dev
- sudo apt install unixodbc-dev
- sudo apt install protobuf-compiler
- sudo apt install libprotobuf-dev
- sudo apt install libjq-dev
- sudo apt install libavfilter-dev
- sudo apt-get install cargo
- sudo apt install libv8-dev
- sudo apt install cmake
- sudo add-apt-repository ppa:marutter/c2d4u
- sudo apt-get install -y libssl-dev
- sudo apt install libgdal-dev
- sudo apt-get install gdal-bin proj-bin_

Two newly discovered missing packages in the MX Linux distro:

_- sudo apt-get install gfortran
- sudo apt install r-cran-mvtnorm_

### For Python

Again super simple [instructions](https://docs.anaconda.com/anaconda/install/linux/) to follow. 

Another thing that is religiously required to be done before installing Linux is to get all of your conda environments downloaded (as you might have added new modules and updated it). The documentations are the best place to go, although there are ton of other resources as well. Use the code:

To list out the environments you have: 

- conda env list


