<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# LimeSurvey for YunoHost

[![Integration level](https://dash.yunohost.org/integration/limesurvey.svg)](https://dash.yunohost.org/appci/app/limesurvey) ![](https://ci-apps.yunohost.org/ci/badges/limesurvey.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/limesurvey.maintain.svg)  
[![Install LimeSurvey with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=limesurvey)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install LimeSurvey quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Creation and distribution survey tool

**Shipped version:** 5.2.6~ynh1



## Screenshots

![](./doc/screenshots/create_html_statistic_screen.png)

## Disclaimers / important information

## YunoHost specific features

* SSO and LDAP are configured.
* Login secured by fail2ban
## Documentation and resources

* Official app website: https://www.limesurvey.org
* Official user documentation: https://help.limesurvey.org
* Official admin documentation: https://manual.limesurvey.org/LimeSurvey_Manual/fr
* Upstream app code repository: https://github.com/LimeSurvey/LimeSurvey
* YunoHost documentation for this app: https://yunohost.org/app_limesurvey
* Report a bug: https://github.com/YunoHost-Apps/limesurvey_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/limesurvey_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/limesurvey_ynh/tree/testing --debug
or
sudo yunohost app upgrade limesurvey -u https://github.com/YunoHost-Apps/limesurvey_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps