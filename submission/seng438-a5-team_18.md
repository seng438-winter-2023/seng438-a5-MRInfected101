**SENG 438- Software Testing, Reliability, and Quality**

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:       |   |
|-----------------|---|
| Student Names:  |   |
|                 |   |
|                 |   |
|                 |   |

# Introduction

# 

# Assessment Using Reliability Growth Testing 

# Assessment Using Reliability Demonstration Chart 

# 

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

## Similarities

Both the Reliability Growth Testing and the Reliability Demonstration Chart use failure time intervals or failure count
to calculate properties of the system which can be used to determine whether the system is reliable. Either technique
graphically plots the number of cumulative failures with respect to some measure of time. Although the data in either
case is discrete, the trend of these datapoints are considered when determining system reliability.

## Differences

The Reliability Growth Testing method aims to determine the overall trend at which bugs are found during testing. Using
a greater number of failure data than what can be used within the Reliability Demonstration Chart, the failure data can
be plotted and compared to several different mathematical models to estimate how many failures can be seen in the
future. This starts with the calculation of different models to see potential candidates to which model the data
follows, followed by an analysis of shared properties of those models with respect to the data to determine a line of
best fit. This modelling and estimation is not found within the Reliability Demonstration Chart. This alterate method
uses client and developer-specified metrics to determine when the system is deemed "reliable enough" to be used within
production. These metrics help define three distinct regions within a cartesian plane, which distinguishes whether the
software can be accepted, rejected or requires further testing. Now, as issues are detected, the number of cumulative
failures can be plotted on this graph with respect to when that failure occurred. As a result, it can be seen which
range the newest data point falls into, informing both the client and the developers that the system is satisfactory.

# How the team work/effort was divided and managed

# 

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself
