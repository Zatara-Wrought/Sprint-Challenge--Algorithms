Exercise I:

A) Runtime is linear.  O(n)

B Runtime is quadratic.  O(n^4)

C) Runtime is linear.  O(1)

Exercise II:

def egg_drop_test(n, f): Start by setting the drop point at n/2 and dropping. If egg breaks, call the function recursively with n/2 as the drop floor until a floor is discovered where the egg remains intact.

This algorithm would run O(log n)