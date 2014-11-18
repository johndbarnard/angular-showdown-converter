#angular-showdown-converter

Inject showdown into Angular controllers and services


## Install

```
bower install angular-showdown-converter
```

Add the script to your html page

```
bower_components/angular-showdown-converter/angular-showdown-converter.js
```


Add the dependency to your app

```
angular.module('app', ['showdown'])
```


## Usage

You can refer to it in your controllers:

```
angular.module('app')
.controller('MainCtrl', function ( $window, showdown) {
```
