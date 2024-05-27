
![](images/banner.png)







<img src="images/htb.png" style="margin-left: 20px; zoom: 60%;" align=left />    	<font size="10"> <b>Redeemer<b></font>

​		21<sup>th</sup> 5 2024

​		Challenge Author(s): 
   HTB
​		

 






### Difficulty: `Very easy`

### Flag: `03e1d2b376c37ab3f5319922053953eb`


# Solver: Nikolaos Bermparis


Which TCP port is open on the machine? 
```6379/tcp```

Which service is running on the port that is open on the machine? 
```redis```

What type of database is Redis? Choose from the following options: (i) In-memory Database, (ii) Traditional Database 
```In-memory Database```

Which command-line utility is used to interact with the Redis server? Enter the program name you would enter into the terminal without any arguments. 
```redis-cli```

Which flag is used with the Redis command-line utility to specify the hostname? 
```-h```

<img src="images/Screenshot 2024-05-28 022932" />  

Once connected to a Redis server, which command is used to obtain the information and statistics about the Redis server? 
```info```

What is the version of the Redis server being used on the target machine? 
```5.0.7```

Which command is used to select the desired database in Redis? 
```select```

How many keys are present inside the database with index 0? 
```4```

Which command is used to obtain all the keys in a database? 
```keys *```

Submit root flag
```03e1d2b376c37ab3f5319922053953eb```

https://www.hackthebox.com/achievement/machine/853890/472



<img src="images/Screenshot 2024-05-20 223226.png" />  

With a little bit of research the file  is written in x86 assembly language, specifically targeting the Intel 32-bit architecture (also known as i386)

<img src="images/KL_Intel_i386DX.jpg" /> 

