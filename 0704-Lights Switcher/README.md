# 704. Lights Switcher

Difficulty: Medium

http://www.lintcode.com/en/problem/lights-switcher/

There is a room with n lights which are turned on initially and 4 buttons on the wall. After performing exactly m unknown operations towards buttons, you need to return how many different kinds of status of the n lights could be.

Suppose n lights are labeled as number [1, 2, 3 ..., n], function of these 4 buttons are given below:

1. You can flip all the lights.
2. You can flip lights with even numbers.
3. You can flip lights with odd numbers.
4. You can flip lights with (3k + 1) numbers, k = 0, 1, 2, ...

**Example**  
Given n = 1, m = 1.  
return 2 // Status can be: [on], [off]

Given n = 2, m = 1.  
return 3 // Status can be: [on, off], [off, on], [off, off]