<h1>Algorithms (JavaScript)</h1>

**Binary search**

For binary search, the array must be sorted!
 - The function arguments are the array, and the value what's index we are looking for
 - create variable for the first, last and the middle index of the array
 - The actual search part: 
    - The while loop don't stop until the middleIndex not equals to the value AND firstIndex is smaller than the lastIndex
    - If the value is bigger than the middleIndex, the lastIndex will be middleIndex - 1
    - But if the value is smaller than the middleIndex, the firstIndex will be middleIndex + 1
    - The middleIndex is always set to be to the 'middle' of the array after every check
    - If the middleIndex not equals to the value, the function return -1, else it returns the middleIndex (The actual index of the given value
