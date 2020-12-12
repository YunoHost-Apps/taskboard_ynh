# TaskBoard pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/taskboard.svg)](https://dash.yunohost.org/appci/app/taskboard) ![](https://ci-apps.yunohost.org/ci/badges/taskboard.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/taskboard.maintain.svg)  
[![Installer TaskBoard pour YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=taskboard)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer TaskBoard rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
TaskBoard est une application inspirée de Kanban pour suivre les choses à faire.
L'objectif de TaskBoard est de fournir une interface simple et propre à une application fonctionnelle et minimale pour suivre les tâches. Il n'essaye pas d'être le prochain Trello ou LeanKit.
TaskBoard permet de commencer facilement à suivre tout ce que vous devez faire. L'aspect visuel d'un tableau permet des vérifications d'état faciles et peut être motivant pour les utilisateurs qui souhaitent déplacer leurs tâches vers la colonne suivante.

**Version incluse :** 1.0.2

## Captures d'écran

![](https://taskboard.matthewross.me/img/boards.043340f1.png)

## Démo

* [Démo officielle](https://taskboard.matthewross.me/demo)

## Documentation

 * Documentation officielle : https://taskboard.matthewross.me/docs/quick-start
 * Documentation YunoHost :  https://yunohost.org/#/app_taskboard_fr

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? **Non**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/taskboard%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/taskboard/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/taskboard%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/taskboard/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/taskboard_ynh/issues
 * Site de l'application : https://taskboard.matthewross.me/
 * Dépôt de l'application principale : https://github.com/kiswa/TaskBoard
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing --debug
or
sudo yunohost app upgrade taskboard -u https://github.com/YunoHost-Apps/taskboard_ynh/tree/testing --debug
```
