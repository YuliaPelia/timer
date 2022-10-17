# timer

id - timer
deadline - final time
1. I am creating a function that will allocate the difference between the deadline (end date) and the present time, 
the function will accept the end time
Data.parse - turns a string into a number, in it we will get the number of milliseconds that will be in our final time, 
now this difference in milliseconds must be converted into the number of days, hours, minutes, seconds.
2. In order to rotate these variables to the outside, use return
3. I create a function that will set this timer on the page
In order to set up our timer, we will need:
1) selector - the main element on the page
2) deadline - by which we will transfer it
4. I create a function that will update the timer every second
1) calculation of the time left right at this second
2) place the estimated values ​​on the page
* the getZero function is needed so that when the number is less than 10, 0 is substituted for them
3) run the updateClock function every second (I write TimeInterval above)
4) in the future, when the time runs out, this timer must stop
5. I make the first two values, when they are single-digit (that is, they have one digit), then 0 is substituted for them
* on average: 08 days, 09 hours
6. So that the date does NOT blink on the page (first the values ​​from the layout are substituted, and then from js), in order to do this, 
I need to call the updateClock function at the beginning (before the updateClock function itself)
