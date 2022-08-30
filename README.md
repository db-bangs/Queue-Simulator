# Call Centre Queue Simulator
A simulated call centre dataset and notebook, designed to be used as a classroom / tutorial dataset for Business and Operations Analytics.

This notebook details the creation of simulated call centre logs over the course of one year. For this dataset we are imagining a business whose lines are open from 8:00am to 6:00pm, Monday to Friday. Four agents are on duty at any given time and each call takes an average of 5 minutes to resolve.

The call centre manager is required to meet a performance target: **90% of calls must be answered within 1 minute**. Lately, the performance has slipped. As the data analytics expert, you have been brought in to analyze their performance and make recommendations to return the centre back to its target.

The dataset records timestamps for when a call was placed, when it was answered, and when the call was completed. The total waiting and service times are calculated, as well as a logical for whether the call was answered within the performance standard.

# Discrete-Event Simulation

**Discrete-Event Simulation** allows us to model real calling behaviour with a few simple variables. 

- Arrival Rate
- Service Rate
- Number of Agents

The simulations in this dataset are performed using the package [**simmer**](https://r-simmer.org/) (Ucar *et al.,* 2019). I encourage you to visit their website for complete details and fantastic tutorials on Discrete-Event Simulation.

Ucar I, Smeets B, Azcorra A (2019). “simmer: Discrete-Event Simulation for R.” *Journal of Statistical Software*, 90(2), 1–30.
