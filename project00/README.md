# Project 00: Guess the Number Game

## TOC  
- [Introduction](#introduction)
- [Use Case](#use-case)
- [Data](#data)
- [Approach](#approach)
- [Outcomes](#outcomes)
- [Learnings](#learnings)

### Introduction    
Guess the randomly chosen number. Hopefully in the least possible steps.

### Use Case    
**Conditions**  
- A number between 0 and 100 is randomly chosen.
- We need to guess the number in the least possible number of steps
- We need to use the 'greater than' or 'lesser than' criteria to nail down the guessed number

**Metrics**     
Need to run this 10,000 times and take the average

**Why we are doing this**    
Learning Python, learning anaconda, learning VS Code


### Approach  
The input is the integer number between 1 and 100 (including). To guess the number we start with 1 and go thru the infinite cycle until the number is guessed correctly. Every step of the cycle we split the space of numbers in half and then cut out the half that does not contain the right number.

**Gotchas**     
To avoid the rounding errors we round up the numbers when cutting off the top of the spectrum, and round down otherwise.

### Outcomes
On average the number is guessed now in 5 steps, which is pretty neat!


### Learnings
Learned how to debug python and use anaconda :-) 



