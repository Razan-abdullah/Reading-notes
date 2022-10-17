# data structures

---

A data structure is a specialized format for organizing, processing, retrieving and storing data. There are several basic and advanced types of data structures, all designed to arrange data to suit a specific purpose. Data structures make it easy for users to access and work with the data they need in appropriate ways.


---

## Why are data structures important?


Typical base data types, such as integers or floating-point values, that are available in most computer programming languages are generally insufficient to capture the logical intent for data processing and use. Yet applications that ingest, manipulate and produce information must understand how data should be organized to simplify processing. Data structures bring together the data elements in a logical way and facilitate the effective use, persistence and sharing of data. They provide a formal model that describes the way the data elements are organized.


### How are data structures used?


In general, data structures are used to implement the physical forms of abstract data types. Data structures are a crucial part of designing efficient software. They also play a critical role in algorithm design and how those algorithms are used within computer programs.


#### Some examples of how data structures are used include the following:

* Storing data. Data structures are used for efficient data persistence, such as specifying the collection of attributes and corresponding structures used to store records in a database management system.
* Managing resources and services. Core operating system (OS) resources and services are enabled through the use of data structures such as linked  lists for memory allocation, file directory management and file structure trees, as well as process scheduling queues.

* Data exchange. Data structures define the organization of information shared between applications, such as TCP/IP packets.
* Ordering and sorting. Data structures such as binary search trees -- also known as an ordered or sorted binary tree -- provide efficient methods of sorting objects, such as character strings used as tags. With data structures such as priority queues, programmers can manage items organized according to a specific priority.
* Indexing. Even more sophisticated data structures such as B-trees are used to index objects, such as those stored in a database.
* Searching. Indexes created using binary search trees, B-trees or hash tables speed the ability to find a specific sought-after item.
* Scalability. Big data applications use data structures for allocating and managing data storage across distributed storage locations, ensuring scalability and performance. Certain big data programming environments -- such as Apache Spark -- provide data structures that mirror the underlying structure of database records to simplify querying.



---

# Linked List :

---

A linked list is a sequence of data structures, which are connected together via links.

Linked List is a sequence of links which contains items. Each link contains a connection to another link. Linked list is the second most-used data structure after array. Following are the important terms to understand the concept of Linked List.

Link − Each link of a linked list can store a data called an element.

Next − Each link of a linked list contains a link to the next link called Next.

LinkedList − A Linked List contains the connection link to the first link called First



---



## Types of Linked List:


Following are the various types of linked list.

* Simple Linked List − Item navigation is forward only.

* Doubly Linked List − Items can be navigated forward and backward.

* Circular Linked List − Last item contains link of the first element as next and the first element has a link to the last element as previous.




### Linked List Representation


Linked list can be visualized as a chain of nodes, where every node points to the next node.

![u](./linked_list.jpg)


---


## Basic Operations


Following are the basic operations supported by a list.

* Insertion − Adds an element at the beginning of the list.

* Deletion − Deletes an element at the beginning of the list.

* Display − Displays the complete list.

* Search − Searches an element using the given key.

* Delete − Deletes an element using the given key.