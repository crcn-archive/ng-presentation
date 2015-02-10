## demystifying angular.js
## Understanding AngularJS Internals
## Angular anti-patterns
## Angular internals

Summary:

Understanding AngularJS internals: the philosophies & pitfalls of AngularJS to help
you build more scalable applications.

- resource:
  - philosophy:
    - http://glennstovall.com/blog/2013/06/27/angularjs-an-overview/
  - internals & pitfalls:
    - http://stackoverflow.com/questions/18697745/apply-vs-digest-in-directive-testing
    - http://www.smashingmagazine.com/2015/01/22/angularjs-internals-in-depth/
    - http://teropa.info/blog/2013/11/03/make-your-own-angular-part-1-scopes-and-digest.html
    - https://news.ycombinator.com/item?id=6630156
    - https://thecodebarbarian.wordpress.com/2014/01/31/what-you-need-to-know-about-angularjs-data-binding/
    - http://branchandbound.net/blog/web/2013/08/some-angularjs-pitfalls/
    - http://thenittygritty.co/angularjs-pitfalls-using-scopes
    - http://nathanleclaire.com/blog/2014/04/19/5-angularjs-antipatterns-and-pitfalls/
    - http://eviltrout.com/2013/06/15/ember-vs-angular.html
    - http://ruoyusun.com/2013/05/25/things-i-wish-i-were-told-about-angular-js.html
  - testing:
    - https://docs.angularjs.org/guide/e2e-testing
    - https://docs.angularjs.org/guide/unit-testing
    - https://github.com/angular/angular-seed

Angular Philosophy:

- use POJO objects
- testability

- dirty type checking - how angular works
- scope.$apply()
  - used in $timeout()
  - used in $http get
- scope.$digest()
- scope.$watch()
  - too many watchers
- ng-cloak

Pitfalls:


