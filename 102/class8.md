## Operators and Loops

# Expressions & Operators - Expressions - valid unit of code that resolves to a value.
    * 2 Types: Those that have side effects (assigning value) & those purely evaluate
        ex: 1st type: x = 7, uses = operator to assign the value 7 + variable x
        ex: 3 + 4, uses + operator to add 3 & 4 together and produces value 7

* Reference - Complete and detailed list of ops and expression 
* JavaScript has binary & unary ops & 1 special tenary the conditional ops.
    - Binary ops- requires two operands, one before the ops & one after the ops -> operand1 operator, operand 2 
        - Inflix operator - oops placed between two operands
            **All binary ops in JavaScript are inflix

# Compound Assignment Operators
Bitwise AND Assignment          x& = f(x)
Bitwise XOR Assignment          x^ = f()
Bitwise OR Assignment           x| = ()
Bitwise AND Assignment          x && = f()
Logical OR Assignment           x|| = f()
Logical nullis Assignment       x?? = f()

* Destructing assignments - syntax is a JavaScript expression that makes it possible to extract data from arrays or objects using syntax that mirros that construction of arrays and object literals.

# Loops - 2 Types: for loops & while loops
    * While loops -> When we don't know how it needs to run
        ew - while () {} <- loops form -> () has to always be true to run
                while(this is true){execute this code}
                    let x =0 
                    while (x < 5){
                        console.log(x);
                    }