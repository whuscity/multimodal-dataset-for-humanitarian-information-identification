# Multimodal dataset for humanitarian information identification
This dataset contains 4,383 crisis-related Twitter text-image pairs annotated for the humanitarian information identification task. It was constructed based on two existing data sources, namely [CrisisLexT26](http://crisislex.org/data-collections.html#CrisisLexT26) and [Twitter Datasets from Crises](https://crisisnlp.qcri.org/lrec2016/lrec2016.html). 
## Annotation details
Given a text-image pair, the annotators need to determine whether it contains the following categories of humanitarian information.
+ Caution and advice
+ Needs and offers
+ Other
+ Affected individuals
+ Infrastructure and utility damage
+ Response

Each positive sample (i.e., the text-image pair that contains humanitarian information) can be assigned one or more labels. If a text-image pair does not contain any humanitarian information, it is labeled as *Not humanitarian*.  
## Data format
This resource contains the following files or folders.
+ *annotation.csv*：It contains 4 fields, namely tweet_id, tweet_text, image_path (relative path), label (Multiple labels of a sample are separated by ";").
+ *image*：This folder contains all the images in our dataset.
## Citation request
Please cite the following paper if you use this resource in your research.
