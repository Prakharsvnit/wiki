# Challenge Make Unique Objects by Passing Parameters to our Constructor

When you have a constructor but don't want to keep creating the same object, all you have to do is add parameters to the constructor the following way:

```javascript
var Car = function(wheels, seats, engines) {

  this.wheels = wheels;

  this.seats = seats;

  this.engines = engines;

};
```

##  

Now you can pass in arguments when you call the constructor. `var myCar = new Car(6, 3, 1);`

This will result in:

```javascript
{

  wheels: 6,

  seats: 3,

  engines: 1

}
```
