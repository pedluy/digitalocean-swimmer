[![Build Status](https://jenkins.loorea.com/buildStatus/icon?job=Digitalocean Swimmer)](https://jenkins.loorea.com/buildStatus/icon?job=Digitalocean Swimmer/)
[![Licence](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/yassirh/digital-ocean-swimmer/master/LICENSE.md)

# DigitalOcean Swimmer App

[![Google Play](https://cloud.githubusercontent.com/assets/16354543/11904684/0667026e-a5c2-11e5-9f53-4614cc53e01f.png)](https://play.google.com/store/apps/details?id=com.yassirh.digitalocean)

# Description

Open-source application for the users of DigitalOcean who wish to manage their droplets, snapshots, images and domains via an android application.

This application allows you to :

* Manage your droplets : create, reboot, boot, shutdown, reset password, resize, take snapshots, enable/disable backups, rename and destroy.

* Manage domains : create, update and destroy.

* Manage domain records : create, update and destroy.

* Manage SSH Keys : create, update and destroy.

* Multiple accounts support.

Source code : https://github.com/yassirh/digital-ocean-swimmer

For issues or feature requests open a new issue here : https://github.com/yassirh/digital-ocean-swimmer/issues

# Building from the source (Android Studio)

To build the application from the source :

1) In your <user>/.gradle folder add two files gradle.properties & digitaloceanswimmer.properties
 
2) Create a file digitaloceanswimmer.properties with the following content :

```
keystore={{Path to your keystore}}

keystore.password={{Keystore password}}

keyAlias={{Key alias}}

keyPassword={{Key password}}

apkOutputDir={{folder to output the generated sdk}}
```

3) in case you don't have a key : http://developer.android.com/tools/publishing/app-signing.html

4) In your gradle.properties file add the following line : 

```
DigitalOceanSwimmer.properties={{path to digitaloceanswimmer.properties}}
```

5) Open project with Android Studio & don't forget to submit a pull request 
