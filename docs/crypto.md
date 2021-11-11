# Instructions  

## aim
* to create produce an encrypted message from an original plain text message
* use `(int)` and `(char)` to convert between character and integer values

> remember that each character in a `String` has a position number starting at `0` and finishing at `1` less than the length of the string

### key idea `charAt()` function
* `"Computer".charAt(2)` would produce the charatcter at position 2
* the `charAt()` function returns a `char` value, not a `String`
* `'A'` is a character, `"A"` is a `String`

### key idea `(char)` & `(int)` casting
* Each character value has a matching integer value in the ASCII table, `'A'` is `65`
* this means it is possible to convert from one datatype to the other, this is called _casting_ in Java.
* it is also possibe to do some arithmetic operations on characters!

## Steps `PRIMM`

### `PREDICT-RUN`

* Read the `PREDICT-RUN` code
* Share with a partner what you think will be displayed by the code, try to give reasons.

### `INVESTIGATE` and `MODIFY`

* try different letters from the alphabet string: start, middle and end. How will you do this?
* try different shift values, 0, 1-25, 26, over 26, negative values? How will you do this?


### `MAKE`

* uncomment the loop code in the `MAKE` section and run the program to see what it does
* create code to encrypt the entire message, use code in the `PRIM` section above

> **challenge** using an `IF` construct

> * Any characters in the message which are not in the alphabet should not be encrypted.

> * The code should also be able to handle lower case letters.

  
  
