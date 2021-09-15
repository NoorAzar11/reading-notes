## Implementation: Hash Tables

1.  What is a Hashtable? 

- A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
- Hash Tables are a data structure that allow you to create a list of paired values. You can then retrieve a certain value by using the key for that value, which you put into the table beforehand. 

![img](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Hash_table_simchk_999.svg/500px-Hash_table_simchk_999.svg.png)

2. What is a Buckets?

- A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.

3. What is a Collisions ?

- A collision is what happens when more than one key gets hashed to the same location of the hashtable. 

-  Hashtable Used for :
   1. Hold unique values
   2. Dictionary
   3. Library

 4. Creating a Hash :

- A hashtable traditionally is created from an array. I always like the size 1024. this is important for index placement. After you have created your array of the appropriate size, do some sort of logic to turn that “key” into a numeric number value

![img](https://www.freecodecamp.org/news/content/images/size/w2000/2021/05/JavaScript-Hash-Table.png)

![img](https://miro.medium.com/max/1400/1*GdE4FHYWAQFTtQ_QdscxxA.png)