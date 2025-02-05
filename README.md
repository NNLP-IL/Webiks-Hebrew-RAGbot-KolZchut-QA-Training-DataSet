# Webiks-Hebrew-RAGbot-KolZchut-QA-Training-DataSet

* The file: [`Webiks_Hebrew_RAGbot_KolZchut_QA_Training_DataSet_v0.1.csv`](https://drive.google.com/file/d/18WE5JARjzBkBD9kCd7cTxm1-7XX4-ylG/view?usp=drive_link) is the training set used to train the [`Webiks_Hebrew_RAGbot_KolZchut_QA_Embedder`](https://drive.google.com/file/d/1eFAddJWBWDvoid-Gyn6ZT5jPwf-vNPI8/view?usp=drive_link) model. You can see how to use it in order to train this model in the following [`repository`](https://github.com/NNLP-IL/Webiks-Hebrew-RAGbot-Trainer). 
* The file contains our training set of questions and corresponding answers. The answers consist of the page relevant to the question from the [Kol-Zchut website](https://www.kolzchut.org.il/) as well as the paragraph relevant to each question taken from the [paragraph corpus](https://github.com/NNLP-IL/Webiks-Hebrew-RAGbot-KolZchut-Paragraph-Corpus).

## Fields
* `doc_id`: The unique identifier of the website page.
* `question`: The question being asked (input to retrieval model).
* `paragraph`: The relevant paragraph in the Kol-Zchut page.
* `link`: The website page link.
  
## License
This data is published the under CC BY 4.0 license
More info: https://creativecommons.org/licenses/by/4.0/
