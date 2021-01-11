# AIOps - Papers and Tutorials
AwesomeAIOps (Papers, Tutorials, and Datasets)

## Tutorials and Suveys
1. Awesome AIOps [[GitHub](https://github.com/linjinjin123/awesome-AIOps)]
2. Anomaly Detection : A Survey [[Paper](http://cucis.ece.northwestern.edu/projects/DMS/publications/AnomalyDetection.pdf)]
3. AIOps based on machine learning (Chinese) [[Slides](https://netman.aiops.org/wp-content/uploads/2016/12/%E5%9F%BA%E4%BA%8E%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E7%9A%84%E6%99%BA%E8%83%BD%E8%BF%90%E7%BB%B4v1.6.pdf)]
4. A collection of tools and datasets for anomaly detection on time-series data [[GitHub](https://github.com/rob-med/awesome-TS-anomaly-detection)]

## Papers
1. GRANO: Interactive Graph-based Root Cause Analysis for Cloud-Native Distributed Data Platform (VLDB 2019) [[Paper](https://dl.acm.org/doi/pdf/10.14778/3352063.3352105)] 🌟
> * Key points (from Sec 3): use graph modeling and propagation algorithm to measure the importance of detection events and minimize the effect of false positive alarms
> * Step 1 - Graph Construction, which forms a unified anomaly graph G = (V, E). V contains (1) the set of system components, and (2) the set of alarms and events retrieved. Each edge in E represents the interdependency between components.
> * Step 2 - Alarm Edge Scoring, which evaluates the alarm’s importance to a connected system component.
> * Step 3 - Component Node Scoring, which calculates the aggregated confidence score on the components, using the criticality of the alarms and the edges’ score that connected to a component.
> * Step 4 - Score Propagation, which detects the actual root cause.

2. iDice: Problem Identification for Emerging Issues (ICSE 2016) [[Paper](https://dl.acm.org/doi/pdf/10.1145/2884781.2884795)]
> * identify the effective combination for an emerging issue with high quality and performance.
3. Opprentice: Towards Practical and Automatic Anomaly Detection Through Machine Learning (IMC 2015) [[Paper](http://conferences2.sigcomm.org/imc/2015/papers/p211.pdf)]
4. HotSpot: Anomaly Localization for Additive KPIs With Multi-Dimensional Attributes (IEEE Access 2018) [[Paper](https://ieeexplore.ieee.org/document/8288614)]
5. AutoMAP: Diagnose Your Microservice-based Web Applications Automatically (WWW 2020) [[Paper](https://dl.acm.org/doi/pdf/10.1145/3366423.3380111)] [[GitHub](https://github.com/rshriram/pymicro)] [[Notes](https://mp.weixin.qq.com/s?__biz=Mzg3NDUwNTM3MA==&mid=2247485389&idx=1&sn=1914974878864d2d77131a1ec998fd17&chksm=cecef238f9b97b2e7e66c7d133cf743479289eb5fba7cfa85c094a3ce494fa1cb49efa997add&cur_album_id=1573418835687309313&scene=189#rd)]
> * (1) Sampling, (2) Build anomaly behavior graph, (3) graph correction, (4) heuristic root cause detection algorithm on the graph, (5) performance analysis, (6) update the weights.
6. Graph-based root cause analysis for service-oriented and micro service architectures (The Journal of Systems and Software 2020) [[Paper](https://www.datsi.fi.upm.es/~mperez/pub/jss-2019.pdf)]
7. Performance Monitoring and Root Cause Analysis for Cloud-hosted Web Applications (WWW 2017) [[Paper](https://dl.acm.org/doi/pdf/10.1145/3038912.3052649)]
8. Survey on Models and Techniques for Root-Cause Analysis [[Paper](https://arxiv.org/pdf/1701.08546.pdf)]
9. Graph-Based Trace Analysis for Microservice Architecture Understanding and Problem Diagnosis (FSE 2020) [[Paper](http://taoxie.cs.illinois.edu/publications/esecfse20in-trace.pdf)]
> * The same author as GRANO.
> * GMTA, a graph-based approach of microservice trace analysis, for understanding architecture and diagnosing various problems.
> * GMTA abstracts traces into different paths and further groups them into business flows. To support various analytical applications, GMTA includes an efficient storage and access mechanism by combining a graph database and a real-time analytics database and using a carefully designed storage structure.


## Summary
1. WeBank project - AIOps + KG [[Link](https://mp.weixin.qq.com/s/50z2fNYBZEsf9C-94L0-QQ)]
2. Paper Summary (Chinese) [[Link](https://mp.weixin.qq.com/s/ILXnXQulDVFwmHdNtEcXng)]
3. Meituan project [[Link](https://tech.meituan.com/2020/10/15/mt-aiops-horae.html)]
