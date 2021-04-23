# Credit-card-checker
A js script with a few functions 1: uses Luhn's algorithm to find invalid numbers 2: returns array of invalid card numbers 3: Returns the type of cards

Credit card numbers are passed as arrays, e.g. const valid1 = [4, 5, 3, 9, 6, 7, 7, 9, 0, 8, 0, 1, 6, 8, 0, 8]; with the batch variable storing the list of arrays.

validateCred() uses Luhn's algorithm to determine if the credit card number is valid or not returning a true or false value.
findInvalidCards() pushes invalid numbers into invalidArrays array which is then returned.
storedInvalidNumbers() makes a check to see which card type the arrays from findInvalidCards() are and returns this as single values in an array.
