The two-pointer technique uses two variables/pointers to 
traverse an array or string, usually from different positions.

BASIC STRUCTURE -
__________________________________________
left = 0.                                
right = len(arr) - 1.                    

while left < right:
    # process arr[left] and arr[right]

    if condition:
        left += 1
    else:
        right -= 1
___________________________________________


Problems can be solved using Two pointer 
TWO POINTERS
      │
      ├── Opposite direction
      │      ├── Palindrome
      │      ├── Pair sum
      │      ├── Reverse
      │      └── Container
      │
      └── Same direction
             ├── Remove duplicates
             ├── Move zeroes
             └── Slow/Fast processing
