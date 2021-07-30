# Network Intrusion Detection using Apriori
In this Notebook Apriori is implemented to detect Network Intrusion.
### Features
- A dataset was obtained which consists of a wide variety of intrusions simulated in a military network environment. 
- The dataset contains _22544 rows_ and _41 columns_ (3 qualitative and 38 quantitative features).
- The class variable has two categories:  1.
Normal 2. Anomalous
- The dataset was pre-processed to convert both Categorical and continuous data into binaryformat and was then applied to apriori to generate frequent itemsets, Rules were generated fromfrequent itemsets with a threshold support and confidence
- Finally the rules having consequent as"normal" or "anomaly" were generated
