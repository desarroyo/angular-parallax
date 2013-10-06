angular-parallax
==============

Install
-------

    $ bower install angular-parallax

Usage
-----

```js
angular.module('myApp', ['duParallax']).
  controller('MyCtrl', function($scope, parallaxHelper){
    $scope.background = parallaxHelper.createAnimator(0.3);
  }
);
```

```html
<section ng-controller="MyCtrl">
  <img src="img.png" du-parallax y="background" alt="" />
</section>

<script src="//ajax.googleapis.com/ajax/libs/angularjs/1.2.0-rc.2/angular.min.js"></script>
<script src="//raw.github.com/durated/angular-scroll/master/angular-scroll.min.js"></script>
<script src="//raw.github.com/durated/angular-parallax/master/angular-parallax.min.js"></script>
```

Building
--------

    $ npm install
    $ grunt
