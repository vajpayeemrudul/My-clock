# My-clock
My-clock is a web version of an analog clock.

# Description
The project uses html,css and javascript. The major part is to use css to style the clock appearance.The clock niddle is simply made up to three seperate divs by giving required height, width and border radius. 
These niddles rotate with the help of the css properties of transform origin and rotate. You can refer these [here](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-origin).
Rotation degree is generated with the help of javascript. It uses Date object where methods getHours(),getMinutes(),getSeconds() returns the hours,minutes,seconds according to local time.
These values help us to calculate the amount of rotation we need to provide to our niddles.

# Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
