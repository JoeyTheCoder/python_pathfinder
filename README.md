# python_pathfinder
Python learning project for using the breadth first search algorithm and navigate through a maze with it
This is a command line application in which i take a 2 dimensional array like this one:

maze = [
    ["#", "#", "#", "#", "#", "#", "O", "#", "#"],
    ["#", " ", " ", " ", " ", " ", " ", " ", "#"],
    ["#", " ", "#", "#", "#", "#", "#", " ", "#"],
    ["#", " ", "#", " ", " ", " ", "#", " ", "#"],
    ["#", " ", "#", " ", "#", " ", "#", " ", "#"],
    ["#", " ", "#", " ", "#", " ", "#", " ", "#"],
    ["#", " ", "#", " ", "#", " ", "#", "#", "#"],
    ["#", " ", " ", " ", " ", " ", " ", " ", "#"],
    ["#", "#", "#", "#", "#", "#", "#", "X", "#"]
]

and define the starting and endpoint with "O" and "X". The blockades are defined as "#".

With the breadth first search algorithm i iterate through the array and have a look of the neighbors uf the starting or current position one by one. As soon as the output of one of the neighbours = "X" i must've found the shortest path and display it in the command line as such.
