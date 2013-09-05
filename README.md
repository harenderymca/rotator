rotator
=======

jquery plugin to create a rotating loader, for percentage.

Pass in the starting number(< 50) and ending number( <= 100) and watch as it rotates to complete the the cycle.


To watch it in action, clone this repo and run rotator.html


Usage
---------
- Depends on jQuery

create a div to hold the rotator
```html
<div id='rotator'></div>
```
```javascript
$('#rotator').rotator({
  starting: 0,
  ending: 100,
  lineWidth: 10
  // For all available options, check rotator.js
})
```


