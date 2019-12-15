# autoclick
tinder and bumble auto click 

open console put thease code.


var myVar = setInterval(myTimer, 3000);

function myTimer() {
var o=document.querySelector('[aria-label=Like]');
o.click();
}



## auto click with randon time 

`
function myFuck() {
var o=document.querySelector('[aria-label=Like]');
o.click();
  var min = 5,
    max = 10;

  var rand = Math.floor(Math.random() * (max - min + 1) + min); 
  setTimeout(myFuck, rand * 1000);
}

myFuck();
`
