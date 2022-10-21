# Queues
A queue is a collection of objects that supports fast first-in, first-out (FIFO) semantics for inserts and deletes. The insert and delete operations sometimes called enqueue and dequeue. Unlike lists or arrays, queues typically don't allow for random access to the objects they contain.
https://dbader.org/blog/queues-in-python#:~:text=A%20queue%20is%20a%20collection,to%20the%20objects%20they%20contain.

## Demonstrate Queues

```
# How to use Python's list as a FIFO queue:

'''
'''
q = []

q.append('eat')
q.append('sleep')
q.append('code')

>>> q
['eat', 'sleep', 'code']

# Careful: This is slow!
>>> q.pop(0)
'eat'
```
