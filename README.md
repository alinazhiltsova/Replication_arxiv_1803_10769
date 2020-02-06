# Replication_arxiv_1803_10769
This is Alina Zhiltsova's attempts at recreating research from arXiv:1803.10769 Network Traffic Anomaly Detection Using Recurrent Neural Networks (NLP+Network Security)


The paper is available here - https://arxiv.org/abs/1803.10769

Benjamin J. Radford, Leonardo M. Apolonio, Antonio J. Trias, Jim A. Simpson
Proceedings of the 2017 MSS National Symposium on Sensor and Data Fusion

The orginal code can be found here - https://github.com/benradford/replication_arxiv_1803_10769
Data for the replication, ISCX IDS 2012, is available from the Canadian Institute for Cybersecurity - https://www.unb.ca/cic/datasets/ids.html


# Alina's changes
There are the following differences with the original code: 
- used less data - only one XML file rather than all of them to address the time limitations: TestbedMonJun14Flows.xml 
- loaded and parsed XML files using lists for each layer of the file
- changed the code from Python 2 to Python 3, as well as introduced some modelling changes due to library updates
- implemented more epochs
