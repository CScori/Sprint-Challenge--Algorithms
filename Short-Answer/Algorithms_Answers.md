#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
o(n)
due to the loop running on a single x*n

b)

o(n^2)
because we have nested for loops both using n*n 

c)
o(n)
due to the function decrementing and will only run as much as initially given
## Exercise II

UNDERSTAND
there is a building
building has floors
floor f or higher eggs break
below f eggs dont break
find a number for f

PLAN
treat eggs as an list
loop thru list on conditionals
ie egg break floor is f or higher
no break floor is below f
return first instance of break (assuming sorted list or stack)

EXECUTE
o(log n)
