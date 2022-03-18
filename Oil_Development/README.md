# Optimization of gold recovery

Based on the data on the parameters of gold ore processing , models were trained to predict the efficiency of the process.

Data preprocessing was conducted. NA values were found in the input data, which were filled in by neighboring values, and anomalies, for example, zero concentrations of substances at some stages. Lines with anomalies have been removed.



The best results (smaller sMAPE metric) were obtained using the random forest model. 

Despite all efforts, the resulting model performs worse than the random one. 