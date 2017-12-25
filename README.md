# rock-paper-scissors
https://soniabradley.github.io/rock-paper-scissors/

1.  User makes a choice
2.  Computer makes a choice
3.  Capture all choices
4.  Compare choices, determine a win, loss or tie
5.  Display the result to the user

Concepts and highlights

<!-- <script type="text/javascript">
    document.onkeyup = function() {
        alert("working");
    } -->

The onkeyup event occurs when the user releases a key (on the keyboard)
A function is triggered when the user releases a key in the input field. The function transforms the character to upper case

Math.random will produce a random decimal number between 0 and 1
Math.random will then be multiplied by the index in the array which always one more than the numbered indexes in the array so the array will be 1,2,3, instead of 0,1,2.

Math.floor runs down the number, instead of rounding up.

The fromCharCode() method converts Unicode values into characters.
Note: This is a static method of the String object, and the syntax is always String.fromCharCode().

toLowerCase() handles user error to make sure that all letters are turned into lower case

id="game" div is created after code logic is completed.