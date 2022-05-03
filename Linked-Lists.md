# Linked Lists
  ## Advantages
   - Easy insertion and deletion
   - Dynamic size
  ## Drawbacks
   - Not cache friendly as storage is not contiguous unlike arrays
   - Random acesses are not allowed, have to traverse the entire list sequentially
   - Extra memory for pointer required with every element

  ## Representation
  ### C
  ```c
  struct Node{
    int data;
    struct Node* next;
  }
  ```
  ### C++
  ```c++
  class Node {
  public:
      int data;
      Node* next;
  };
  ```
  ## Traversal
  ```c
  Node* n = head;
  while(n != null)
  {
    n = n->next;
  }
  ```
