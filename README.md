<!-- SPDX-FileCopyrightText: no
     SPDX-License-Identifier: CC0-1.0
-->

# Calamares: Distribution-Independent Installer Framework
---------

[![Current issue](https://img.shields.io/badge/issue-in_progress-FE9B48)](https://github.com/calamares/calamares/labels/hacking%3A%20in-progress)
[![GitHub release](https://img.shields.io/github/release/calamares/calamares.svg)](https://github.com/calamares/calamares/releases)
[![GitHub Build Status](https://img.shields.io/github/workflow/status/calamares/calamares/ci?label=GH%20build)](https://github.com/calamares/calamares/actions?query=workflow%3Aci)
[![GitHub license](https://img.shields.io/github/license/calamares/calamares.svg)](https://github.com/calamares/calamares/blob/calamares/LICENSE)


> Calamares is a distribution-independent system installer, with an advanced partitioning
> feature for both manual and automated partitioning operations. Calamares is designed to
> be customizable by distribution maintainers without need for cumbersome patching,
> thanks to third party branding and external modules support.

---
# calamares-Kiyung

This calamares-kiyung exstension __support advanced modules for better user experience__ that autofill existing user name on the "users" module and do backup important file to usb on the "partition" module


---

## Advanced module

 - [user](https://github.com/yonghanJu/calamares/tree/calamares/src/modules/users/) 


 - [partition](https://github.com/yonghanJu/calamares/tree/calamares/src/modules/partiton/) 

---

## Demonstration video

The following video demonstrates shortly how this extension would work.    
Click [here](https://www.youtube.com/watch?v=Ye19DK44Wdc) to view the demonstration.
    
---

## Quickly Getting Started

**Don't EVER run deploycala.py on a non-live system.** 
Please read [Wiki](https://github.com/calamares/calamares/wiki/Develop-Guide#build).

###### 1. Set up Envrionment
     
```
$ curl -LO https://calamares.io/deploycala.py
$ python3 deploycala.py
```

###### 2. Make build directory
     
```
$ git clone https://github.com/yonghanJu/calamares-Kiyung.git
$ mkdir calamares-Kiyung/build
$ cd calamares-Kiyung/build
$ cp ../settings.conf .
```

###### 3. Build
     
```
$ cmake -DCMAKE_BUILD_TYPE=Debug ..
$ make
```

###### 4. Run
     
```
$ sudo calamares -d
```

---

### Contributer

**Team Kiyung**

name: Ju yong han <br>
email: ju990828@konkuk.ac.kr <br>
site: https://yonghanju.github.io/
    
 <br>
 
name: Choi yong jae <br>
email: yongjae.choi20@gmail.com
