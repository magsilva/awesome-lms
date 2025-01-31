# Awesome LTI Resources
> :warning: This is a personal project. It does not necessarily represent the views of either 1EdTech Consortium nor of my employer. I provide no warranty that the linked resources contain correct informations and/or are functioning properly.

List of awesome resources for learning and developing tools according to the [Learning Tools Interoperability](https://www.imsglobal.org/activity/learning-tools-interoperability) (LTI &copy;) standard created by the 1EdTech Consortium.

![](https://img.shields.io/github/license/scollovati/awesome-lti?style=for-the-badge)
[![](https://img.shields.io/static/v1?label=Gitlab&message=awesome-lti&style=for-the-badge&logo=gitlab)](https://gitlab.com/scollovati/awesome-lti)
[![](https://img.shields.io/static/v1?label=Github&message=awesome-lti&style=for-the-badge&logo=github)](https://github.com/scollovati/awesome-lti)
## Table of Contents

  - [Learning materials](#learning-materials)
  - [Reference Implementations](#reference-implementations)
  - [Libraries and Examples](#libraries-and-examples)

## Learning materials

* [LTI 1.1: from B to C](https://www.youtube.com/watch?v=I0zhjzCxovw&list=PLb5mG7w3UZkM_kx0mbojgDX4qFkGQsXO_&index=1) by Claude Vervoot  ![](https://img.shields.io/badge/playlist-red?logo=YouTube)
* [An Illustrated Guide to OAuth and OpenID Connect](https://www.youtube.com/watch?v=t18YB3xDfXI) by OktaDev ![](https://img.shields.io/badge/playlist-red?logo=YouTube)
* [LTI 1.3 and LTI Advantage Bootcamp](https://github.com/1EdTech/ltibootcamp) by 1EdTech Consortium ![](https://img.shields.io/badge/code-000?logo=GitHub)
* [LTI 1.3 and LTI Advantage Bootcamp](https://www.youtube.com/watch?v=f_6pWiQpg5s&list=PLb5mG7w3UZkPKHODmz5YCkIqnWQEsjMkd) by Claude Vervoot ![](https://img.shields.io/badge/playlist-red?logo=YouTube)
  * [Companion text and code](https://github.com/1EdTech/ltibootcamp) for the bootcamp video by Claude Vervoot ![](https://img.shields.io/badge/code-000?logo=GitHub)
* Build a LTI 1.3 and LTI Advantage Tool with Martin Lenord ![](https://img.shields.io/badge/video-red?logo=YouTube) :
  * [Part 1 - LTI 1.3 Launch](https://www.youtube.com/watch?v=fI-rhSSDU8M) 
  * [Part 2 - Deep Linking Capabilities](https://www.youtube.com/watch?v=EQUEmJFWNbI) 
  * [Part 3 - Assignment & Grades Service](https://www.youtube.com/watch?v=YOg_mZ6bWXg) 
  * [Part 4 - Names & Roles Provisioning Service](https://www.youtube.com/watch?v=1Ux-P8d-L0Q) 
  * [Part 5 - Group Service](https://www.youtube.com/watch?v=MpdsoZiFXuE) 

## Reference Implementations

* [LTI 1.1 and 1.3 saLTIre Tool Consumer/Platform emulator](https://saltire.lti.app/platform) by ceLTIc project
* [LTI 1.1 and 1.3 saLTIre Tool (Provider) emulator](https://saltire.lti.app/tool) by ceLTIc project
* [LTI 1.3 Reference Implementation Platform](https://lti-ri.imsglobal.org/platforms) by 1EdTech Consortium
* [LTI 1.3 Reference Implementation Tool](https://lti-ri.imsglobal.org/lti/tools) by 1EdTech Consortium

## Utilities

* [View & debug LTI requests from within the developer tools](https://github.com/pfgray/lti-debugger) by Paul Gray 
* [JSON Web Token (JWT) Debugger](https://jwt.io/#debugger-io) by Auth0

## Libraries and Examples
> :warning: Before using these libraries and tools verify that their LICENSES allow you to do so.

Demo codes or sample implementations are listed below each library.

### .NET Core
* [LTI 1.3 and LTI Advantage `LtiAdvantage`](https://github.com/LtiLibrary/LtiAdvantage)
* [LTI 1.3 `Tpcly.Lti`](https://github.com/LtiLibrary/LtiAdvantage) by  Jelle Maas


### JAVA

* [LTI 1.1 `basiclti-util`](https://github.com/1EdTech/basiclti-util-java) by 1EdTech Consortium
* [LTI 1.3 and LTI Advantage `lti-13`](https://github.com/UOC/java-lti-1.3) by UOC
* [LTI 1.3 and LTI Advantage `spring-boot-lti-advantage`](https://github.com/UOC/spring-boot-lti-advantage) by UOC
  * [Sample Tool Provider in Spring Boot](https://github.com/UOC/java-lti-1.3-provider-example) by UOC

### Javascript (Node.js)
* [LTI 1.3 and LTI Advantage `ltijs`](https://cvmcosta.me/ltijs/) by Carlos Costa

### Python
* [LTI 1.1 `pylti`](https://github.com/mitodl/pylti) by MIT Office of Digital Learning
  * [Sample Tool Provider in Flask](https://github.com/mitodl/mit_lti_flask_sample) by MIT Office of Digital Learning
  * [Tool Provider Template in Flask ](https://github.com/ucfopen/lti-template-flask) by University of Central Florida - Open Source
* [LTI 1.1 `lti`](https://github.com/pylti/lti) by Python LTI Initiative
  * [Local Tool Consumer in Django](https://github.com/wachjose88/local-lti-consumer) by Josef Wachtler
  * [Tool Provider in Django](https://github.com/wachjose88/django-lti-provider-auth) by Josef Wachtler
* [LTI 1.3 and LTI Advantage `pylti1.3`](https://github.com/dmitry-viskov/pylti1.3) by Dmitry Viskov
  * [Example Tool Provider in Django](https://github.com/dmitry-viskov/pylti1.3-django-example) by Dmitry Viskov
  * [Example Tool Provider in Flask](https://github.com/dmitry-viskov/pylti1.3-flask-example) by Dmitry Viskov
  * [LTI 1.3 Advantage Django reusable app](https://github.com/academic-innovation/django-lti) by UM Center for Academic Innovation

### PHP
* [LTI 1.1 and LTI 1.3 Advantage](https://github.com/celtic-project/LTI-PHP) by ceLTIc project
  * [Rating PHP](https://github.com/celtic-project/Rating-PHP) by ceLTIc project
  * [Integrates the Celtic LTI library with a Laravel app](https://github.com/longhornopen/laravel-celtic-lti) by Longhorn Open Ed Tech
  * [A simple LTI tool for integrating Qualtrics surveys into a course](https://github.com/longhornopen/qualtrics-lti) by Longhorn Open Ed Tech
* [LTI 1.3 Advantage Library](https://github.com/1EdTech/lti-1-3-php-library) by 1EdTech Consortium
  * [LTI 1.3 Advantage Demo Tool](https://github.com/1EdTech/lti-1-3-php-example-tool) by 1EdTech Consortium
* [LTI 1.3 Tool Library](https://github.com/packbackbooks/lti-1-3-php-library) by Packback Book (this is a fork of the 1EdTech Consortium library)
* [LTI 1.3 Core](https://github.com/oat-sa/lib-lti1p3-core) by  Open Assessment Technologies (TAO)
  * [LTI 1.3 Demo Application](https://github.com/oat-sa/demo-lti1p3) by  Open Assessment Technologies (TAO)


# Contributing
Any contribution (`Issues` or `Pull requests`) is welcome!

# License
This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.
See `LICENSE` file for more details.

[![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](LICENSE)
