# 1 - HTML

## [ ] Create the needed files

- [ ] Create a file "index.html"
- [ ] Create a file "script.js"

## [ ] Create the HTML structure

- [ ] Create a text box, give it an id of "name" and a value of "Batata"
- [ ] Create a button, give it an id of "submit"
- [ ] Add a div, give it an id of "result"
- [ ] Add a script tag, link it to the javascript file "script.js"

# 2 - Javascript

## [ ] First Javascript steps

- [ ] In javascript, target the "result" div
- [ ] Make it so the div "result" displays "Hello"

## [ ] Writing a function

- [ ] Make a function called "sayHello"
- [ ] Make it so the function, when run, make the div "result" display "CHANGED"
- [ ] Run the function, and verify that when the page loads, the div "result" says "CHANGED"
- [ ] Once you've verified the function works, remove the line that runs it.

## [ ] Making the button work

 - [ ] In Javascript, target the "submit" button
 - [ ] In Javascript, make it so when you click the "submit" button, the "sayHello" function runs. You will need to use `addEventListener`
 
## [ ] Capturing User Input

- [ ] In Javascript, target the "name" text box
- [ ] In Javascript, make it so you `console.log` the text box's `value`. The Javascript console should show you the text box's value, that is, "Batata"

## [ ] Tying it all together

- [ ] In Javascript, make it so when the button "submit" is clicked, you capture the user's input from "name" and insert it in the "result" div. That means that, initially, the "result" div should display "Batata". If I change the text to "World" and press the button, the "result" div should display "World".
- [ ] In Javascript, make it so the "result" div always displays "Hello NAME", where `NAME` is the value of the text box. That means that initially, the "result" div should show "Hello Batata". If I change the text to "World" and press the button, the "result" div should display "Hello World"

## [ ] Add a password field

- [ ] In HTML, add a password field, give it an id of "pass"
- [ ] In Javascript, make it so when the button is clicked, the "result" div shows "Hello NAME PASSWORD", where `NAME` is the value of the "name" input, and `PASSWORD` the value of the "pass" input.
- Congrats!

# Optionals

## Level 1 - Handling empty state

- [ ] In Javascript, make it so when the button is clicked with no name, the message shows ":(" instead of "Hello!"

## Level 2 - Showing an error

- [ ] In HTML, add a div with id "messages"
- [ ] In Javascript, make a function that displays the text "wrong password" inside the div "messages"
- [ ] In Javascript, make it so when the button is clicked, *if* the username is not `Batata`, show the error
- [ ] In Javascript, make it so "name"'s value has to be "Batata", and "pass"'s value has to be `is good`. If any of those is wrong, display the error

## Level 3 - Multiple users

- [ ] Make it so 3 different users can be accepted. You already have one, `Batata` with pass `is good`. Add two others.
- [ ] Add yet 3 others
- [ ] Add 20 more

## Level 4 - Make it look good

- [ ] Make it so it looks good
- [ ] Make it so the errors look different from non-errors
- [ ] Add an animation when the message shows up
