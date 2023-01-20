<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# YunoRunner for YunoHost

[![Integration level](https://dash.yunohost.org/integration/yunorunner.svg)](https://dash.yunohost.org/appci/app/yunorunner) ![Working status](https://ci-apps.yunohost.org/ci/badges/yunorunner.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/yunorunner.maintain.svg)  
[![Install YunoRunner with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=yunorunner)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install YunoRunner quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

CI runner of YunoHost

**Shipped version:** 2023.01.20~ynh1

## Screenshots

![Screenshot of YunoRunner](./doc/screenshots/screenshot.png)

## Disclaimers / important information

## Limitations

* You need to install [CI_package_check](https://github.com/YunoHost/CI_package_check) using the `install.sh` script before installing YunoRunner
* When YunoRunner is installed, modify the systemd script to add the path of the script `analyseCI.sh`. The default systemd is configured to `/home/CI_package_check/analyseCI.sh`

## Documentation and resources

* Upstream app code repository: <https://github.com/YunoHost/yunorunner>
* YunoHost documentation for this app: <https://yunohost.org/app_yunorunner>
* Report a bug: <https://github.com/YunoHost-Apps/yunorunner_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/yunorunner_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/yunorunner_ynh/tree/testing --debug
or
sudo yunohost app upgrade yunorunner -u https://github.com/YunoHost-Apps/yunorunner_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
