# Webiks-Hebrew-RAGbot-KolZchut-QA-Training-DataSet

* The file [`Webiks_Hebrew_RAGbot_KolZchut_QA_Training_DataSet_v0.1.csv`](https://drive.google.com/file/d/18WE5JARjzBkBD9kCd7cTxm1-7XX4-ylG/view?usp=drive_link) contains the training set used to train the [`Webiks_Hebrew_RAGbot_KolZchut_QA_Embedder`](https://drive.google.com/file/d/1eFAddJWBWDvoid-Gyn6ZT5jPwf-vNPI8/view?usp=drive_link) model.  Instructions on how to utilize this training set can be found in the following [repository](https://github.com/NNLP-IL/Webiks-Hebrew-RAGbot-Trainer). 
* The file comprises our training set of questions along with their corresponding answers. The answers consist of the page from the [Kol-Zchut website](https://www.kolzchut.org.il/) website relevant to each question, as well as the specific paragraph from the [paragraph corpus](https://github.com/NNLP-IL/Webiks-Hebrew-RAGbot-KolZchut-Paragraph-Corpus) that pertains to each question.

## Fields
* `doc_id`: The unique identifier of the website page.
* `question`: The question being asked (input to retrieval model).
* `paragraph`: The relevant paragraph in the Kol-Zchut page.
* `link`: The website page link.
  
## License
This data is published the under CC BY 4.0 license
More info: https://creativecommons.org/licenses/by/4.0/
