# ENGR 102 Lab Topic 3 (individual)

## Activities
This lab consists of two individual activities, and an optional bonus activity. Please submit the following files to Gradescope. Check out the [Frequently Asked Questions](#frequently-asked-questions) below. **Please include the individual header in your ~.py files.**

1. [Using Input](#using-input)
2. [Calling Functions](#calling-functions)
3. [Challenge Program (Optional)](#challenge-program-optional)

## Using Input
Convert your program from individual Lab: Topic 2 Activity #1 (Using Variables) to a new program that produces identical output. However, your new program should take in input from the user as appropriate, store values in variables, and output in the required format. Please name the program `using_input.py`.

Produce output for the following calculations:
1. Calculate the **Reynolds Number (Re)** for a fluid with a given velocity in m/s, a given characteristic linear dimension in m, and a given viscosity in m^2/s. Display the result with zero (0) decimal places.
2. Calculate the **wavelength** of x-rays scattering from a crystal lattice with a given distance between crystal layers in nm and a given scattering angle in degrees. Assume first order diffraction. Display the result with four (4) decimal places. (See **Bragg’s Law** from before)
3. Use the **Arps equation** to calculate the production rate of a well given a time in days, an initial production rate in barrels/day, an initial decline rate in 1/day, and a hyperbolic constant of 0.8. Display the result with two (2) decimal places.
4. Use the **Tsiolkovsky rocket equation** to calculate the change of velocity of an object with a given initial mass in kg, a given final mass in kg, and a given exhaust velocity in m/s. Display the result with one (1) decimal places.

Each part of your program should perform the following tasks:
- Print what the part of the program does to the screen.
- Prompt the user to enter required data from the keyboard. Include proper units in the prompt as shown in the example output below.
- Get the inputs from the user and store in appropriately named variables.
- Perform the necessary calculations.
- Output the result to the screen with **proper labels and units**.

Example output (using inputs `9`, `0.875`, `0.0015`, `0.025`, and `35`):
```
This program calculates the Reynolds number given velocity, length, and viscosity
Please enter the velocity (m/s): 9
Please enter the length (m): 0.875
Please enter the viscosity (m^2/s): 0.0015
Reynolds number is 5250

This program calculates the wavelength given distance and angle
Please enter the distance (nm): 0.025
Please enter the angle (degrees): 35
Wavelength is 0.0287 nm
```

Please see the tests on Gradescope for exact wording for the remaining parts. As always, please include descriptive comments in your code so that someone may follow your programming logic.

## Calling Functions
description

## Challenge Program (Optional)
description

## Frequently Asked Questions
1. **How do I round my output again?** Use string formatting (not the `round()` function!) to specify how many digits to display. Watch [this video](https://mediasite.tamu.edu/Mediasite/Play/95fc0a90130d47f5802d87e1d3020ecd1d) for examples.

2. **Do I have to use radians in my trig functions every time?** YES! Every. Single. Time. Have python convert for you! Example: `sin(angle * pi / 180)`

3. **I'm still having trouble figuring out why my output is wrong. Help?** Click on the failed test. You should see a caret (`^`) indicating what's different between your output and the solution output. Did you misspell something? Math error? Incorrect formatting? Hopefully that helps you figure it out!

4. **Challenge activity how do I do it without `round()`?** If I gave you the answer it wouldn't be a challenge, would it? :) There's more than one way to solve it. One method: get creative with math operators. Remember some of the new ones we talked about in lecture 1? Another method: we use string formatting to control how many digits to display. But instead of hardcoding a number, can you use a variable to construct the format string?

Have a question you don't see here? Email your instructor!

Based upon Dr. Keyser’s Original<br/>
Revised Summer 2025 SNR
