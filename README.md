# Simulating-Election-Result
Simulating the outcome of an election based on a simple probabilistic model estimated from polls data. Assume that there are two political parties, which we refer to as the Democrats and the Republicans. There is a number of regions participating in the election, and each region has a certain number of delegates that can be awarded to one of the two parties. Within each region, the party receiving the most votes will be awarded all of the delegates from that region. Assume also that the number of votes each party receives within each region is drawn from a normal distribution with a given mean and standard deviation.


For example, consider the following sample data with four regions. The first two columns denote the mean and standard deviation of the number of votes for Democrats in each region. The next two columns denote the same information for the Republicans. The final column states the number of delegates in each region. A likely outcome of the election is that the Democrats win the first two regions, with a total delegate count of 25, while the republicans win the other two regions, with a total delegate count of 23. Of course, there are other possible outcomes, and the likelihood of each outcome depends on the given means and standard deviations.

Region A	10	2	8	1.5	15
Region B	8	1.5	6	1	10
Region C	6	1	8	2	13
Region D	5	1	8	1	10
