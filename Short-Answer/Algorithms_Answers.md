#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Time complexity will be O(n) because the operations will increase 3 times faster as the input grows. Space complexity I believe will be the same.


b) Time complexity wil be O(n log n)


c) Time complexity I believe will be O(n) because we do only do O(n) operations but it's space complexity will be O(n) because the space will increase as the input increases.

## Exercise II

def exercise(eggs):
  broken_eggs = 0
  dropped_eggs = 0
  for index in range(len(eggs)):
    if(eggs[index] > 'f'):
      <!-- Only drop if floor is higher than f, this will get us to log of n -->
      dropped_eggs += 1
      broken_eggs += 1

<!-- This is log of n because we only do things if we are at a certain floor -->
<!-- Dropped eggs get reduce, broken_eggs stay the same -->