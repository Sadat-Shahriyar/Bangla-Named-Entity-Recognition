## NLP Hackathon on Named Entity Recognition
* `banglabert` token-classification submodule was used for the fine tuning task
* `SVM classifier` was used as the hand-crafted ML model

### Description
During the Bangladesh National NLP Hackathon, we developed a project to detect named entities in Bangla sentences using BanglaBERT, Support Vector Machine (SVM), and Conditional Random Fields (CRF). The dataset was augmented with techniques like word swapping, token replacement by label, synonym replacement, random insertion/deletion, stemming, lemmatization, and stopword removal. CRF was enhanced with features such as context words, word suffixes, named entity information, and digit features. The models achieved a macro average F1 score of 0.7938 with BanglaBERT, 0.68 with SVM, and 0.34 with CRF.
