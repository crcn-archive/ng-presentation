

## topic: Understanding AngularJS internals

http://slides.com/craigjefferdscondon/ng-internals

- whoami
  - when did I start?
  - why do I like programming?
  - what have I done?


- Agenda
  - internals - why understand your tools?
    - avoid common pitfalls
    - demystification
    - how to manipulate

- why ng?
  - testability


- digest cycle

- digest cycle functions
  - $scope.$apply()
    - what does it do?
    - how does it work? (dirty type checking)
    - when to use it?
      - directives
      - syncing changes in the UI
  - $scope.$watch()
  - $scope.$digest()
  - other functions
    - $scope.$http
    - $scope.$timeout

## DO 
  - exampes - analogies

## Talk about
  - $scope.$apply()

## Examples

- Hello World: http://jsfiddle.net/uoo7yzvz/
- manually updating scope without apply: http://jsfiddle.net/uoo7yzvz/5/
- manually updating scope with apply: http://jsfiddle.net/uoo7yzvz/6/
- click handler for incrementing count: http://jsfiddle.net/uoo7yzvz/7/
- jquery click handler http://jsfiddle.net/b06tk4a6/


## Bibliography

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
