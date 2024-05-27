
![](images/banner.png)







 	

​		28<sup>th</sup> 5 2024

​		Challenge Author(s): 
   HTB
​		

 

### Difficulty: `Very easy`

### Flag: `03e1d2b376c37ab3f5319922053953eb`


# Solver: Nikolaos Bermparis



### What is Redis?
Redis is an open source in-memory data store that can be used as a database, cache, or message broker. It's often used for caching web pages and reducing the load on servers. Redis also has some features that make it attractive for use as a database, such as support for transactions and publish/subscribe messaging.


Which TCP port is open on the machine? 
```6379/tcp```

<img src="images/Screenshot 2024-05-28 022107.png" />  

Which service is running on the port that is open on the machine? 
```redis```

What type of database is Redis? Choose from the following options: (i) In-memory Database, (ii) Traditional Database 
```In-memory Database```

Which command-line utility is used to interact with the Redis server? Enter the program name you would enter into the terminal without any arguments. 
```redis-cli```

Which flag is used with the Redis command-line utility to specify the hostname? 
```-h```

<img src="images/Screenshot 2024-05-28 022932.png" />  

Once connected to a Redis server, which command is used to obtain the information and statistics about the Redis server? 
```info```

<img src="images/Screenshot 2024-05-28 023020.png" />  

What is the version of the Redis server being used on the target machine? 
```5.0.7```

Which command is used to select the desired database in Redis? 
```select```

How many keys are present inside the database with index 0? 
```4```

<img src="images/Screenshot 2024-05-28 023133.png" />  

Which command is used to obtain all the keys in a database? 
```keys *```

<img src="images/Screenshot 2024-05-28 023300.png" />  

Submit root flag
```03e1d2b376c37ab3f5319922053953eb```

<img src="images/Screenshot 2024-05-28 023327.png" />  

https://www.hackthebox.com/achievement/machine/853890/472


