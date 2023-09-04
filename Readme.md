# index.html 
in this file we have a div which is conainer and another is for nubers of stop watch 
then we have a div which is for buttons 
we have three buttons and each of them calles diffrent fuctions of javascript

# index.js 
in this file we get the element which is div 
after that we we are delaring the 4 variables
then we have a function called startTimer which iis for starting the timer with checking the conditions and calling the function timercycle
same thing we did for stop the timer we have checked the condition that is if stoptime is false then make it true 
then we have a function timercycle which cheecks the condition if stop time is false then convert to number

then we are setting the second with +1 value which will increase 
then we are checking that seconds is 60 than minutes value will increase and seconds will be 0 again 
same we are checking for hours 
then we are setting the value for second minute  and hours with single value with 0
then we are passing that to inner html which will be disolayed over browser
then we have added setTimeout method for calling the function after 1000 miliseconds 


after that we have a functions called reset which will set the value of innerHTML as empty

