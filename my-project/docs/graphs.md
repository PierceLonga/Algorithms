# Graphs
A graph can be easily presented using the python dictionary data types. We represent the vertices as the keys of the dictionary and the connection between the vertices also called edges as the values in the dictionary.
https://www.tutorialspoint.com/python_data_structure/python_graphs.htm#:~:text=A%20graph%20can%20be%20easily,the%20values%20in%20the%20dictionary.

## Demonstrate Graphs
```

# Create the dictionary with graph elements
graph = { 
   "a" : ["b","c"],
   "b" : ["a", "d"],
   "c" : ["a", "d"],
   "d" : ["e"],
   "e" : ["d"]
}
# Print the graph 		 
print(graph)
```
