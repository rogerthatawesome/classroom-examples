# Codingbat Solution Tracing
This is a collection of [Codingbat](http://codingbat.com) solutions that may or may not work. 
The idea is to trace the code to discover the errors or to determine if the solution is infact correct.

## Adding a post
Simply edit this document and add your code as shown below with the following rules:
1. Ensure your code is within triple backticks like below. 
2. Add [type annotations](https://docs.python.org/3/library/typing.html) for the function header so we know what type of data the function recieves and returns.
3. Ensure that the name of the function is under an appropriate `###` header.
4. Ensure that the problem's explanation text is above all the "solutions". 
5. Keep the problems in alpha order.

## Example:
### double
Create a function that will double the given integer.
```
double(5) -> 10
double(3) -> 6
double(0) -> 0
```
Solutions:

```python
def double(n: int) -> int:
    return n * 2
```

```python
def double(n: int) -> int:
    return n * 1
```

End example
---
### double_23
Given an int array, return true if the array contains 2 twice, or 3 twice. The array will be length 0, 1, or 2.

```
double_23([2, 2]) → true
double_23([3, 3]) → true
double_23([2, 3]) → false
```
Solutions:

```python
def double_23(list_1: list) -> bool:
    if list_1[0] == 2 and list_1[1] == 2:
        return True
    elif list_1[0] == 3 and list_1[1] == 3:
        return True
    else:
        return False
```


"""
###Array 1 middleWay
def middleWay(a,b):
  midnum = []
  midnum.append(a[1])
  midnum.append(b[1])
  return midnum
"""
"""
###Array 1 make_ends
def make_ends(nums):
  new = []
  last = len(nums)-1
  new.append(nums[0])
  new.append(nums[last])
  return new
"""
"""
###Array 1 has23
def has23(nums):
  if nums[0] == 2 or nums[0] == 3:
    return True
  elif nums[1] == 2 or nums[1] == 3:
    return True
  else:
    return False
"""
"""
###Array 2 withoutTen
def withoutTen(nums)
  new_list = []
  for n in nums:
    if n == 10:
      del nums[n]
      new_list.append[0]
  return nums
"""


