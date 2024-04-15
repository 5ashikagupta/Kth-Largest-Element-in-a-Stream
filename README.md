# Kth Largest Element in a Stream
This class aims to efficiently find the kth largest element in a stream of integers. 
It utilizes a min-heap to keep track of the k largest elements encountered so far.
#### Approach
Initialization: The class is initialized with the parameters k and nums, creating a min-heap.

Population: The min-heap is populated with the first k elements from nums.

Heap Adjustment: The heap is maintained to contain only the k largest elements.

Adding Elements: New elements are added to the heap while ensuring its size remains <= k.

Heap Size Check: If the heap size exceeds k, the smallest element is removed.

Query: When requested, the current kth largest element is returned.
