# The Medical Misspelling Correction Corpus

The medical misspelling correction (MMC) corpus is a corpus of 99 spelling mistakes found in 1000 random posts of the GIST International Support Facebook forum for Gastro-Intestinal Stromal Tumor (GIST) patients. Their corrections were determined first individually by AR Dirkson and a GIST patient and forum user and then compared and agreed upon. If the correction could not be agreed upon, a third annotator resolved the matter. 

The medical misspelling detection (MMD) corpus is based on the same 1000 posts. We share the training data for training our spelling mistake detector. This is a combination of all mistakes found in this training subset and a 10-fold of correct words found in this set with the same word lenght distribution. These words were randomly selected. This approach was chosen in order to balance the data for training while still mimicing the strong imbalance present in the data. The training set does not contain the full sentences but for each word, it does contain the details of the SentenceBit (i.e. the two neighbouring words) and whether it occured at the start (BoS = True) or end (EoS= True) of the sentence.

Due to anonymization of the data set, 24 instances were removed from the training set (only non-errors). For one error, a personal name was replaced with -NAME-. For privacy reasons, the test set is only available upon request from AR Dirkson at a.r.dirkson@liacs.leidenuniv.nl

For more detail please refer to: 

Dirkson AR, Verberne S, Sarker A and Kraaij W (2019). Data-driven Lexical Normalization for Medical Social Media. Multimodal Technologies and Interaction, 3(3), 60.

https://www.mdpi.com/2414-4088/3/3/60


# The PsyTAR Spelling Corpus

After the publication of this paper, we developed a second spelling corpus for the community: The PsyTAR Spelling Corpus. It consists of 79 mistakes which were collected from the publicly available PsyTAR corpus. These mistakes were either spelling mistakes made by annotators (i.e. the extracted text contained a mistake the original text did not) or made by the forum users (i.e. in the extracted text the spelling mistake was corrected).

The original corpus can be found at: https://sites.google.com/view/pharmacovigilanceinpsychiatry/home
The PsyTAR corpus is a collection of posts from Askapatient.com in which patients recount their experiences with drugs related to psychiatric conditions. It was developed by M. Zolnoori and described in her paper: 

The PsyTAR dataset: From patients generated narratives to a corpus of adverse drug events and effectiveness of psychiatric medications
https://www.sciencedirect.com/science/article/pii/S2352340919301891



