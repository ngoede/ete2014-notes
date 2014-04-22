Why Angular?
######
Uses D/I so it is more testable
Uses MVC for seperation of concerns
Large community and lots of add in modules

http://codepen.io/krimple/professor/szKbp/

If the attribute starts with ng its an angular attribute
{{ "did you know that 3 + 4 = " + 7 }} <--Template

ng-app creates a scope that is attached to the application -> angular.moudle('myApp', []) // name, dependencies

ng-controller -> .controller('name', fuction($scope) {
//Stuff controller does
});

$scope will be injected by angular.  It is what you setup as your model I think.

<button ng-click='yell()'>Yell!!!</button> <--Hooks up yell function on scope to button
<input ng-model='name' />
<p>Hello, {{ name }}</p>  <!--Will take text from input and place it dynamicly into template-->

$scope is a scoped magic global in the sky
$scope can do event bussing also
ng-repeat <--For Each $index for index

Angular.js batarang <--Debuging and perf tool for seeing what is going on with angular pages/apps

ng-if only addes things to DOM if true instead of just making invisible

.config runs at setup of page
