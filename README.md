# using-sample-maven-package

project to consume packages from github registry

right now consuming [this project](https://github.com/ekorab/sample-maven-package)

 ![Build Status](https://github.com/ekorab/using-sample-maven-package/actions/workflows/maven.yml/badge.svg)

## building

```bash
ekorab@k:~/git/sample-maven-package> TOKEN=<github token here> mvn -s settings.xml clean install
```
