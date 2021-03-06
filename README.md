# pthread_test!
  ![Imgur](https://i.imgur.com/DPPbweS.png)
- I have tested concurrency and implemented it in my program.
- As algorithm to divide, I used prime factorization
- We can see from the plot, that the more threads we use, the faster algorithm is going. But according to Amdahl's Law, using more and more processors won't give boost.
# Speed of algorithm
  ![Imgur](https://i.imgur.com/7OrIDXl.jpg)
- There we can see the speed of algorithm using different amount of threads.
- So if we extrapolate the plot, we'll observe that increasing the amount of cores, won't boost our algorithm more and more.
# Amdahl's Law
 ![Imgur](https://i.imgur.com/d4JOD0L.jpg)
 ![wiki](https://wikimedia.org/api/rest_v1/media/math/render/svg/4ddfe7ea1f14ac8da03a6eda65459d1f8d85f6b9)
- where (used data from wikipedia https://en.wikipedia.org/wiki/Amdahl%27s_law)
- S latency is the theoretical speedup of the execution of the whole task;
- s is the speedup of the part of the task that benefits from improved system resources;
- p is the proportion of execution time that the part benefiting from improved resources originally occupied.
