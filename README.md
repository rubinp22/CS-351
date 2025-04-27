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

