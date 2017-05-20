Big Data Term Project

# BigData-FlightDataAnalysis

Oozie workflow to process and analyze a large volume of flight data.

--------------------------------------------------------------------------------------------
Find following things using Map-Reduce 

a. The 3 airlines with the highest and lowest probability, respectively, for being on
schedule.

b. The 3 airports with the longest and shortest average taxi time per flight (both in and
out), respectively.

c. The most common reason for flight cancellations.

--------------------------------------------------------------------------------------------
Performed following observation using Oozie workflow

1. Run Oozie workflow to analyze the entire data set (total 22 years from 1987 to 2008) at one
time on two VMs first and then gradually increase the system scale to the maximum allowed number 
of VMs for at least 5 increment steps, and measure each corresponding workflow execution time.

2. Run Oozie workflow to analyze the data in a progressive manner with an increment of 1 year, 
i.e. the first year (1987), the first 2 years (1987-1988), the first 3 years (1987-1989), ..., 
and the total 22 years (1987-2008), on the maximum allowed number of VMs, and measure each 
corresponding workflow execution time.

3. A performance measurement plot that compares the workflow execution time in
response to an increasing number of VMs used for processing the entire data set (22
years) and an in-depth discussion on the observed performance comparison results

4. A performance measurement plot that compares the workflow execution time in
response to an increasing data size (from 1 year to 22 years) and an in-depth 
discussion on the observed performance comparison results
