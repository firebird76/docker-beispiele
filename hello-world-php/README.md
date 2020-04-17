# Apache mit PHP 7
Ein einfacher PHP 7 Server mit index.php.

Herunterladen der refernzierten Images aus dem *Dockerfile* und erstellen des zu startenden *Docker-Image*
```
docker build -t hello-world-php .
```
Das erstelle Docker-Image als Container starten 
```
docker run -p 8080:80 hello-world-php

```
Der gestartete Container kann nun unter 127.0.0.1:8080 aufgerufen werden. 
