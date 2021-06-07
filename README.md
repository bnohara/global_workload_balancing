# Global Workload Balancing
Framework and analysis for balancing workload across regions at my job. The data has been altered, but the logic is the same as what I used in real life.

Our team has staff in 3 regions, let's call them region A, B, and C. Over time, certain regions have encountered bandwidth limits. Meanwhile, other regions had relatively lower workload. When this happens, we want to reassign tasks from the high workload region to a lower workload region. In this project, we'll do the following:
1. Look at some simple methods for projecting task count in the near future
2. Provide a framework for determining the capacity for each region
3. Calculate how many tasks to transfer between regions to achieve balanced volume

The Jupyter notebook has the code, visualizations, and analysis for this project. The csv files are the altered query results from an internal database.
