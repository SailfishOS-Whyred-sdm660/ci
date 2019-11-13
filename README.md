# SailfishOS for Xiaomi Redmi Note 5/5 Plus

* 3.2.0.12   - [![pipeline status](https://gitlab.com/sailfishos-porters-ci/vince-ci/badges/3.2.0.12/pipeline.svg)](https://gitlab.com/sailfishos-porters-ci/vince-ci/commits/3.2.0.12)
* 3.1.0.12   - [![pipeline status](https://gitlab.com/sailfishos-porters-ci/vince-ci/badges/3.1.0.12/pipeline.svg)](https://gitlab.com/sailfishos-porters-ci/vince-ci/commits/3.1.0.12)
* 3.0.3.9   - [![pipeline status](https://gitlab.com/sailfishos-porters-ci/vince-ci/badges/3.0.3.9/pipeline.svg)](https://gitlab.com/sailfishos-porters-ci/vince-ci/commits/3.0.3.9)
* 3.0.2.8   - [![pipeline status](https://gitlab.com/sailfishos-porters-ci/vince-ci/badges/3.0.2.8/pipeline.svg)](https://gitlab.com/sailfishos-porters-ci/vince-ci/commits/3.0.2.8)
* 3.0.1.11  - [![pipeline status](https://gitlab.com/sailfishos-porters-ci/vince-ci/badges/3.0.1.11/pipeline.svg)](https://gitlab.com/sailfishos-porters-ci/vince-ci/commits/3.0.1.11)
* 3.0.0.8   - [![pipeline status](https://gitlab.com/sailfishos-porters-ci/vince-ci/badges/3.0.0.8/pipeline.svg)](https://gitlab.com/sailfishos-porters-ci/vince-ci/commits/3.0.0.8)


This repository uses gitlab-ci to build the sailfish images for the Xiaomi Redmi Note 5/5 Plus

![Xiaomi Redmi 5 Plus](https://cdn2.gsmarena.com/vv/pics/xiaomi/xiaomi-redmi-5-plus-2.jpg "Xiaomi Redmi 5 Plus")

## Device specifications

Basic   | Spec Sheet
-------:|:----------
CPU     | Octa-core 2.02 GHz ARM Cortex A53
Chipset | Qualcomm Snapdragon 625, MSM8953
GPU     | Adreno 506
ROM     | 32/64GB 
RAM     | 3/4GB
Android | 7.1.2
Battery | 4000 mAh
Display | 1080x2160 pixels, 5.99
Rear Camera  | 12MP, PDAF
Front Camera | 5 MP



# Files

[vince.env](https://gitlab.com/sailfishos-porters-ci/vince-ci/blob/master/vince.env) contains all the environment variables required for the process. On every release, version number is changed in the master branch and a new tag is created with the release number to trigger the build process.

[Jolla-@RELEASE@-vince-@ARCH@.ks](https://gitlab.com/sailfishos-porters-ci/vince-ci/blob/master/Jolla-@RELEASE@-vince-@ARCH@.ks) file is the kickstart file which is used by PlatformSDK image, this files contains device specific repositories, Repositories can be changed by from devel to testing or vice versa.

[run-mic.sh](https://gitlab.com/sailfishos-porters-ci/vince-ci/blob/master/run-mic.sh) is a simple bash script, which executes the build.

# Download

[Download the latest build](https://gitlab.com/sailfishos-porters-ci/vince-ci/-/jobs?scope=finished)

# Source code
[https://github.com/Sailfish-On-Vince](https://github.com/Sailfish-On-Vince)
