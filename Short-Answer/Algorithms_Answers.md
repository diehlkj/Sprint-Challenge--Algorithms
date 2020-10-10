#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)
    The number of calculations to be preformed increase by 1 as n does the same

b)O(n^2)
    singly nested loop, each being O(n), O(n(On)) == O(n^2)

c)0(n log n)

## Exercise II

O(n)

start is 0, end is n
target is not breaking an egg

middle is int((start + end) / 2)

while start <= end:
    if egg breaks at middle:
        end = middle
    else
        start = middle


f = middle

return f