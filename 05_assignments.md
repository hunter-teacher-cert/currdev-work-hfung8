Develop two assignments that are different types for your unit plan.<br>
Describe the assignment, including student facing instructions in a markdown file. Save this file in your own personal work repository.<br>
This is individual work, that can be incorperated into your unit plan later.<br>

The performance task that students will create for AP CS Principles is a snake game by the end of the unit and both of these assignments will help with the learning process of making the snake game. 

### Assignment Number One 
<hr>

**Description**
Students will be able to use the setInterval method to make a piece of text appear after a set amount of time. 

**Student facing instructions**
Students need to understand callback functions and how they are called every few millisecond within the setInterval method. 

```
var block = document.getElementById("test");
block.style.visibility = "hidden";

function disappear(){
  setInterval(function(){
    block.style.visibility = "visible";
  }, 1000);
}

disappear();
```

Some code will be scaffolded to the students and they will need to fill out the rest of it in order to solve the problem. Students will be told that they need to use a function and make a call to a function. They will also be told that they need to make a call to a css method using ".style" in order for the problem to work. There is another method that they could use which involves using display: block and display: none, for which the students will be informed about. 

### Assignment Number Two 
<hr>

**Description**
Students will be able to define a callback function. 

**Student facing instructions**
Since callbacks will be used in the functions for creating a snake game, students will have to be able to define a callback function. Students will be asked:

```
//What are Callbacks? 

document.addEventListener("click", getTime());


function getTime(){

    console.log("time");
}

setTimeout(function() {console.log("Hello")}, 1000);

//Where are they useful? 

asynchronous nature of javascript for calling of a function. Javascript is run line by line.

//What is the definition? 

functions called at a later time 

//What is callback hell? 

when you are chaining functions with callback functions to get to an endpoint 
so we created promises 
```

This will be a less code heavy assignment. Students will be asked questions for which they will be required to write a response to. "What are callbacks?", "Why are they useful", "Give an example of a callback" and a final question could be, "What is callback hell?"

