# Instructor comments

1. You forgot to explain vectorization and broadcasting in your own words.
1. Nicely done on the plot annotations.
1. The 3D plot had issues. Try this tutorial: http://www.scipy-lectures.org/intro/matplotlib/index.html#d-plots  (In general, http://www.scipy-lectures.org is a very good resource for examples and helpful information. I had linked it in the syllabus and in the info repository, but this is a good reminder to revisit it!)
1. For the Lorentzian sampling, you still sampled a Gaussian (using randn samples from a normal distribution, i.e., a Gaussian). You should use the cauchy random sampling function instead.
