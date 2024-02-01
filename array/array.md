# Arrays

An array is a sequence (list) of values stored in memory, back-to-back-to-back. (Contiguous)

Contiguous area of memory, can be in the stack or heap. Consits of equal-size elements indexed by contiguous integers.

Constant-time access
Read
Write

array_addr + elem_size * (i - first_index) 

Times for Common Operations
     
          |Add  Remove
------------------
Beginning |O(n) O(n)
      End |O(1) O(1)
   Middle |O(n) O(n)

Good for adding or removing elements at the end, expensive if you want to add or remove  in the middle/beginning.
Huge advantage for arrays is we have constant-time access to read or write.

Constant-time access to any element
Constant time to add/remove at the end
Linear  time to add/remove at an arbitrary location.

Test
12
3

1
