
<div align="center">
<img src="https://www.itsm-ng.org/pics/itsmng-logo.png" style="width: 500px; margin-bottom: 30px;"/>
</div>

# Welcome to ITSM-NG

ITSM-NG is a GLPI fork with the objective of offering a strong community component and relevant technological choices. It is an ITSM software that allow you to manage all your assets from technical information to financial and contractual details.

## How to install

We propose three installation methods :

* [From source](https://wiki.itsm-ng.org/install/)
* [With docker](https://wiki.itsm-ng.org/docker-install/)
* [With repository](https://wiki.itsm-ng.org/repo-install/) (RPM/DEB)
* [With LXC template](https://wiki.itsm-ng.org/lxc-install/)

To allow the installation of ITSM-NG, it is necessary to have a Linux (recommended) or Windows server with the following services installed and configured :

* Apache, Nginx, ISS, etc 
* MariaDB or MySQL
* PHP

Create the MySQL database and user.

Download [the latest release](https://github.com/itsmng/itsm-ng/releases), uncompress and go to http://localhost/itsmng.

Follow the installation steps and enjoy ITSM-NG !

You will find the complete documentation here : [ITSM-NG installation](https://wiki.itsm-ng.org/install/)

## Third party tools

* [Android application](https://github.com/itsmng/tech-android-app/releases) : this application allow to create and change ITSM-NG tickets from your organisation.
* [Grafana template](https://github.com/itsmng/grafana-template) : we provide a default template which can be used in order to provide an ITSM-NG reporting in Grafana.
* Various plugin catalog :
    * [Whitelabel](https://github.com/itsmng/whitelabel/releases) : allow its users to modify the look of their itsm deployment, unifying their internal software's appearance.
    * [Edit traduction](https://github.com/itsmng/edittraduction/releases) : edit traduction file directly in the web interface.
    * [Holidays](https://github.com/itsmng/holidays/releases) : set holidays from over 40 countries.
    * [Split dropdown](https://github.com/itsmng/splitdropdown/releases) : split a dropdown into multiple dropdowns based on the level of splitting.
    * [Stock management](https://github.com/itsmng/stockmanagement/releases) : allows user to configure an alert threshold for a type of material or for a manufacturer/model depending on a status.
    * GLPI plugin compatibilities (up to version 9.5.7)

## Features

ITSM-NG provide a lot of differents feature in order to help you manage your IT Services on a daily basis :

* Helpdesk
* Project / Assets / Financial management
* Administration
* Configuration

Recently added :

* [OpenID Connect](https://wiki.itsm-ng.org/features/oidc/) : allows clients to verify the identity of an end user based on the authentication performed by an authorization server.
* [Accessibility](https://wiki.itsm-ng.org/features/accessibility/) : 
    * Keyboard shortcut
    * Special font for dyslexia
    * Zoom
* [Chat notification](https://wiki.itsm-ng.org/features/chat-notification/) : allows you to send chat notification from ITSM-NG to your chat application.

![ITSM-NG preview](https://www.itsm-ng.org/pics/itsmng-preview.png)

## Useful links

[Release](https://github.com/itsmng/itsm-ng/releases) | [Site](https://www.itsm-ng.com/) | [Wiki](https://wiki.itsm-ng.org/) | [Roadmap](https://github.com/orgs/itsmng/projects/1)

## How to contribute

* Fork it !
* Create your feature branch: git checkout -b itsm_my-new-feature
* Add your changes: git add folder/file1.php
* Commit your changes: git commit -m 'Add some feature'
* Push to the branch: git push origin itsm_my-new-feature
* Submit a pull request !
