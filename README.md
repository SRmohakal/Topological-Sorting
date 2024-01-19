<b>Topological Sorting

Sandro is a well organised person. Every day he makes a list of things which need to be done<br>
and enumerates them from 1 to n. However, some things need to be done before others.<br>
In this task you have to find out whether Sandro can solve all his duties<br>
and if so, print the correct order.<br>

Input<br>

In the first line you are given an integer n and m (1 <= n <= 10000, 1 <= m <= 1000000).<br>
On the next m lines there are two distinct integers x and y, (1 <= x, y <= 10000)<br>
describing that job x needs to be done before job y.<br>

Output<br>

Print "Sandro fails." if Sandro cannot complete all his duties on the list.<br>
If there is a solution print the correct ordering, the jobs to be done separated by a space.<br>
If there are multiple solutions print the one, whose first number is smallest,<br> 
if there are still multiple solutions, print the one whose second number is smallest, and so on.<br>

Example 1<br>
Inputt<br>
8 9<br>
1 4<br>
1 2<br>
4 2<br>
4 3<br>
3 2<br>
5 2<br>
3 5<br>
8 2<br>
8 6<br>
Output<br>
1 4 3 5 7 8 2 6 <br>

Example 2<br>
Input<br>
2 2<br>
1 2<br>
2 1<br>
Output<br>
Sandro fails.<br>
