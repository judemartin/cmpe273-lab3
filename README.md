# cmpe273-lab3




The purpose of this lab is to understand how to implement a RESTful persistent key-value data store using Chronicle Map.



The limitation of the current implementation is the data will be lost whenever a node is goes down. To locally persist the data, you will use Chronicle Map to store the key-value hashmap into a file system. You are going to implement a new class called ChronicleMapCache using the same interface: CacheInterface and then replace the existing implementation with the new ChronicleMapCache.java. Finally, delete InMemoryCache.java from the code base.
