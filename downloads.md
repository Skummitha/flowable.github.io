---
id: downloads
title: Downloads
layout: single
permalink: downloads.html
---
Flowable is a compact and highly efficient workflow and Business Process Management (BPM) platform written in Java. At its core is a lightning fast, tried and tested BPMN 2 process engine, coupled with native Case Management (CMMN) and DMN engines.

Just unzip your selected download to a directory of choice and then follow the instructions in the readme.html.  This has links to the docs and the release notes. The User Guide has a quick start section to get you running in minutes.

## Flowable 6

<img class="logo" src="{{ site.baseurl }}/img/v6_character.png" srcset="{{ site.baseurl }}/img/v6_character.png 1x, {{ site.baseurl }}/img/v6_character@2x.png 2x">

Version 6 is the next generation of the process engine that was released in early 2017 after many years of development and testing. This is the focus of new features, scalability and performance.  It is a fork from the Activiti project by its original developers.

<div class="buttons-unit">
  <a href="https://github.com/flowable/flowable-engine/releases/download/flowable-{{site.flowable_version}}/flowable-{{site.flowable_version}}.zip" class="button">Download Flowable v{{site.flowable_version}}</a>
</div>

### Maven
```xml
<dependency>
  <groupId>org.flowable</groupId>
  <artifactId>flowable-engine</artifactId>
  <version>{{site.flowable_version}}</version>
</dependency>
```

### Docker

All Flowable UI apps are available on [Docker Hub](https://hub.docker.com/u/flowable) .

To start the Flowable REST app (with a in memory h2 database):

```bash
docker run -p8080:8080 flowable/flowable-rest
```

The API documentation will be available on [http://localhost:8080/flowable-rest/docs/ ](http://localhost:8080/flowable-rest/docs/) .
(login/password: rest-admin/test)

For a quick start with the full Flowable experience run the 'All-in-One' Docker image. This image contains Flowable IDM, Modeler, Task and Admin UI apps on a Tomcat container with a in memory H2 database. 

```bash
docker run -p8080:8080 flowable/all-in-one
```

Flowable Modeler; [http://localhost:8080/flowable-modeler](http://localhost:8080/flowable-modeler)  
Flowable Task; [http://localhost:8080/flowable-task](http://localhost:8080/flowable-task)  
Flowable Admin; [http://localhost:8080/flowable-admin](http://localhost:8080/flowable-admin)  
Flowable IDM; [http://localhost:8080/flowable-idm](http://localhost:8080/flowable-idm)    

(login/password: admin/test)


Take a look at our [GitHub repo](https://github.com/flowable/flowable-engine/tree/master/docker) for other and more advanced configurations.


## Flowable Enterprise Trial

If you're interested in a 30 day trial of the enterprise version of Flowable, then you
can get a download and trial license in a matter of minutes.  It's a fully functioning version of Flowable Engage (which includes Flowable Work).  Here's more information on the [enterprise products](https://flowable.com/products).

<div class="buttons-unit">
  <a href="https://flowable.com/trial" class="button">Flowable Enterprise Trial </a>
</div>


## Flowable 5

<img class="logo" src="{{ site.baseurl }}/img/v5_character.png" srcset="{{ site.baseurl }}/img/v5_character.png 1x, {{ site.baseurl }}/img/v5_character@2x.png 2x">

Version 5 is the previous release that has been under development by the core Flowable engineers since 2010.  It is a fork from the Activiti project and keeps all the same package names and interfaces.
<div class="buttons-unit">
  <a href="https://github.com/flowable/flowable-engine/releases/download/flowable-{{site.flowable_5_version}}/flowable-{{site.flowable_5_version}}.zip" class="button">Download Flowable v{{site.flowable_5_version}}</a>
</div>

### Maven
```xml
<dependency>
  <groupId>org.flowable</groupId>
  <artifactId>flowable-engine</artifactId>
  <version>{{site.flowable_5_version}}</version>
</dependency>
```

## What's the difference between V5 and V6?

From the perspective of a developer and process designer, at one level there is very little difference between the versions.  If you have built something using V5, then in many cases you just need to change to use the V6 JAR.

On another level, V6 is the future: it's faster, more scalable and more flexible.  The V6 engine is where you want to be going, so start looking at it now to be ready to exploit its new capabilities.

<br><br>

---

Many thanks to EJ Technologies for providing open source licenses for the <a href="https://www.ej-technologies.com/products/jprofiler/overview.html">Java Profiler product JProfiler</a>

<br>

---

<a href="https://www.browserstack.com"><img src="{{ site.baseurl }}/img/browserstack-logo-600x315.png" width="120"></a><br>
Many thanks to <a href="https://www.browserstack.com">BrowserStack</a> for providing open source licenses to test our Flowable UI apps on all the different browsers.
