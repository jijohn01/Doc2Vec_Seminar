# Doc2Vec_Seminar

■ 문서 임베딩을 위한 고전 방식부터 Deep Learning을 활용한 방식까지를 실습

1. TF-IDF
- 문서에 등장하는 Term의 정보량을 통계적으로 계산한 방법.
- 다른 문서에서는 등장하지 않는 키워드가 특정 문서에서 많이 나타나면 높아짐

2. Word2Vec
- 단어의 Embedding을 근처 단어의 맥락으로 학습시키는 방법을 Word2Vec이라고 함.
- 문장에 등장하는 단어들의 Embedding Vector를 평균하는 방법
- gensim을 활용하여 작성, google의 사전학습 모델 사용, TF-IDF등을 통한 Normalize는 포함X

3. Doc2Vec
- Word2Vec과 유사한 방식이나 목적이 다름
- Doc2Vec은 문서 ID를 입력으로 하여 함께 학습 -> 결과적으로 문서 ID가 임베딩 되도록 한다.
