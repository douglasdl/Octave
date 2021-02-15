# [Octave](https://www.gnu.org/software/octave/index)
Basic Commands for Machine Learning

# Installation (MacOS)  
`sudo xcode-select --install`  
`brew update`  
`brew install octave`  
  
  

## Comments  
`% Comment`  

## Math Operators  
`+`  
`-`  
`*`  
`/`  
`^`  

## Logical Operators  
`==`  
`~=`  
`&&`  
`||`  
`xor(1, 0)`  

## Change Prompt Apearance  
`PS1('>> ')`  

## Variables  
`a = 3`  
`a = 3;`  
`b = 'hi';`  
`c = (3>=1);`  
`a = pi;`  
`a`  
`disp(a);`  
Print a string  
`disp(sprintf('2 decimals: %0.2f', a))`  
Configure the format of numeric variables to be displayed  
`format long`  
`format short`  

## Matrix  
`A = [1 2; 3 4; 5 6]`  
Create a Line Matrix defining the first element, and last element (step will be 1 by default).    
`v = 1:6`  
Create a Line Matrix defining the first element, step, and last element.    
`v = 1:0.1:2`  
Create a Matrix with all elements 1  
`ones(2,3)`
Create a Matrix with all elements 0  
`zeros(4,3)`  
Create a Matrix with all elements with random numbers (between 0 and 1)  
`rand(2,3)`  
Create a Matrix with all elements with random gausian distribution numbers  
`randn(2,3)`  
Show a Histogram Chart  
`hist(v)`  
`hist(v, 50)`  
Create an Identity Matrix   
`eye(4)`  
Help (command)  
`help eye`  
`help help`  


## Vector  
`v = [1; 2; 3]`  

