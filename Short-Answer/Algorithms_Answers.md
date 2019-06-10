Add your answers to the Algorithms exercises here.


Excercise 1:

1- Since we have n * n * n inside the while loop, this would be O(n^3)

2- For this one I feel like it should be O(n^4) because of the 4 nested for loops

3- This would be O(n) because for each input of "bunnies" (n), it would directly relate to the amount of calls to bunnyEars... (recursion) would keep calling until it reached the base case set where bunnies == 0


Excercise 2:

Knowing that a building is obviously sorted already from bottom to top... I would do a binary search and start in the middle... if I drop the egg out of middle floor f and it cracks, then I know I can eliminate all the floors above me. If it didnt crack, eliminate the floors below and repeat this step until you find the floor where it stops cracking. 