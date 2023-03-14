[Actual Github repo for this work ](https://github.com/Joy879/operators_control_flow)
## Symbols for Javascript operators

* Arithmetic Operators

            +	            Addition
            -	            Subtraction
            *	            Multiplication
            *             Exponentiation 
            /	            Division
            %	            Modulus 
            ++	    Increment
            --	    Decrement

* Assignment Operators

            =	
            +=	
            -=	
            *=	
            /=	
            %=	
            **=	

* Comparison Operators

            ==	            equal to
            ===	            equal value and equal type
            !=	            not equal
            !==	            not equal value or not equal type
            >	                    greater than
            <	                    less than
            >=	            greater than or equal to
            <=	            less than or equal to
            ?	                    ternary operator

* Logical Operators

            &&	            logical and
            ||	            logical or
            !	                    logical not

* Bitwise Operators

            &	            AND	
            |	            OR	
            ~	            NOT	
            ^	            XOR	
            <<	  left shift	
            >>	  right shift	
            >>>	  unsigned right shift	

## For each JavaScript Operator, write 2 examples.
* Arithmetic operations
```js
let a = 3;
let x = (100 + 50) * a;

//Result is x = 450

let a = 10;
let x = (100 - 50) / a;

//Result is x = 5
```
* Assignment operators
```js
let x = 10;
    x += 5;

Result is x = 15

 let x = 10;
     x *= 5;

Result is x=50
```
* Comparison operators
```js
let x = 5;
x == 10

Result is false

x != 8

Result is true
```
* Logical operators

```js
let x = 6; 
let y = 3;

(x == 5 || y == 5)

Result is false

(x == 5 && y == 5)

Result is false
```
* Bitwise operators

```js
5 $ 1

Result is 1

5 | 1

Result is 5
```
## Result of the following code:
```js
 for( let i=1; i< 20; i+=7) {
    console.log(i);
}
```
                1
                8
                15
