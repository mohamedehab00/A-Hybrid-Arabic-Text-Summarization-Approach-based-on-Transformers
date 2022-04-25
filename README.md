# A-Hybrid-Arabic-Text-Summarization-Approach-based-on-Transformers
In this paper, we proposed a sequential  hybrid model based on a transformer to summarize Arabic  articles. We used two approaches of summarization to  make our model. The First is the extractive approach which  depends on the most important sentences from the articles to be the summary, so we used Deep Learning techniques specifically transformers such as AraBert to make our summary, The  second is abstractive, and this approach is similar to human  summarization, which means that it can use some  words which have the same meaning but different from  the original text. We apply this kind of summary using  MT5 Arabic pre-trained transformer model. We sequentially  applied these two summarization approaches to building our A3SUT  hybrid model. The output of the extractive module is fed into  the abstractive module. We enhanced the summary’s quality to  be closer to the human summary by applying this approach.  We tested our model on the ESAC dataset and evaluated the  extractive summary using the Rouge score technique; we got  a precision of 0.5348 and a recall of 0.5515, and an f1 score of  0.4932 and the evaluation of the abstractive model is evaluated by  user satisfaction. We add some features to our summary to make  it more understandable by applying the metadata  generation task” data about data” and classification. By applying  metadata generation, we add facilities to our  summary, identification, and summary organization. Metadata provides essential contextual details, as not all  summaries are self-describing. Also, classify the original text to  determine the summary topic before reading. We acquire 97.5%  accuracy by using Support Vector Machine (SVM) and trained  it using NADA corpus.
