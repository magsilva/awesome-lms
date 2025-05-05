# Awesome resources for Learning Management Systems

## Learning management system (LMS)
* [Adapt Framework](https://github.com/adaptlearning/adapt_framework): Javascript framework and authoring tool for fully responsive, multi-device, HTML5 e-learning content.
  * [xAPI Adapt Framework](https://github.com/adaptlearning/adapt-contrib-xapi): Extension for Adapt Framework that enables xAPI support.

## Learning Tools Interoperability (LTI)

### Learning materials
* [LTI 1.1: from B to C](https://www.youtube.com/watch?v=I0zhjzCxovw&list=PLb5mG7w3UZkM_kx0mbojgDX4qFkGQsXO_&index=1) by Claude Vervoot  ![](https://img.shields.io/badge/playlist-red?logo=YouTube)
* [An Illustrated Guide to OAuth and OpenID Connect](https://www.youtube.com/watch?v=t18YB3xDfXI) by OktaDev ![](https://img.shields.io/badge/playlist-red?logo=YouTube)
* [LTI 1.3 and LTI Advantage Bootcamp activities and sample code in Python](https://github.com/1EdTech/LTI-bootcamp-python/tree/main?tab=readme-ov-file) by 1EdTech Consortium ![](https://img.shields.io/badge/code-000?logo=GitHub)
* [LTI 1.3 and LTI Advantage Bootcamp](https://www.youtube.com/watch?v=f_6pWiQpg5s&list=PLb5mG7w3UZkPKHODmz5YCkIqnWQEsjMkd) by Claude Vervoot ![](https://img.shields.io/badge/playlist-red?logo=YouTube)
  * [Companion text and code](https://github.com/1EdTech/ltibootcamp) for the bootcamp video by Claude Vervoot ![](https://img.shields.io/badge/code-000?logo=GitHub)
* Build a LTI 1.3 and LTI Advantage Tool with Martin Lenord ![](https://img.shields.io/badge/video-red?logo=YouTube) :
  * [Part 1 - LTI 1.3 Launch](https://www.youtube.com/watch?v=fI-rhSSDU8M) 
  * [Part 2 - Deep Linking Capabilities](https://www.youtube.com/watch?v=EQUEmJFWNbI) 
  * [Part 3 - Assignment & Grades Service](https://www.youtube.com/watch?v=YOg_mZ6bWXg) 
  * [Part 4 - Names & Roles Provisioning Service](https://www.youtube.com/watch?v=1Ux-P8d-L0Q) 
  * [Part 5 - Group Service](https://www.youtube.com/watch?v=MpdsoZiFXuE)
* [Getting Started with LTI](https://blackboard.github.io/lti/getting-started-with-lti): by Blackboard

### Reference Implementations
* [LTI 1.1 and 1.3 saLTIre Tool Consumer/Platform emulator](https://saltire.lti.app/platform) by ceLTIc project
* [LTI 1.1 and 1.3 saLTIre Tool (Provider) emulator](https://saltire.lti.app/tool) by ceLTIc project
* [LTI 1.3 Reference Implementation Platform](https://lti-ri.imsglobal.org/platforms) by 1EdTech Consortium
* [LTI 1.3 Reference Implementation Tool](https://lti-ri.imsglobal.org/lti/tools) by 1EdTech Consortium

### Utilities
* [View & debug LTI requests from within the developer tools](https://github.com/pfgray/lti-debugger) by Paul Gray 
* [JSON Web Token (JWT) Debugger](https://jwt.io/#debugger-io) by Auth0

### Libraries and Examples
Demo codes or sample implementations are listed below each library.

#### .NET Core
* [LTI 1.3 and LTI Advantage `LtiAdvantage`](https://github.com/LtiLibrary/LtiAdvantage)
* [LTI 1.3 `Tpcly.Lti`](https://github.com/LtiLibrary/LtiAdvantage) by  Jelle Maas

#### JAVA
* [LTI 1.1 `basiclti-util`](https://github.com/1EdTech/basiclti-util-java) by 1EdTech Consortium
* [LTI 1.3 and LTI Advantage `lti-13`](https://github.com/UOC/java-lti-1.3) by UOC
* [LTI 1.3 and LTI Advantage `spring-boot-lti-advantage`](https://github.com/UOC/spring-boot-lti-advantage) by UOC
  * [Sample Tool Provider in Spring Boot](https://github.com/UOC/java-lti-1.3-provider-example) by UOC

#### Javascript, Typescript, NodeJS
* [LTI 1.3 and LTI Advantage `ltijs`](https://cvmcosta.me/ltijs/) by Carlos Costa
* [Enable LTI 1.3 Service](https://aws-samples.github.io/enable-lti/) by AWS
* [LTI 1.3 Tool for testing Launches, Caliper, and Outcomes](https://github.com/blackboard/BBDN-LTI-Tool-Provider-Node) by Blackboard Inc.

#### Python
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

#### PHP
* [LTI 1.1 and LTI 1.3 Advantage](https://github.com/celtic-project/LTI-PHP) by ceLTIc project
  * [Rating PHP](https://github.com/celtic-project/Rating-PHP) by ceLTIc project
  * [Integrates the Celtic LTI library with a Laravel app](https://github.com/longhornopen/laravel-celtic-lti) by Longhorn Open Ed Tech
  * [A simple LTI tool for integrating Qualtrics surveys into a course](https://github.com/longhornopen/qualtrics-lti) by Longhorn Open Ed Tech
* [LTI 1.3 Advantage Library](https://github.com/1EdTech/lti-1-3-php-library) by 1EdTech Consortium
  * [LTI 1.3 Advantage Demo Tool](https://github.com/1EdTech/lti-1-3-php-example-tool) by 1EdTech Consortium
* [LTI 1.3 Tool Library](https://github.com/packbackbooks/lti-1-3-php-library) by Packback Book (this is a fork of the 1EdTech Consortium library)
* [LTI 1.3 Core](https://github.com/oat-sa/lib-lti1p3-core) by  Open Assessment Technologies (TAO)
  * [LTI 1.3 Demo Application](https://github.com/oat-sa/demo-lti1p3) by  Open Assessment Technologies (TAO)

#### Ruby
* [LTI Advantage](https://github.com/atomicjolt/atomic_lti) by  Atomic Jolt, Inc. 


## xAPI

### Standard
* [Overview](https://xapi.com/overview/)
* [Specification](https://github.com/adlnet/xAPI-Spec)
* [IEEE 9274.1.1 xAPI Base Standard](https://opensource.ieee.org/xapi/xapi-base-standard-documentation)
* [IEEE 9274.2.1 xAPI Profile Standard](https://adlnet.github.io/xapi-profiles/xapi-profiles-about.html)

### API implementation in LMS
* [Moodle support for xAPI](https://moodledev.io/docs/5.0/apis/subsystems/xapi): Technical explanation on how the xAPI Moodle integration library works.

### Examples and tutorials
* [ADL's resources](https://adlnet.github.io/#xapi): several examples by ADL regarding xAPI.
* [xAPI Prototypes](https://xapi.com/prototypes/): several examples by Rustici regarding xAPI.

### Software
#### xAPI
* [Logstore xAPI](https://moodle.org/plugins/logstore_xapi) Moodle plugin that emits xAPI statements to a Learning Record Store (LRS).
* [ADL xAPIWrapper](https://github.com/adlnet/xAPIWrapper): Javascript wrapper for xAPI, for usage in client applications.
* [TinCanJS](https://github.com/RusticiSoftware/TinCanJS): Javascript library for xAPI, for usage in client applicatons, by Rustici Software.
* [xapijs](https://github.com/xapijs/xapi): Strongly typed JavaScript library for enabling learning content and learning systems to speak to each other using xAPI specification
* [Adopters of xAPI](https://xapi.com/adopters/): List of vendors that uses or provides tools for xAPI.
#### LRS
* [ADL Learning Record Store](https://github.com/adlnet/ADL_LRS) Open source Learning Record Store (LRS), used to store learning data collected with the xAPI.
* [Learning Locker](https://github.com/LearningLocker/learninglocker): Open source Learning Record Store (LRS) implementing the xAPI (Tin Can API) using JavaScript.
* [SQL LRS](https://www.sqllrs.com/): Open source Learning Record Store (LRS), used to store learning data collected with the xAPI in a SQL database.
* [lxHive](https://github.com/g3i/lxHive): Open source Learning Record Store (LRS), impelemented in PHP.
* [Ralph](https://github.com/openfun/ralph): Learning Record Store (LRS), impelemented in Python.
* [SCORM Cloud](https://cloud.scorm.com): Cloud provider for SCORM and xAPI solutions.


## Caliper Analytics

### Standard
* [Overview](https://www.1edtech.org/standards/caliper)
* [Specification](https://www.imsglobal.org/spec/caliper/latest/)


# Contributing
Any contribution (`Issues` or `Pull requests`) is welcome!

# License
This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.
See `LICENSE` file for more details.

[![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](LICENSE)
