# COMP-1012-Lab-2

Download Here:[COMP 1012: Lab 2](https://codingherolab.com/product/comp-1012-lab-2/)

For Custom/Original Work email codingprolab@gmail.com/whatsapp +1(541)423-7793

Exercise 1: Getting input
We can request input from the user using the input function.

input is provided a string which it displays to the user as a prompt. The prompt should be something meaningful, instructing the user to provide something to the program.

Try running the code:

whatTheyType = input('I am the great and powerful fortune-teller. What is your name? > ')
print("I think your name is {}".format(whatTheyType))
Modify the above code in Spyder to ask for:

first (given) name,
last (family) name, and
a favourite colour.
Your output should look like:

Your name is Jerry Smith, and your favourite colour is Yellow
Be sure to use meaningful names for your variables!

Exercise 2: Getting numbers
The input function always returns a string, but we want to ask our user to enter numbers as input. To convert strings to numbers, we use the int() or float() functions, which convert strings into int and float types, respectively.

Try:

theInput = input('What is your age? > ')
ageAsInteger = int(theInput)
nextYear = ageAsInteger + 1
print("The great and powerful fortune-teller predicts that you will be {} years old next year!".format(nextYear))
For now, we will assume that the user always enters an actual number when we convert to a numeric type. Later, we’ll investigate how to check that the input the user provides is valid.

Write a new script that asks for four (4) numbers and stores the four (4) numbers in four (4) distinct variables. You will need to call input four (4) times to do this. Once you’ve got all four (4) numbers, compute and print out the sum, and the average of these numbers. Use string formatting to only show four (4) decimal places for the average.

Your output should look like:

Sum: 10
Average: 2.5000
Exercise 3: BMI Calculation
Write a complete script that will prompt the user for:

their weight (in kilograms),
their height (in centimetres)
Then, calculate and report their body-mass index. The BMI formula is:

BMI=wh2BMI=wh2

Where ww is weight in kg, and hh is height in metres.

Convert the height you read in from centimeters to meters, then report the BMI to two decimal places.

Your output should look something like (highlighted text means the user typed this in):

What is your weight in kgs? > 90
What is your height in cm? > 180
Your BMI is 27.78
Exercise 4: Jump height calculator
Given the kinematic equation:

v2f=v2i+2×a×dvf2=vi2+2×a×d

Make a calculator that calculates how high a jump will be, given the velocity at the start of the jump. You’re going to have to rewrite this equation to solve for dd.

Reminder: the acceleration of gravity is 9.8ms29.8ms2.

Write the calculations in two ways: once using the ** operator, and once using math.pow(). Are the outputs any different? Is either of these versions more readable than the other? You will have to import math to be use the pow() function.

Your output should look something like (highlighted text means the user typed this in):

How fast were you when you left the ground, in m/s? > 3
You have jumped 0.4591836734693877m in that jump
Note: Remember that at the end of a jump (the final velocity), your speed is 0.

Bonus Question: Pokémon Damage Calculator
Pokémon involves a lot of fairly complicated math behind the scenes. Below is the formula to calculate base damage, assuming no modifiers. Given the level of the attacking Pokémon and the other relevant stats seen below, calculate the base damage as shown here.

Base Damage=⎢⎢ ⎢ ⎢ ⎢ ⎢ ⎢ ⎢ ⎢⎣⌊⌊2×Level5+2⌋×Base Power×AttackDefense⌋50⎥⎥ ⎥ ⎥ ⎥ ⎥ ⎥ ⎥ ⎥⎦+2Base Damage=⌊⌊⌊2×Level5+2⌋×Base Power×AttackDefense⌋50⌋+2

Reminder: The floor function shown here (⌊x⌋⌊x⌋) rounds down to the nearest integer. Look in the math library for something that can do this.

Your output should look something like (highlighted text means the user typed this in):

What level is the attacking Pokemon? > 50
What is the attacking Pokemon's ATK stat? > 100
What is the defending Pokemon's DEF stat? > 70
What is the base power of the attack? > 90
The base damage of the attack (before modifiers) is 58
Saving your work
Save the files to the H: (Home) drive on your lab computer if you can; otherwise use the desktop or a USB drive. The desktop on a lab computer is stored on the computer itself, not on your network drive, so you should copy your files to a more permanent location before you leave. A good approach is to carry a thumb drive and plug it into the lab computer, using it to store your programs. Remember to take it with you!

Or, students have access to cloud storage (OneDrive), accessible through your @myumanitoba account. Log in at http://365.myumanitoba.ca. Once logged in, click on the App Launcher at the top left hand side and select OneDrive. To save a file, simply drag it to the OneDrive screen.
