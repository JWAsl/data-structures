Array's are sequences of values stored in memory back to back (Contiguous). They consist of equal-sized elements (Same memory size) indexed by contiguous integers.

Array's have constant time access to read/write any element in the array due to being able to do arithmetic to find the address of a particular array element:

```
array_address + element_size * (i - first_index)
Note: In some languages the first index in the array is 1, not 0.

```

![ArrayOne](https://github.com/JWAsl/data-structures/blob/master/array/images/ArrayOne.PNG)

To find the address of the element in i = 3 we do:
```
array_address + element size * (3 - 0)
```

![ArrayTwo](https://github.com/JWAsl/data-structures/blob/master/array/images/ArrayTwo.PNG)

To find the address of the element in (2,3) we do:
```
array_address + element size * ((2 - 0) * 6 + (3 - 0))
We multiply by six to skip all the elements in the first 2 rows
```

**Time for common operations**

|  | Insert | Remove |
| ---- | ---- | ---- |
| Beginning | O(n) | O(n) |
| Middle | O(n) | O(n) |
| End | O(1) | O(1) |

**Inserting and removing at the beginning**

![ArrayThree](https://github.com/JWAsl/data-structures/blob/master/array/images/ArrayThree.PNG)

**Inserting and removing in the middle**

![ArrayFour](https://github.com/JWAsl/data-structures/blob/master/array/images/ArrayFour.PNG)

**Inserting and removing at the end**

![ArrayFive](https://github.com/JWAsl/data-structures/blob/master/array/images/ArrayFive.PNG)


