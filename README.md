# spring-boot-polymer
A template for web applications powered by Spring Boot (server side) and Polymer Starter Kit (client side).

## Included out of the box
From the [Polymer Starter Kit](https://github.com/PolymerElements/polymer-starter-kit) :
* [Polymer](https://www.polymer-project.org/), [Paper](https://elements.polymer-project.org/browse?package=paper-elements), [Iron](https://elements.polymer-project.org/browse?package=iron-elements) and [Neon](https://elements.polymer-project.org/browse?package=neon-elements) elements
* [Material Design](http://www.google.com/design/spec/material-design/introduction.html) layout
* SPA routing with [Page.js](https://visionmedia.github.io/page.js/)
* Unit testing with [Web Component Tester](https://github.com/Polymer/web-component-tester)
* Optional offline setup through [Platinum](https://elements.polymer-project.org/browse?package=platinum-elements) Service Worker elements
* End-to-end Build Tooling (including [Vulcanize](https://github.com/Polymer/vulcanize))

From [Spring Boot](http://projects.spring.io/spring-boot/) :
* A stand-alone, production-grade Spring based Application that you can "just run"

## Getting started
```
git clone https://github.com/jdemeulenaere/spring-boot-polymer.git
cd spring-boot-polymer
npm install -g gulp bower
./gradlew installDeps
./gradlew build
java -jar build/libs/spring-boot-polymer-1.0.0-SNAPSHOT.jar
```
