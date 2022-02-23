
# Knowledge Graph-based gene-disease predictions

This repository contains the data and code to produce the figures for the paper titled "Knowledge graphs for indication expansion: an explainable target-disease prediction method" which is submitted to [Network Bioscience Volume II](https://www.frontiersin.org/research-topics/20837/network-bioscience-volume-ii) that is being put together by [Frontiers in Genetics](https://www.frontiersin.org/journals/genetics).

# Authors
Ozge Gurbuz, Gregorio Alanis-Lobato, Sergio Picart-Armada, Miao Sun, Christian Haslinger, Nathan Lawless, Francesc Fernandez-Albert

# Affiliation
Boehringer Ingelheim Pharma GmbH & Co. KG, Biberach (Riss), Germany

# Correspondence: 
Ozge Gurbuz, Francesc Fernandez-Albert
{ozge.gurbuz, francesc.fernandez-albert}@boehringer-ingelheim.com

# Keywords: 
knowledge graphs, ontologies, drug discovery, target repurposing, target repositioning

# Abstract

The rapid increase in data sources for computational drug discovery has not only highlighted the key role of ontology research in data integration, but also fostered the use of semantic knowledge graphs (KGs) for target repositioning. Previously, we developed a novel method to construct a KG for indication expansion studies, with the aim of finding and justifying alternative indications for a target gene of interest. In contrast to other KGs, ours combines full-text literature and biomedical database information to encode relationships between genes, diseases and tissues. Here, we assessed the suitability of our KG for explainable target-disease link prediction using a glass-box approach.
To evaluate the predictive power of our KG, we applied shortest path with tissue information- and embedding-based prediction methods to a graph constructed with information published before or during 2010. We also obtained random baselines by applying the shortest path predictive methods to KGs with randomly shuffled node labels. Then, we evaluated the accuracy of the top predictions using gene-disease links reported after 2010. In addition, we investigated the contribution of the KG’s tissue expression entity to the prediction performance.
Our experiments showed that shortest path-based methods significantly outperform the random baselines and embedding-based methods outperform the shortest path predictions. Importantly, removing the tissue expression entity from the KG severely impacts the quality of the predictions, especially those produced by the embedding approaches. Finally, since the interpretability of the predictions is crucial in indication expansion, we highlight the advantages of our glass-box model through the examination of example candidate target-disease predictions.

# Citation
TBA


