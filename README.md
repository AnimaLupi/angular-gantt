# angular-gantt 
[![npm version](http://img.shields.io/npm/v/angular-gantt.svg)](https://npmjs.org/package/angular-gantt) 
[![build status](http://img.shields.io/travis/angular-gantt/angular-gantt.svg)](https://travis-ci.org/angular-gantt/angular-gantt)
[![Coverage Status](https://img.shields.io/coveralls/angular-gantt/angular-gantt.svg)](https://coveralls.io/r/angular-gantt/angular-gantt)

## Gantt chart component for AngularJS

[angular-gantt](http://www.angular-gantt.com) provides a gantt chart component to your [AngularJS](https://angularjs.org/) application.

<br/> 

![Angular Gantt](docs/img/angular-gantt.png)

## Try now

Try angular-gantt now using the [Demo Application](http://www.angular-gantt.com/demo).

[Unstable Demo Application](http://rawgit.com/angular-gantt/angular-gantt/master/demo/dist/index.html) is also available.
It is build against [github master](https://github.com/angular-gantt/angular-gantt) branch, and allows to preview 
bleeding edge features, but may be very unstable.

## Features
- Two-way data binding between model and view.
- Advanced calendar support to define holidays and working hours.
- Each task and row has its own properties and behavior.
- Rows and tasks can be sorted and filtered.
- Plugin architecture to add custom features and hooks.
- API to listen events and call methods from your controller.

## Docs

Docs are built using [MkDocs](http://www.mkdocs.org/) and available at
[angular-gantt website](http://www.angular-gantt.com) (stable) and [ReadTheDocs](http://angular-gantt.readthedocs.org/en/latest/)
(master).

## Download

angular-gantt is available through [bower](http://bower.io/) and [npm](https://www.npmjs.org/package/angular-gantt).

    bower install angular-gantt
    npm install angular-gantt
    
or

    bower install angular-gantt#master
    npm install https://github.com/angular-gantt/angular-gantt/tarball/master


[Latest released version](https://github.com/angular-gantt/angular-gantt/releases/latest) is available to 
[download](https://github.com/angular-gantt/angular-gantt/releases/latest) on Github and is the recommended and stable version.

You can also find released version on [CDNjs](http://www.cdnjs.com/) and [jsDelivr](http://www.jsdelivr.com/)

[Master branch version](https://github.com/angular-gantt/angular-gantt/tree/master) contains bleeding edge features, but may be very unstable.

## Dependencies
- [AngularJS](https://angularjs.org) >= 1.3
- [angular-moment](https://github.com/urish/angular-moment) ([momentJS](http://momentjs.com/) wrapper)

## The MIT License

Copyright (c) 2014 Marco Schweighauser, Rémi Alvergnat

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
