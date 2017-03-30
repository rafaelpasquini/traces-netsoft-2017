# traces-netsoft-2017
Traces used in Learning End-to-end Application QoS from OpenFlow Switch Statistics - IEEE Netsoft 2017.

The datasets available in this repository are under the license CC-BY-4.0.
The full terms are describe in the LICENSE.txt file in the root folder and also in the following link:
https://creativecommons.org/licenses/by/4.0/

If you make any use of such datasets, please refer to it as follows:

Rafael Pasquini and Rolf Stadler. "Learning End-to-end Application QoS from OpenFlow Switch Statistics". 
In: 3rd IEEE Conference on Network Softwarization (IEEE NetSoft 2017), 3-7 July 2017, Bologna, Italy.

The authors can be contact through:
rafael.pasquini@ufu.br
stadler@kth.se

# Description of traces

Collected statistics for X_cluster, X_port and X_flow are stored in csv files. A csv file contains m rows of n features. Each row represents one observation and has a timestamp t indicating when the statistics were measured. Collected service-level metrics for VoD and KV are stored in Y.csv files together with the observation time t.

During experiments, X and Y statistics are collected every second on the testbed. For each application running on the testbed, the data collection framework produces a time series {(Xt, Yt)}t. We interpret this time series as a set of samples {(X1, Y1), ..., (Xm, Ym)}. Assuming that each sample (Xt, Yt) in the set is drawn uniformly at random from a joint distribution (X, Y), we obtain models using methods from statistical learning.
