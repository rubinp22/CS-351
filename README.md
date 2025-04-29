# CS-351

Initial run:

hash-00         359.80 real	   344.54 user	9.00 sys	2884 memory (KB)
hash-01         20.34 real	   16.89 user	1.52 sys	2896 memory (KB)
hash-02         15.57 real	   14.17 user	1.24 sys	2888 memory (KB)
hash-03         16.47 real	   15.22 user	1.12 sys	2896 memory (KB)
hash-04         14.50 real	   13.85 user	0.54 sys	5012368 memory (KB)

First-run analysis:

On comparing the system performance, the program hash-00 seemed to be significantly the slowest of all programs. As it took the longest for around 359.80 seconds in real time to run the first program using the full time command. In comparing the memory usage between the different programs, the hash-01 program and the hash-03 output had around the same memory of 2896 in Kilobytes. Which means the same amount of memory was taken up by the two programs despite the real time they each took in seconds to execute. With the same memory of 2896 KB, the hash-03 program executed 3.87 sec faster in real time, and .12 sec faster in system time than in hash-01 while using the same memory. With a second outlier being hash-04 it had the fastest performance of 14.5 seconds in real time, although it came at the cost of taking the greatest amount of memory. 

When seeing hash-04 performs the fastest with 2 sec more than hash-03, and by up to 6 sec than hash-0, the amount of memory is definitely not proportionate in comparison. Because the difference in memory for hash-04 is having 5,009,477 KB greater than the average (2891 KB) of all the other four programs. Which makes the hash-04 inefficient by a large sum in memory usage and for it’s program to run the fastest. 

To maximize efficiency I would need to take in the factors of both time and memory usage into account. And in hash-00 which took the greatest amount of time in 359.80 seconds and hash-04 which then took the greatest memory. Both of those outliers over compensated in time or memory by optimizing one of them from my point of view. The most time and memory efficient program would have to be hash-02 with the best time space complexity. Since it had the fastest time (15.57 seconds), and least amount of memory usage (2888 kb), from considering the more averaged out files from the hash-01 to hash-03 programs. 

Hash Optimization run:

344.95 real	331.27 user	10.20 sys	2888 memory (KB)
14.85 real	7.46 user	2.98 sys	2880 memory (KB)
7.82 real	6.52 user	0.99 sys	2880 memory (KB)
7.45 real	6.31 user	1.02 sys	3468 memory (KB)
6.72 real	6.23 user	0.39 sys	5012360 memory (KB)


Optimization analysis:

In comparing the timing for my optimized runs, hash-00 has improved in both real time and user time. Hash-01 has very much increased the speed with Real time going from 20 sec to 14, and user time from around 17 sec to 7.5. The programs hash-02 to hash-04 were the most significant since their averages of around 15 (real sec) and 14 (user sec) times have increased in speed to averaging 7 seconds in real time and 6 dec in user time for those three programs. Though the Unit that had not had a predictable or stable change in measures were system time. Because they were around 9 sec for hash 0, and 1 sec for hash 1 to 3 at the initial runs. While for the optimized ones their system times were more rather broadley varied in my perspective than observing their initial run. The last two programs hash-03 and hash-04 seemed to be outliers as hash-03 increased in memory usage from 2896 kb to 3468 kb to compensate for greater its speed. And hash-4 program had stayed roughly the same in really high memory from 5012368 to 5012360 kilobytes. So if I were to compare the most optimized programs, it would be from hash-00 to hash-02 options. Where hash-02 and hash-03 had similar times for real time (between 7.82 and 7.45 sec) and similar for user time (6.52 and 6.31 sec). Though because hash two far outweighed in memory with taking only 2880 Kb over 3468 kb, then I would choose the second hash program, which although around seconds slower, the hash-02 has the highest memory to run time speed in the optimized version.
