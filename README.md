# pyprofile
A list of easy to use resources for python profiling

### First step - get the overall memory footprint

[`ps_mem.py`](https://github.com/pixelb/ps_mem/) is an excellent place to start.
```
(py3) hardik@shire:~/pyprofile$ python3 ps_mem.py -p 32747
 Private  +   Shared  =  RAM used	Program

553.4 MiB +   2.4 MiB = 555.8 MiB	python3
---------------------------------
                        555.8 MiB
=================================
```

[Stackoverflow link](https://stackoverflow.com/questions/131303/how-to-measure-actual-memory-usage-of-an-application-or-process) for this question.

### Next steps
https://www.huyng.com/posts/python-performance-analysis
