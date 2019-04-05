Exercise I:

A) Runtime is linear because it'll require n steps of adding n^2 to get to n^3.  O(n)

B.) Last nested loop is a constant so runtime is quadratic.  O(n^3)

C) Runtime is linear because it runs the # of times = input .  O(n)

Exercise II:

def egg_drop_test(n, f): Start by setting the drop point at n/2 and dropping. If egg breaks, call the function recursively with n/2 as the drop floor until a floor is discovered where the egg remains intact.

This algorithm would run O(log n)