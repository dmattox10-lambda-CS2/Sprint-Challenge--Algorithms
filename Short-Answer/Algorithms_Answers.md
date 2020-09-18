#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
O(n), it will run n times.

b)
O(n log n)

c)
O(n), when n depletes the recursion stops.

## Exercise II
This one screams binary search algorithm which is O(log n) in runtime complexity:
Out of n floors, find the middle floor m
    Drop the egg from m.
    If BROKEN
        top floor in our range is now = m - 1
        start at the top of this code recursively providing m - 1 as our new n
    if !BROKEN
        This MAY be the floor we want, recursion with m + 1 would exclude this floor, so, if it breaks on m + 1 we never find the answer. 
        We want a custom Binary search here, that starts over in range m through n inclusive. This problem literally won't work in code, but with humans executing the task, this is the way to do it.


