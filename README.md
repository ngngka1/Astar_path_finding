# Astar_path_finding
This program aims to find the shortest path to the goal with provided map and start position. To use it, run:<br>
Astar_search(map, start position)<br>
The function returns a stack by default which is the path to the goal.<br>
For more details, please refer to the documentation of the function.

Note:
- There is a bug at line 154 regarding the return value when the target position is not reachable (the program will return None instead of an empty list), I am just too lazy to make another commit again as the bug is minor, nonetheless i'll fix that when I start working on the C++ version (just a plan tho not sure if i will do that anytime soon)
- There is also type hinting that is only available in python 3.10 or above, will probably make some changes to make it more compatible 
