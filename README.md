# learning
딥러닝자연어처리

# 250416
## 워드 임베드 개념 학습 
 워드 임베드란 단어를 문백 기반으로 저차원의 밀집 벡터로 표현 
 단어간 의미적 유사성을 벡터화하는 작업 
Word2Vec
 - 단어를 저차원의 벡터로 표현할 때 주변에 같이 사용된 다른 단어의 정보를 사용하는 방식
 - 단어를 이웃 단어 정보를 사용해 벡터로 표현 → 의미적 유사도보다는 문맥적 의미가 유사한 단어를 찾아낼 때 유용
CBOW(Continusou Bag of Words):
- 주변에 있는 단어들을 입력으로 중간에 있는 단어들을 예측
Skip-gram
- 중간에 있는 단어들을 입력으로 주변 단어들울 예측하는 방법
CBOW(Continusou Bag of Words),Skip-gram을 실습 공부!
  
