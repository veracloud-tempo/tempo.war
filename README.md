# VeraCloud _Tempo_ (free)

VeraCloud _Tempo_ (free) is the free limited edition of [VeraCloud _Tempo_](http://www.veracloud.com/tempo).

VeraCloud _Tempo_ consists of a JavaEE-based runtime deployed as a Web Application Resource (WAR), and a browser-based flow editor. The flow editor derives from [Node-RED](https://nodered.org), but, unlike Node-RED, the runtime and all VeraCloud _Tempo_ nodes are implemented in Java.

## Installation

Before you can install VeraCloud _Tempo_ free [Web Application Resource (WAR)](https://en.wikipedia.org/wiki/WAR_(file_format)) you must have a working installation of a JavaEE container like [Apache Tomcat](https://tomcat.apache.org/download-90.cgi).

Download the latest release of VeraCloud _Tempo_ WAR, rename it to `tempo.war`, and copy it to `$CATALINA_BASE/webapps` folder. Start Tomcat and point a local browser at `http://localhost:8080/tempo`.

![Tempo](https://raw.githubusercontent.com/wiki/veracloud-tempo/tempo.war/screenshots/tempo1.png)
