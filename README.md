# Ex.No:06 JavaScript Calculator
## Date:22-11-2026
## AIM

To design and develop a simple calculator using HTML, CSS, and JavaScript to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

## ALGORITHM

1. Create an HTML page to design the calculator interface.
2. Create a display field to show the numbers and calculation results.
3. Create buttons for digits from 0 to 9 and arithmetic operators.
4. Use CSS to arrange and style the calculator buttons and display.
5. Write JavaScript functions to handle button clicks.
6. Store the entered numbers and operators in the calculator display.
7. Use JavaScript to evaluate the arithmetic expression.
8. Display the calculated result on the calculator screen.
9. Provide a clear button to reset the calculator.
10. Test the calculator with different arithmetic operations.

## PROGRAM
<!DOCTYPE html>
<html>

<head>
    <title>My Calculator</title>

    <style>
        
.calc {
    height: 400px;
    border: 4px solid darkblue;
    background-color: blanchedalmond;
    width: 300px;
    border-radius: 20px;
    text-align: center;
    margin: 100px auto;
    padding: 10px;
    box-shadow: 0px 5px 20px gray;
}

.calculator {
    width: 90%;
    height: 40px;
    font-size: 25px;
    margin-bottom: 15px;
    text-align: right;
}

.row {
    display: flex;
    justify-content: center;
}

input[type="button"] {
    width: 60px;
    height: 50px;
    margin: 5px;
    font-size: 20px;
    cursor: pointer;
}

input[value="C"] {
    background-color: red;
    color: white;
}

input[value="="] {
    background-color: green;
    color: white;
}

h2 {
    text-transform: uppercase;
}

    </style>
</head>

<body>

    <div class="calc">
        <h2>Calculator</h2>

        <input type="text" id="cal" class="calculator">
        <div class = "row">
            <input type = "button" value = "1" onclick="cal.value += '1'">
            <input type = "button" value = "2" onclick="cal.value += '2'">
            <input type = "button" value = "3" onclick="cal.value += '3'">
            <input type = "button" value = "+" onclick="cal.value += '+'">
        </div>
        <div class = "row">
            <input type = "button" value = "4" onclick="cal.value += '4'">
            <input type = "button" value = "5" onclick="cal.value += '5'">
            <input type = "button" value = "6" onclick="cal.value += '6'">
            <input type = "button" value = "-" onclick="cal.value += '-'">
        </div>
        <div class = "row">
            <input type = "button" value = "7" onclick="cal.value += '7'">
            <input type = "button" value = "8" onclick="cal.value += '8'">
            <input type = "button" value = "9" onclick="cal.value += '9'">
            <input type = "button" value = "*" onclick="cal.value += '*'">
        </div>
        <div class = "row">
            <input type = "button" value = "0" onclick="cal.value += '0'">
            <input type="button" value="C" onclick="cal.value = ''">
            <input type="button" value="=" onclick="cal.value = eval(cal.value)">
            <input type = "button" value = "/" onclick="cal.value += '/'">
        </div>
    </div>

</body>
</html>



## OUTPUT <img width="1842" height="1012" alt="CALCULATOR" src="https://github.com/user-attachments/assets/2e68625f-18a7-458a-97e3-a47c87b35280" />



## RESULT

Thus, a JavaScript-based calculator was successfully designed and developed to perform basic arithmetic operations using HTML, CSS, and JavaScript.

## RESULT

Thus, a JavaScript-based calculator was successfully designed and developed to perform basic arithmetic operations using HTML, CSS, and JavaScript.
