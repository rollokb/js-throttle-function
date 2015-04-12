# js-throttle-function

Function which resticts the number of times a callback can be called a second.

## Usage

  var throttle = require("throttle-function");
  
  throttle(function () {
    // Regardless of how often throttle is called
    // this function will only be called a maximum 
    // of one every 500 milliseconds
  }, 500)
