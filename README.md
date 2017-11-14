# Homework of 11/13

**Due: 11/18**

## Merge two sorted array

Include test cases.

Name: `merge.cpp`

## Queue implementation using Stack

Your queue should be a `class` and need to have these functions:
```
class Queue{
public:
	Queue(){};
	void push(int x);
	void pop();
	int front();
	int size();
	bool empty();	
}
```

Name: `queue.cpp`

## Stack implementation using Queue

Your stack should be a `class` and need to have these functions:
```
class Stack{
public:
	Stack(){};
	void push(int x);
	void pop();
	int top();
	int size();
	bool empty();	
}
```

Name: `stack.cpp`

## BFS & DFS

Create your own graph abstracted from reality such as relationship, at least 6 nodes.
Store them in a linked table.
And traverse each node using BFS and DFS.

**And while you're solving this problem, try to build your own** `Graph` **class**.

If possible, implement BFS and DFS using recursive method.

Structure:
`Graph.h`
`Graph.cpp`
`graph_test.cpp` includes `main()` function and the graph instance.
