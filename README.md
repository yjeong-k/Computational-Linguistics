# computational-linguistics
23-1 Computational Linguistics Class by prof. Lee

본 repository는 Word Sense Disambiguation(이하 WSD)을 수행하는 모델을 파인튜닝하는 프로젝트를 담고있다.  
WSD는 중의적 의미를 지닌 단어가 주어진 맥락에서 어떠한 의미로사용되었는지를 찾는 과제이다.

뼈대 모델로는 GlossBERT: BERT for Word Sense Disambiguation with Gloss Knowledge(Huang et al., EMNLP-IJCNLP 2019)의 GlossBERT를 사용하였고,
ambiguous target word의 품사 정보와 유의어 정보를 추가적으로 활용하여 파인튜닝 하였다.




### Citation  
```
@inproceedings{huang-etal-2019-glossbert,
    title = "{G}loss{BERT}: {BERT} for Word Sense Disambiguation with Gloss Knowledge",
    author = "Huang, Luyao  and
      Sun, Chi  and
      Qiu, Xipeng  and
      Huang, Xuanjing",
    booktitle = "Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP)",
    month = nov,
    year = "2019",
    address = "Hong Kong, China",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/D19-1355",
    doi = "10.18653/v1/D19-1355",
    pages = "3507--3512"
}
```
