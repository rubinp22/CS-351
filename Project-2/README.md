


Run Threads Results: 

|Thread<br>Count|Wall Clock<br>Time|User Time|System Time|Speedup|
|:--:|--:|--:|--:|:--:|
|1|15.18|13.79| 0.57|1.00|
|2| 9.27|17.36| 0.64| 1.64|
|3| 5.67|15.12| 0.83| 2.68|
|4| 4.68|16.11| 0.89| 3.24|
|5| 3.76|15.55| 0.99| 4.04|
|6| 3.34|15.90| 1.13| 4.54|
|7| 3.07|16.35| 1.28| 4.94|
|8| 2.81|16.69| 1.32| 5.40|
|16| 2.03|18.03| 3.08| 7.48|
|24| 1.99|18.94| 5.93| 7.63|
|32| 1.98|18.54| 8.58| 7.67|
|40| 1.95|17.61|18.00| 7.78|
|48| 1.96|17.13|17.05| 7.74|
|56| 1.88|16.72|26.11| 8.07|
|64| 1.96|17.25|16.16| 7.74|
|72| 1.99|17.77|13.53| 7.63|
|80| 1.99|17.50|16.40| 7.63|


Graph for run trials:

![Speedup Plot](speedupfile.png)


Timed.cpp output:
Serial setup 6.67e-07 s
Serial setup 5.1788e-05 s
results output 0.129161369 s
main program 14.16137863 s

Short answers: 

Question 1:
Considering how there is a maximum speed factor, it does make me reason how with threads that more of them aren't always better. Working with a greater amount of threads like a turnstile that was mentioned, can not be more efficient if one person can only go at a time. Then just like in Disney world or at BART, there becomes an increase in wait time and the duration for the process in total. It becomes longer and more complex for all the variables of either people or threads in this case to go through. Just like in many computing or even increasing the space time complexity of any program, more threads can make things slower. Especially if just some parts of a program can run one at a time, that can cause both traffic in data processing as well as memory overhead in the program.

Question 2:
Trying to reach perfect scaling may not be possible, because for the serial fraction from (1-p) to become zero would require that every operation is parallelizable which is challenging to make sure. Amdahl’s law does state that a maximum speed can be limited by the fraction of work being serialized. Though one of the most likely effects to attempt to perfectly scale each operation would cause memory or synchronization overhead. As well as limits to the hardware itself to fully parallelize each of its operations. Just as in adding threads in a program there are limits to having positive gains, where how serial and parallelized work can only be done to a certain extent. Since the amount of serialization that can scale can be based on hardware limits and from the overhead in scaling it by each amount.

Question 3: 
In reviewing the graph of the speed-up to threads, the linear increase does show to flatten out after greater threads in the chart. It starts as a steep increase until 7 seconds and then shows around 16 threads to be flat in the positive curve. I think the curve becomes more flat really because there becomes a peak where more threads do not increase at the general speed. Which means that the memory can only handle so many additions to threads before the same time is compensated for every greater amount. As the general slope within the graph was around .57 with rise over run. When using rise 5 - 1 / 8 - 1 to be a positive increase in slope. Where the graph from the Trial runs data showed a similar peek in time, from the range of 6 to 7 seconds as their peak and from the thread count with any more quantity of threads to be placed.
