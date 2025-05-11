
Results for runTrials and iota.gpu:

|Vector<br>Length|Wall Clock<br>Time|User Time|System Time|
|:--:|--:|--:|--:|
|10| 0.30| 0.01| 0.28|
|100| 0.21| 0.00| 0.20|
|1000| 0.22| 0.00| 0.21|
|10000| 0.21| 0.00| 0.20|
|100000| 0.21| 0.01| 0.20|
|1000000| 0.22| 0.01| 0.20|
|5000000| 0.25| 0.02| 0.22|
|100000000| 0.81| 0.16| 0.64|
|500000000| 3.29| 0.82| 2.46|
|1000000000| 6.82| 1.71| 5.10|
|5000000000|37.13| 7.90|29.23|


Results for runTrials and iota.cpu

|Vector<br>Length|Wall Clock<br>Time|User Time|System Time|
|:--:|--:|--:|--:|
|10| 0.00| 0.00| 0.00|
|100| 0.00| 0.00| 0.00|
|1000| 0.00| 0.00| 0.00|
|10000| 0.00| 0.00| 0.00|
|100000| 0.00| 0.00| 0.00|
|1000000| 0.00| 0.00| 0.00|
|5000000| 0.02| 0.00| 0.02|
|100000000| 0.54| 0.08| 0.45|
|500000000| 2.97| 0.41| 2.55|
|1000000000| 5.96| 0.91| 5.05|
|5000000000|33.32| 5.95|27.36|

Shortanswer1:

The results for the iota GPU file were not what I expected, especially based on the speed of its output. I noticed that the CPU version from the runTrials and iota.cpu execution was much faster in comparison. The GPU took longer even for the smaller amount of elements being processed.

I think CUDA isn’t as great as a solution, because the memory overhead from the GPU is high when executing the file. Also since the iota operation doesn’t involve as much heavy computation, the parallelism of the GPU isn’t as fully being used. And because the iota cpu file can handle smaller input sizes more efficiently, the GPU slows down due to the extra time needed to allocate and move its memory for the GPU to run their tasks.
