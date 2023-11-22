## Computer Architecture
- In Software Engineering, we mostly focus on four main components in a Computer Architecture including Disk, RAM, CPU and Cache. Those four components plays as building blocks of a computer, and in this section, we will learn about the importance and role of each component.

# Disk
- A disk is a primary storage device within a computer. 
- The data stored in disk is persistent which means in situations of crashes, disasters, sudden restarts, the data will not be lost.
- Nowsaday (in 2023), most disk stores ranging from Gygabytes up in Terabytes (~1 trillion bytes, 1 byte = 8 bits) which is pretty large.
- In order to write/ read to disk, it is measured in miliseconds (10^-3 seconds)

# RAM
- RAM (Random Access Memory) is also used to store data but a lot smaller in size, more expensive and more efficient.
- RAM stored data is not persitent unlike Disk (described as volatile memory which means got erased once computer is shut down).
- A size of a typical RAM is measured in GBs (1-128GBs of data).
- Running applications/ programs' code will be stored in memory, as the CPU read/write from/to RAM to execute the code, the declared variables/ data in code will also be store in memory. 
- RAM and disk does not directly communicate with each other but are dependent on CPU faciliating data between those two hardwares.
- Much faster to write/ read to RAM which is measured in microseconds (10^-6 seconds)

# CPU 
- CPU (Central Processing Unit) is intermediate device between RAM and disk.
- It faciliates transfering data between RAM and disks intelligently, in other words, the CPUs reads and execute instructions stored in RAM, which may involve data manipulation data stored somewhere else in the Disk or RAM itself. 
- Execution of those instructions is done in matter of miliseconds (10^-3 seconds)

# Cache
- Cache is a sub component of CPU which is much more efficient, but much more expensive and smaller than other devices.
- Stores in order of KBs or MBs which is significantly smaller than RAM in size, but the performance is much better (measured in nanoseconds)
- The workflow is instead of looking at the RAM for every read, the CPU will check the cache first to see if the data exists, if not, we fetch from the RAM then store this data into the cache. 
- For situation where the data is frequently fetched or heavily read again and again, this could return in much faster performance. 

# Conclusions
- Three type of memories have its own use cases
- To solve much larger problems, the combination of multiple computers is needed (distributed system) due to a fact that resources within a single computer are limited despite of cheaper/ faster hardwares. 