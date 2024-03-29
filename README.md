# Java Collections Framework quick guide
A quick guide for the Java Collections Framework

## Queues 

| Implementation        | offer    | peek | poll     | size | 
|:---------------------:|:--------:|:----:|:--------:|:----:|
| PriorityQueue         | O(log n) | O(1) | O(log n) | O(1) |
| ConcurrentLinkedQueue | O(1)     | O(1) | O(1)     | O(n) |
| ArrayBlockingQueue    | O(1)     | O(1) | O(1)     | O(1) |
| LinkedBlockingQueue   | O(1)     | O(1) | O(1)     | O(1) |
| PriorityBlockingQueue | O(log n) | O(1) | O(log n) | O(1) |
| DelayQueue            | O(log n) | O(1) | O(log n) | O(1) |
| LinkedList            | O(1)     | O(1) | O(1)     | O(1) |
| ArrayDeqeue           | O(1)     | O(1) | O(1)     | O(1) |
| LinkedBlockingDequeue | O(1)     | O(1) | O(1)     | O(1) |


## Lists


| Implementation       | get  | add  | contains | next | remove | iterator.remove |
|:--------------------:|:----:|:----:|:--------:|:----:|:------:|:---------------:|
| ArrayList            | O(1) | O(1) | O(n)     | O(1) | O(n)   | O(n)            |
| LinkedList           | O(n) | O(1) | O(n)     | O(1) | O(1)   | O(1)            |
| CopyOnWriteArrayList | O(1) | O(n) | O(n)     | O(1) | O(n)   | O(n)            |
