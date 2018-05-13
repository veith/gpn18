# \<showcase\>

Die einzelnen Schritte des showcases könnt ihr direkt auschecken um sie miteinander zu vergleichen.

Macht als erstes einen `bower install`

`git checkout init` stellt den anfangszustand her.

`git checkout step1` eine weitere Lampe wird hinzugefügt.

`git checkout step2` erste Lampe wird entfernt.

`git checkout step3` weiterer Schalter wird hinzugefügt.

`git checkout step4` erste Lampe wird wieder hinzugefügt.

`git checkout step5` Lampen können getrennt geschaltet werden.

`git checkout step6` dritte Lampe für Gruppe B hinzugefügt.

`git checkout step7` color-pad hinzugefügt und eingebaut.









## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
