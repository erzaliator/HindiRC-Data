# HindiRC-Data
This repo contains data for HindiRC. Please cite [our paper](https://www.researchgate.net/publication/342424208_HindiRC_A_Dataset_for_Reading_Comprehension_in_Hindi) when using our dataset.

#### About HindiRC
HindiRC is the first Reading Comprehension dataset for Hindi. 

The dataset has been split into grades 2-5 according the educational reading proficiency.

The data has been sourced from educational websites [https://sandeepbarouli.com/](https://sandeepbarouli.com/) and [2classnotes](https://www.2classnotes.com/). Hence, it is completely natural and formal.


#### Xml Schema of the Dataset
* Reading Comprehension consists of a passage (given in the tag &lt;passage&gt;) and a set of questions (given in the tag &lt;q&gt;). 
* For HindiRC, the answers (&lt;a&gt;) belong to the passage.
* The index of these answers in the passage is given in &lt;l&gt;.
* If an answer spans multiple sentences, we consider the most important sentence only. However, the dataset does provide the index of these sentences is given in &lt;lg&gt;.
* Additionally, the dataset also provides a copy of the passage with all anaphors resolved. 


### References
Kaveri Anuranjana*, Vijjini Anvesh Rao*, Radhika Mamidi,
"[Hindi Question Generation Using Dependency Structures](https://www.researchgate.net/publication/342424208_HindiRC_A_Dataset_for_Reading_Comprehension_in_Hindi)", 20<sup>*th*</sup> International Conference on Computational Linguistics and Intelligent Text Processing, CICLing, 2019.

Please cite our paper above when using this dataset! :)