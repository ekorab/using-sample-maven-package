# using-sample-maven-package

project to consume packages from github registry

right now consuming [this project](https://github.com/ekorab/sample-maven-package)
![main status](https://github.com/github/docs/actions/workflows/maven.yml/badge.svg)

## building

```bash
ekorab@k:~/git/sample-maven-package> TOKEN=<github token here> mvn -s settings.xml clean install
```
