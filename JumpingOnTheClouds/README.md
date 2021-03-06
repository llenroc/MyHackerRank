Jumping on the Clouds

https://www.hackerrank.com/challenges/jumping-on-the-clouds


Emma is playing a new mobile game involving n clouds numbered from 0 to n-1. A player initially 
starts out on cloud c(0), and they must jump to cloud c(n-1). In each step, she can jump from any cloud i to cloud i+1 or cloud i+2.

There are two types of clouds, ordinary clouds and thunderclouds. The game ends 
if Emma jumps onto a thundercloud, but if she reaches the last cloud (i.e., c(n-1)), she wins the game!

https://s3.amazonaws.com/hr-challenge-images/20832/1461134431-8156ea51b7-jump1.png

Can you find the minimum number of jumps Emma must make to win the game? 
It is guaranteed that clouds c(0) and c(n-1) are ordinary-clouds and it is always possible to win the game.


Input Format

The first line contains an integer, n (the total number of clouds). 
The second line contains n space-separated binary integers describing clouds c(0), c(1),...,c(n-1).

If c(i)=0, the i^th cloud is an ordinary cloud.
If c(i)=1, the i^th cloud is a thundercloud.

Constraints
2<=n<=100
c(i) E {0,1}
c(0)=c(n-1)=0

Output Format

Print the minimum number of jumps needed to win the game.

Sample Input 0

7
0 0 1 0 0 1 0

Sample Output 0

4
Sample Input 1

6
0 0 0 0 1 0

Sample Output 1

3

Explanation

Sample Case 0: 
Because c(2) and c(5) in our input are both 1, Emma must avoid c(2) and c(5). 
Bearing this in mind, she can win the game with a minimum of 4 jumps:

https://s3.amazonaws.com/hr-challenge-images/20832/1461134731-c258160d15-jump2.png

Sample Case 1: 
The only thundercloud to avoid is c(4). Emma can win the game in 3 jumps:

https://s3.amazonaws.com/hr-challenge-images/20832/1461136358-764298d363-jump5.png
