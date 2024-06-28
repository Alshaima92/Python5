## Data Structures:

### Linked List
- **Definition**: A succession of elements, each of which points back to the next one.
- **Singly Linked List Example**:
  - **Node Class**: Characterizes each node having data and a next pointer.
  - **LinkedList Class**:
    - `__init__`: Initializes the list.
    - `append(data)`: Adds a new element at the end.
`- `__str__`: This should return a string representation of the list.
    - `retrieve_x_node(index)`: Retrieves the node at a specified index.
  **Usage**:
    Adds elements to a created linked list. It prints and retrieves the elements.
- **Methods to Implement**:
  - `prepend(value)`: Adds a new value to the beginning.
  - `delete(value)`: Deletes the first node with the specified value.
- `__len__`: Return the number of nodes
  - `reverse()`: Reverse the list in place

### Doubly Linked List
- **Definition**: Linked list where each node has references to the next and previous nodes.

### Stack
- **Definition**: It is a linear data structure that follows Last-In-First-Out, LIFO.

### Queue
- **Definition**: This is a linear data structure following First-In-First-Out, FIFO.

### Binary Search Tree
- **Definition**: A hierarchical data structure where each node has no more than two children, ordered such in some senses.


### Tree Traversal
- **Definition**: Each node of a tree is visited in a particular order.
- Types:
  - **Inorder**: Visit left subtree, root, right subtree.
- **Preorder**: Visit root, left subtree, right subtree.
  - **Postorder**: Visit left subtree, right subtree, root.


