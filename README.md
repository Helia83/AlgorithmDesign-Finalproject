# MST Clustering on Bitcoin Trust Network

This project analyzes the Bitcoin OTC trust network by applying **K-Means clustering** and computing **Minimum Spanning Trees (MST)** on the resulting clusters. It demonstrates algorithm design, graph theory, and performance optimization with multithreading.

## Dataset
The dataset used is `soc-sign-bitcoinotc.csv`, which represents signed edges (trust scores) between users in a social network.

## Project Breakdown

- **Part 1:** Load the dataset, construct a graph with edge weights (trust values), and compute the MST for the whole graph.
- **Part 2:** Apply **K-Means** clustering to group the nodes and compute MSTs for each cluster using parallel threads.
- **Part 3:** Merge all MSTs to form a final optimized graph and compute the overall cost.

## Technologies Used

- Python
- NetworkX
- Pandas
- Scikit-learn (KMeans)
- Threading
- CSV I/O

## Collaboration & AI Usage

This project was completed for the "Design and Analysis of Algorithms" course.  
It was a **collaborative effort** between me and a classmate.

We also used **ChatGPT** to help us:
- Brainstorm algorithmic approaches
- Debug code
- Optimize performance

All code was written, tested, and structured by us, with AI acting as a support tool in the learning process.

## Performance Output

- MST total cost
- Execution time before and after clustering
- Cost per cluster and overall merged result

