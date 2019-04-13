# Homework - JS Practice and Project HTML/CSS Draft

![](https://media.giphy.com/media/yYSSBtDgbbRzq/giphy.gif)

This gif is completely irrelevant to the hw tonight, but might be relatable for some other things this week!


anyways!

This homework has two parts!  The first part is practicing the javascript skills we learned today.  The second part is to work on projects!


# Part 1 - Javascript Practice

For this assignment, complete the problems below and add your solutions to this README.md.  

## 1 - Activity Assignment
*Without running the following code*, try to determine:

```js
var a = 1;
var b = 'bongos';
var c = true;

a = b;
b = c;
c = a;
```

### Your solution here:
1.  What is `a`?
```
a is (bongos)
```
2.  What is `b`?
```
b is (true)
```
3.  What is `c`?
```
c is (1)
```

Now run it and don't update your answers above.  Any surprises?  Don't worry about submitting wrong answers, it's all good :3

For the next problems, feel free to test out solutions in repl.it before putting your solutions in this readme!

## 2 - Activity Concatenation
Use the `+` operator to concatenate these strings together within a `console.log()`: "Please", "squeeze", "the", "cheese". __Make sure there are spaces in-between each word__.

```js
var firstWord = "Please";
var secondWord = "squeeze";
var thirdWord = "the";
var fourthWord = "cheese";
```
Result should be:
```js
"Please squeeze the cheese"
```

```js
console.log("please" + " squeeze" + " the" + " cheese.");
```

## 3 - Variable Assignments

Output a console log `The sum of 5 and 10 is 15` where the values for 5 and 10 are saved to variables, and where 15 comes from those variables being summed.

```js
var num1 = 5;
var num2 = 10;
```

Let's do this in parts:
1. How can we make `num3` equal to the sum of `num1` and `num2`?
```js
// var num3 = num1 + num2;
```
2. Use variables `num1`, `num2` and `num3` to fill in the `console.log()` to complete the sentence: 

>The sum of 5 and 10 is 15

```js
var num1 = 5;
var num2 = 10;
var num3 = num1 + num2

console.log("The" + " sum" + " of " + num1 + " and " + num2 + " is " + num3);

```

## 4 - Comparisons
By just looking at the following expressions, determine in your mind whether or not each will evaluate to true or false
```
a) 999 > 999
b) 999 === 999 
c) 999 !== 999
d) -5 >= -4
e) 100 <= -100
f) 20 + 5 < 5 
g) 81 / 9 === 9
h) 9 !== 8 + 1
```
### Your solution here:
Write `true` or `false` based on the list above
```
a) false
b) true 
c) false
d) false
e) false
f) false
g) true
h) false
```

## 5 - Functions:

* Write a function called `timeTwo` that takes in a parameter `num` and `return`'s that number multiplied by 2.

```js
function timeTwo(num){
return num * 2;
}
console.log (timeTwo(3));
```
 
## 6 - Loops:

*  Write a `for` loop so that the function outputs all values between 0 and any number passed into the `maxNum` parameter.
   
```js
// var maxNum =10
   function number(maxNum) {
   for (var i = 0; i <= maxNum; i++)
   }
   console.log(i);//
```

## 7 - Arrays:

*  Create a variable `favoriteMovies` that is equal to an array of your 5 favorite movies:

```js
// var favoriteMovies = ["7 pounds" , "The Call" , "Leon: The Professional" , "The Pursuit of Happiness" , "Taken"]
```

*  How would you replace the 3rd favorite movie with the value `Toy Story 3`?

```js
// favoriteMovies[2] = "Toy Story 3";
console.log(favoriteMovies);
```

*   How would you remove the last movie from that array?
```js
// favoriteMovies.pop();
console.log(favoriteMovies);
```

*   **Write a function** called `addMovie` that takes a parameter of `newMovie` that adds that movie to the end of the array.  (i.e. addMovie('Titanic')) adds Titanic to the end of the array.

```js
// function addMovie(newMovie){
return favoriteMovies.push(newMovie);
}
addMovie('Titanic');
console.log(favoriteMovies);
```//


# Part 2: Project Progress: HTML and CSS!

Let's keep trucking along with our projects!  Our next project milestone is to have the a draft of the HTML/CSS.  Your draft should be focused on the structure of your application, like placement of the headers, the main content, the nav, footer, etc.  You should have a little bit of the text/content ready to go, but making sure you have a good layout is far more important at this point.

We are going to start looking at your project proposals tonight and will have all proposals addressed by tomorrow (Friday, April 12th) at noon!

To start your projects:
* Make a new folder on your computer called "Final Project"
* In that folder create files called `index.html`, `style.css` and `main.js`
* Do all if your work in the new `index.html` and `style.css` files.

# Due Dates and Times:

Your javascript exercises are due at midnight Saturday night!

Your project progress is due Sunday morning in class!  We'll do submissions together that morning.
