# Dispatch for YunoHost

[![Integration level](https://dash.yunohost.org/integration/dispatch.svg)](https://dash.yunohost.org/appci/app/dispatch) ![](https://ci-apps.yunohost.org/ci/badges/navidrome.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/dispatch.maintain.svg)  
[![Install Dispatch with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=dispatch)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Dispatch quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

**Shipped version:** 0.7

## Screenshots

![](https://camo.githubusercontent.com/335eb6270d56b9218d3b0fb21f3779f36604a918/68747470733a2f2f6b686c69656e672e636f6d2f64697370617463682e706e673f31)

## Demo

* [Official demo](https://dispatch.khlieng.com/connect)

## Configuration

## Documentation

 * Official documentation: 
 * YunoHost documentation: https://yunohost.org/en/app_dispatch

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **No**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/dispatch.svg)](https://ci-apps.yunohost.org/ci/apps/dispatch/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/dispatch.svg)](https://ci-apps-arm.yunohost.org/ci/apps/dispatch/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/dispatch_ynh/issues
 * Upstream app repository: https://github.com/khlieng/dispatch
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/dispatch_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/dispatch_ynh/tree/testing --debug
or
sudo yunohost app upgrade dispatch -u https://github.com/YunoHost-Apps/dispatch_ynh/tree/testing --debug
```
