
# Calculator using Logic Gates
![calculator on real life](https://github.com/aliaagheisX/Calculator-using-Logic-Gates/blob/d4fb983bd0364fd0b8719d72d9e3ce44a6aa6cea/Logic%20Calculator.jpeg)
4 bit Calculator using Logic Gates

  1-reminder
  
  2-addition/subtraction
  
  3-multiplication
  
##  Reminder

**Extendable** Reminder using :

  1-3 subtractors(3 adder and xor ) 
  
  2-piority encoder and mux -> for choosing the right value
  
  3-nor -> for division of zero error
  
### idea (A%B) 
we subtract the **A** three times and get the value before become negative

##  Addition / Subtraction
**Extendable** Adder / Subtractor using :
  
  1-adder
  
  2-4 muxs -> to choose the complement value or the real value
  
  3-2 And / 2 OR -> for zero error
  
  4-5 Xor / 1 OR -> to complement the numbers => (two inputs - one output)



### idea (+-A +- +-B)

  -if the input sign negative we convert it to it's 2nd complement .
      
  the second input sign xor with the operator(+ or -) give the real sign if it.
    
  -we add them using adder.
  
  -if there's a carry out from adder mean that the output negative and it's need to convert it to it's 2nd complement state.
  
  -if not means that's positive output and it's correct.
  
  
  ##  Multiplication
**Extendable** Multiplication using :
  
  1-3 xor -> 1 for sign and rest for A1, A2
  
  2-6 And -> to get carries

### idea (+-A * +-B)

  -the first output is A0B0
  
  -the second output is A0B1 + B0A1 and carry(C) out
  
  -the third output is A1B1 + C and carry(C) out
  
  -the fourth output is C
  
  
  ## Collection
  we use:
    
    1-4 mux -> for o1,o2,o3,sign 
    
    2-and -> for o4 =>  as it out from multiplication only
    
    3-OR/And for flags and show sign
    
    4-7-segment IC converter
 
 ## Teammates 

I work on this project with   **Ali Farid**,  **Mahmoud Farid** and **Omar Said**
  
