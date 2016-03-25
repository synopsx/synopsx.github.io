# SynopsX

SynopsX is a lightweith framework which goal is to easily publish and expose XML scholarly corpora. It’s a full XQuery web application built with the native XML database BaseX.


## SynopsX’ Prerequisits

SynopsX requires **[BaseX > 8.0](http://basex.org/products/download/all-downloads/)**

Since BaseX 8.0, Java 7 is required. We recommend using Java 8.

SynopsX uses [Saxon](http://sourceforge.net/projects/saxon) for XSLT transformations

### To install the last JDK from Oracle

- To download the last JDK from the Oracle Page : http://www.objis.com/formation-java/tutoriel-java-installation-jdk.html. - Before downloading choose the appropriate version (system + processor: i.e. Mac OSX x64)
- Go to you Downloads directory and double-click on the installation file: i.e.: jdk-8u60-macosx-x64.dmg or jdk-8u60-macosx-x64.exe
- Complete installation
- Open a terminal to check the Java JDK version (`java --version`)

### BaseX Installation

- Install BaseX by downloading the latest ZIP Archive from <http://basex.org/products/download/all-downloads/>
- Unzip the Archive
- Run BaseX to check if it works properly

### Saxon Installation

- download from (choose the zipped directory, on top of the page): <http://sourceforge.net/projects/saxon/files/>
- unzip the downloaded files
- put the content (the .jar files) inside `basex/lib`


## Installing SynopsX

### from git

- Fork SynopsX’ repo
- Clone SynopsX on your computer
- Move the download directory in `basex/webapp/`

### with


## Using SynopsX

SynopsX is directly available on localhost when you start BaseX in HTTP server.

To start BaseX in HTTP server
```bash
  cd <path-to-basex>
  sh ./bin/basexhttp # run basex in http server
```

In a browser, reach  [localhost:8984/](localhost:8984/)
