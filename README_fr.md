# Dispatch pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/dispatch.svg)](https://dash.yunohost.org/appci/app/dispatch) ![](https://ci-apps.yunohost.org/ci/badges/dispatch.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/dispatch.maintain.svg)  
[![Installer Dispatch avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=dispatch)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Dispatch rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble

**Version incluse :** 0.7

## Captures d'écran

![](https://camo.githubusercontent.com/335eb6270d56b9218d3b0fb21f3779f36604a918/68747470733a2f2f6b686c69656e672e636f6d2f64697370617463682e706e673f31)

## Démo

* [Démo officielle](https://dispatch.khlieng.com/connect)

## Configuration

## Documentation

 * Documentation officielle : 
 * Documentation YunoHost : https://yunohost.org/fr/app_dispatch

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP est-elle prise en charge ? **Non**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/dispatch.svg)](https://ci-apps.yunohost.org/ci/apps/dispatch/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/dispatch.svg)](https://ci-apps-arm.yunohost.org/ci/apps/dispatch/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/navidrome_ynh/issues
 * Site de l'application : https://dispatch.khlieng.com/connect
 * Dépôt de l'application principale : https://github.com/khlieng/dispatch
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/dispatch_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/dispatch_ynh/tree/testing --debug
ou
sudo yunohost app upgrade dispatch -u https://github.com/YunoHost-Apps/dispatch_ynh/tree/testing --debug
```
