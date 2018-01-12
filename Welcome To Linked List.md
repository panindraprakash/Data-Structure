                                                  Welcome To Data Structures

* Data Structure is a particular way of organizing and  storing data in a computer which can be accessed and modified efficiently.

* Topics In Data Structure(DS)

01 Linked List                          06 Binary search Tree
02 Array                                07 Heap
03 Stack                                08 Harshing
04 Queue                                09 Graph
05 Binary Tree                          10 Advanced Data Structure
11 Matrix                               11 Misc

                                                       Linked List 

* Linked list is a linear data structure,they are not stored at contiguous location unlike arrays but the elements are linked using pointers.

* Advantages Of Linked list
01 Dynamic Size ( We can add elements Dynamicaly,Unlike in Array we must know the upper limit on the number of elements in advance.)
02 Easy of Insertion and Deletion ( Using Pointer as link we can easly add or delete elements in between but in Array to Inserting a new element room has to be created,To create room existing elements have to shifted)

* Drawbacks
01 Random access is not allowed,We have to start from first Node so Binary Search is not possible ( In Array using index random acces is possible)
02 Extra Memory space for a pointer is required with each element of the list.

* Types of Linked List 
01 Single   Linked List
02 Doubly   Linked List
03 Circular Linked List

* ** Single Linked List ** 
 In a singly Linked list every element contains some data and a link to the next element.

 The elements of a linked list are called the nodes.In a singly Linked List a node has two fields data and next. The data field contains the data being stored in that specific node. It cannot just be a single variable. There may be many variables presenting the data section of a node. The next field contains the address of the next node. So this is the place where the link between nodes is established.

     NODE
-----------------             ----------------  
|        |       |            |        |      |
|  Data  | Next  | ---------> |  Data  | Next |
|        |       |            |        |      |  
------------------            -----------------

Node Address
    1001                            1002                         1003
-----------------             ----------------             ----------------    
|        |       |            |        |      |            |        |      |
|   25   | 1002  | ---------> |   50   | 1003 | ---------> |   75   | 1004 |
|        |       |            |        |      |            |        |      | 
------------------            -----------------            -----------------

* ** Doubly Linked List ** 
In a Doubly Linked List every node in a list contains some data a link to the next node and a link to the previous node.

Head
    Node Adress                                                     
--------------------------            --------------------------            --------------------------   
|      |         |       |            |      |         |       |            |      |         |       |
| Null |   Data  | Next  | ---------> | Prev |   Data  | Next  | ---------> | Prev |   Data  | Next  | 
|      |         |       | <--------- |      |         |       | <--------- |      |         |       | 
|      |         |       |            |      |         |       |            |      |         |       | 
--------------------------            --------------------------            --------------------------

Head
    Node Adress                                                     
          1001                                  1002                                 1003
--------------------------            --------------------------            --------------------------   
|      |         |       |            |      |         |       |            |      |         |       |
| Null |    25   | 1002  | ---------> | 1001 |    50   | 1003  | ---------> | 1002 |    75   | 1004  | 
|      |         |       | <--------- |      |         |       | <--------- |      |         |       | 
|      |         |       |            |      |         |       |            |      |         |       | 
--------------------------            --------------------------            --------------------------

* Advantages Of Linked list
Doubly Linked List can be traversed in both forward and backward direction.
The Delete operation in Doubly Linked List is more efficient if pointer to the node to be deleted is given.

* Drawbacks
Every node required extra space to store previous pointer.[It is possible to implement Doubly Linked List with single pointer]

                                             Implementation Of Linked List


                                             

