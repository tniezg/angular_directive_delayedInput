# DelayedInput

AngularJS directive that extends ngModel to synchronize the view with the view-model but adds a custom delay.

## In a view:
```
<input delayed-input="searchDelayed" propagation-delay="300" ng-model="search" type="text"/>
```