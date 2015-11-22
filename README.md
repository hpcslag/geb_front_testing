# Geb front testing
Groovy based use geb + selenium + gradle + maven do front-end website testing

Reference guide:　[啟動 Geb - 網站自動化測試之美](http://learngeb-ebook.readbook.tw/)

## install
Java SE (Runtime), you need setup JAVA_HOME path (x32bit)
Groovy
Gradle
Maven

## MVN Package (Groovy)
[MVNRepository](http://mvnrepository.com/) / [Geb-Core](http://mvnrepository.com/artifact/org.gebish/geb-core/0.12.2)
```
import groovy.grape.Grape
Grape.grab(group: 'org.gebish', module: 'geb-core', version: '0.12.2')
Grape.grab(group: 'org.seleniumhq.selenium', module: 'selenium-firefox-driver', version: '2.46.0')
```

