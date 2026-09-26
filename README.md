# Python Linked List

A simple implementation of a singly linked list in Python. This project demonstrates how linked lists work using custom nodes and references between nodes.

## Features

- Create a linked list using a custom `LinkedList` class
- Create individual nodes using an inner `Node` class
- Check whether the list is empty
- Add elements to the end of the list
- Remove elements from the list
- Track the number of elements using a length counter
- Maintain a reference to the first node using the head pointer

## How It Works

Each node contains:

- `element` – stores the value
- `next` – points to the next node in the list

The `LinkedList` class maintains:

- `head` – references the first node
- `length` – tracks the number of nodes

### Example

```python
my_list = LinkedList()

print(my_list.is_empty())

my_list.add(1)
my_list.add(2)

print(my_list.is_empty())
print(my_list.length)

my_list.remove(1)
print(my_list.length)
