# Blocksworld-AI
Solving the Classical Blocksworld AI Problem using A* Search

File: blocksworld_project.py

Execution Procedure - To Run file:

Linux: 
'python blocksworld_project.py <number of blocks> <number of stacks>'
This command is to be used when the python file is accessible in the current working directory. Else, the path needs to be provided and executed as below:
‘python <file_location/>blocksworld_project.py <number of blocks> <number of stacks>'

Enthought Canopy/Idle Environments:
‘%run blocksworld_project.py <number of blocks> <number of stacks>
If the python file is not in the current Python Working Directory, then the complete path must be provided and then executed as below:
‘%run  <file_location/>blocksworld_project.py <number of blocks> <number of stacks>’

Example Program Trace 1:
%run "C:/Users/abm11/Personal/Tamu_MS/Courses/Sem_3/AI/Projects/blocksworld_project.py" 5 3

The Initial State is: 
1 | ['C', 'E']
2 | ['D', 'A']
3 | ['B']

Iteration no.=  1       Queue =  0      Depth =  0
Iteration no.=  2       Queue =  5      Depth =  1
Iteration no.=  3       Queue =  8      Depth =  2
Iteration no.=  4       Queue =  9      Depth =  3
Iteration no.=  5       Queue =  12     Depth =  4
Iteration no.=  6       Queue =  15     Depth =  5
Iteration no.=  7       Queue =  18     Depth =  6
Iteration no.=  8       Queue =  19     Depth =  7
Iteration no.=  9       Queue =  22     Depth =  8
Iteration no.=  10      Queue =  25     Depth =  9
Iteration no.=  11      Queue =  26     Depth =  10

Goal State reached: Success !!

The total number of iterations are:11

The frontier size is:26
Total execution time = 0.00800013542175 s.

Goal State reached at a depth of 10

Initial State: 
1 | ['C', 'E']
2 | ['D', 'A']
3 | ['B']

Sequence of moves according to obtained search path is: 

Next Move:
1 | ['C']
2 | ['D', 'A']
3 | ['B', 'E']

Next Move:
1 | []
2 | ['D', 'A']
3 | ['B', 'E', 'C']

Next Move:
1 | ['A']
2 | ['D']
3 | ['B', 'E', 'C']

Next Move:
1 | ['A']
2 | ['D', 'C']
3 | ['B', 'E']

Next Move:
1 | ['A']
2 | ['D', 'C', 'E']
3 | ['B']

Next Move:
1 | ['A', 'B']
2 | ['D', 'C', 'E']
3 | []

Next Move:
1 | ['A', 'B']
2 | ['D', 'C']
3 | ['E']

Next Move:
1 | ['A', 'B', 'C']
2 | ['D']
3 | ['E']

Next Move:
1 | ['A', 'B', 'C', 'D']
2 | []
3 | ['E']

Next Move:
1 | ['A', 'B', 'C', 'D', 'E']
2 | []
3 | []

Example Trace 2:
%run "C:/Users/abm11/Personal/Tamu_MS/Courses/Sem_3/AI/Projects/blocksworld_project.py" 6 3

The Initial State is: 
1 | ['C', 'A']
2 | ['B', 'E']
3 | ['F', 'D']

Iteration no.=  1       Queue =  0      Depth =  0
Iteration no.=  2       Queue =  5      Depth =  1
Iteration no.=  3       Queue =  8      Depth =  1
Iteration no.=  4       Queue =  11     Depth =  1
Iteration no.=  5       Queue =  14     Depth =  1
Iteration no.=  6       Queue =  17     Depth =  2
Iteration no.=  7       Queue =  18     Depth =  3
Iteration no.=  8       Queue =  21     Depth =  4
Iteration no.=  9       Queue =  23     Depth =  5
Iteration no.=  10      Queue =  26     Depth =  6
Iteration no.=  11      Queue =  27     Depth =  7
Iteration no.=  12      Queue =  30     Depth =  8
Iteration no.=  13      Queue =  33     Depth =  9
Iteration no.=  14      Queue =  36     Depth =  10
Iteration no.=  15      Queue =  37     Depth =  11

Goal State reached: Success !!

The total number of iterations are:15

The frontier size is:37
Total execution time = 0.0090000629425 s.

Goal State reached at a depth of 11

Initial State: 
1 | ['C', 'A']
2 | ['B', 'E']
3 | ['F', 'D']

Sequence of moves according to obtained search path is: 

Next Move:
1 | ['C']
2 | ['B', 'E']
3 | ['F', 'D', 'A']

Next Move:
1 | []
2 | ['B', 'E', 'C']
3 | ['F', 'D', 'A']

Next Move:
1 | ['A']
2 | ['B', 'E', 'C']
3 | ['F', 'D']

Next Move:
1 | ['A']
2 | ['B', 'E']
3 | ['F', 'D', 'C']

Next Move:
1 | ['A']
2 | ['B']
3 | ['F', 'D', 'C', 'E']

Next Move:
1 | ['A', 'B']
2 | []
3 | ['F', 'D', 'C', 'E']

Next Move:
1 | ['A', 'B']
2 | ['E']
3 | ['F', 'D', 'C']

Next Move:
1 | ['A', 'B', 'C']
2 | ['E']
3 | ['F', 'D']

Next Move:
1 | ['A', 'B', 'C', 'D']
2 | ['E']
3 | ['F']

Next Move:
1 | ['A', 'B', 'C', 'D', 'E']
2 | []
3 | ['F']

Next Move:
1 | ['A', 'B', 'C', 'D', 'E', 'F']
2 | []
3 | []
