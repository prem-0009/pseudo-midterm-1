# pseudo-midterm-1

### Capitalizing the beginning letter in each sentence.
1. Make a new empty string.
2. Change the sentences to lower case.
3. Loop through each index of the sentences.
4. Check if the current index is 0, or '2 index' before current is '.'
5. If step 4 is yes, then add the empty string and the char at current index.(uppercase it).
6. Otherwise
7. Add the empty string and the char at current index.
8. Display the result.

###  Checking if a password is valid.
1. Check if the password has empty space or is less than 12 characters.
2. If yes, give output false.
3. Otherwise.
4. Give output true.

### Squaring a numbers of number in an array and halving it.
1. Make a new empty array.
2. Loop through each index of given array.
3. Square the number at current index and half it. 
4. Move the calculated number to the empty array.
5. Display the now filled -pre empty array.

### Delete the middle letter/s from a given string.
1. Make a new empty string.
2. Check if given string length when divided by 2 gives some remainder.
   >1. Get the middle index number of the string.
   >2. Get the first-half string by slicing the given string, from 0 to the middle index.
   >3. Get the last-half string by slicing the given string, from one up of middle index to the last index.
   >4. Change the empty string to addition of first-half and last-half string.
   >5. Otherwise
   >6. Get the first-half string by slicing the given string, from 0 to one less of middle index.
   >7. Get the last-half string by slicing the given string, from one up of middle index to the last index.
   >8. Change the empty string to addition of first-half and last-half string.
3. Display the now filled, pre empty array.

### Display the last index of empty space.
1. Display the last index of empty space.

### Replace space with hyphen between the last and middle name or last and first name.
1. Make a new empty string.
2. Loop through each index of given string.
   >1. If the current index is equal to last index of empty space.
   >    >1. If yes add the empty string and hyphen '-'.
   >2. Otherwise
   >    >1. Add the empty string and character at current index.
3. When the loop is over ,return the result.
