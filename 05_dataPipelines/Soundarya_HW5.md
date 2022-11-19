HW: Vary the parallel_threads and prefetch_buffer_size parameters at the top of train_resnet34.py and make a table of how the mean image rate changes.

No. of parallel threads 	  buffer_size		Mean rate of images/sec
	16				8			592
	32				8			674
	64				8			725
	128				8			834
	128				16			856
	128				32			915


Image processing mean rate increases with increase in no. of steps and buffer size. Increase in the number of parallel threads from 16 - 128 also increases the image rate and a highest increase is noted when buffer size goes from 16 to 32.


