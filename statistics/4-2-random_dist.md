[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

>> randoms = np.random.random(1000)  

>> pmf = thinkstats2.Pmf(randoms, label = 'random')  
>> thinkplot.Pmf(pmf, align='right', linewidth=.1)  

This PMF represents how every value has an equal probability (1/1000).

>> cdf = thinkstats2.Cdf(randoms, label = 'random')  
>> thinkplot.Cdf(cdf)  
>> thinkplot.Config(xlabel='Random Numbers', ylabel='CDF')  

The CDF is approximately a line with a slope of 1, but it isn't exactly a uniform distribution.
