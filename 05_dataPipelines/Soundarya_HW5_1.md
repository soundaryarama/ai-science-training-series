HW: Vary the parallel_threads and prefetch_buffer_size parameters at the top of train_resnet34.py and make a table of how the mean image rate changes.

 

Image processing mean rate increases with increase in no. of steps and buffer size. Increase in the number of parallel threads from 16 - 128 also increases the image rate and a highest increase is noted when buffer size goes from 16 to 32.