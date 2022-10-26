<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# LibreERP for YunoHost

[![Integration level](https://dash.yunohost.org/integration/libreerp.svg)](https://dash.yunohost.org/appci/app/libreerp) ![Working status](https://ci-apps.yunohost.org/ci/badges/libreerp.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/libreerp.maintain.svg)  
[![Install LibreERP with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=libreerp)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install LibreERP quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

LibreERP is a suite of web based open source business apps. LibreERP is a fork of Odoo Community Edition.

The main LibreERP Apps include an Open Source CRM, Website Builder, eCommerce, Project Management, Billing &amp; Accounting, Point of Sale, Human Resources, Marketing, Manufacturing, Purchase Management, ...

LibreERP Apps can be used as stand-alone applications, but they also integrate seamlessly so you get a full-featured Open Source ERP when you install several Apps.


**Shipped version:** 16.0~ynh1

**Demo:** https://www.odoo.com/trial
## Disclaimers / important information

**WARNING**: LibreERP is a complex app. **DO NOT USE THIS PACKAGE** to run your business unless you know what you are doing!!! If you don't, you should consider to ask for help from a professionnal!

**IMPORTANT:** This app MUST be installed on a domain's root!
https://erp.example.com/ will work
https://example.com/erp/ will NOT work

To connect on your LibreERP
-----------
- Go on https://YOURDOMAIN/web
- Login as "admin" with the master password you provided during installation

About licences
-----------
LibreERP 8.0 is under AGPL-3.0
Next version are under LGPL-3.0
LibreERP is forked from Odoo Community Edition. The name is change due to Odoo trademark policy.

## Documentation and resources

* Official app website: <https://odoo.com>
* Official user documentation: <https://www.odoo.com/documentation/15.0/applications.html>
* Official admin documentation: <https://www.odoo.com/documentation/15.0/administration.html>
* Upstream app code repository: <https://github.com/odoo/odoo>
* YunoHost documentation for this app: <https://yunohost.org/app_libreerp>
* Report a bug: <https://github.com/YunoHost-Apps/libreerp_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/libreerp_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/libreerp_ynh/tree/testing --debug
or
sudo yunohost app upgrade libreerp -u https://github.com/YunoHost-Apps/libreerp_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
