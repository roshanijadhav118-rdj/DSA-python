A Variable Size Sliding Window is a technique where the window size is not fixed
Instead, it expands or shrinks based on a condition

==============================================

General Template 
left = 0

for right in range(n):
    # Expand the window
    include arr[right]

    while window is invalid:
        remove arr[left]
        left += 1

    update answer

===============================================

Time Complexity
Time: O(n) because each element enters and leaves the window at most once.
Space: O(k) or O(n), depending on the data structure used (e.g., hash map).

=================================================

Fixed Size
Window length is constant
Move both pointers together
Example: Maximum sum of size k
Simpler implementation

Variable Size
Window length changes dynamically
Left pointer moves only when needed
Example: Smallest subarray with sum ≥ k
Requires maintaining a validity condition
