# SpellingCorpus

The medical misspelling correction (MMC) corpus is a corpus of 99 spelling mistakes found in 1000 random posts of the GIST International Support Facebook forum for Gastro-Intestinal Stromal Tumor (GIST) patients. Their corrections were determined first individually by AR Dirkson and a GIST patient and forum user and then compared and agreed upon. If the correction could not be agreed upon, a third annotator resolved the matter. 

The medical misspelling detection (MMD) corpus is based on the same 1000 posts. We share the training data for training our spelling mistake detector. This is a combination of all mistakes found in this training subset and a 10-fold of correct words found in this set with the same word lenght distribution. These words were randomly selected. This approach was chosen in order to balance the data for training while still mimicing the strong imbalance present in the data. The training set does not contain the full sentences but for each word, it does contain the details of the SentenceBit (i.e. the two neighbouring words) and whether it occured at the start (BoS = True) or end (EoS= True) of the sentence.

Due to anonymization of the data set, 24 instances were removed from the training set (only non-errors). For one error, a personal name was replaced with -NAME-. For privacy reasons, the test set is only available upon request from AR Dirkson at a.r.dirkson@liacs.leidenuniv.nl

For more detail please refer to: 

Dirkson AR, Verberne S, Sarker A and Kraaij W (Under submission). Data-driven Lexical Normalization for Medical Social Media. Multimodal Technologies and Interaction [Text Mining in Complex Domains]. 


