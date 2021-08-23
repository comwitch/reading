2021.08.23
============
  
## 1.AGC2021 Paper Review : Deep Neural Solver
  
  어떤 수학문제가 있으면 그 답을 찾는 내용. number mapping으로 토큰형태로 바꿈 --> 어떤 방법을 써서 수식으로 확인함 --> 토큰으로 바꿨으니 인버스로 mapping을 시켜 자동으로 숫자로 바꾸어서 원하느 문제를 해결한다.
  
  what is somehow : seq2seq 한번 찾아보기. ground truth messy output 간의 loss를 찾아보기 : binary vector를 찾아봄
  
  Significant NAme Identification --> LSTM을 통해서 번역함 
  
  hybrid? 통계량을 이용해 J(p,q) 를 특정 thresholds를 넘어가면 templet을 인용 아니면 seq2seq를 사용함 jacard similiarity 
  F(w,d) =  tf - idf(w,d) 단어의 카운트를 통해서 토큰의 유사성을 많이 보일시에, 기존 템플릿을 사용하고 아닐시에, seq2seq를 사용하는 방향을가진다.

## 2. MathDQN
  
  https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16749/16111
  MathDQN 
  어떤수학문제를 푸는것. --> 문제를 파서를 이용해서 parser tree를 구축한 다음 , 그 학습을 classifier를 DQN을 이용해서 문제를 해결하는방식 (이부분은 좀더 읽어보고 분석해봐야함)
  
  MATH AI와의 관련성 ==> tree문제로 해결하기에는 문제가 잇는경우가 있다. (ex. 3에1을 더한수랑 7을 곱한수의 차를 구하여라) 이런경우에 subproblem을 이용해서 각각 MER을 사용해서 하는건 어떤지..
  
  
## 3. Translating a Math Word Problem to a Expression Tree.

  
  translating a MAth word ... 
  애초에 1,2,3 이 같은 저자
  
  seq2seq framework --> 1번째 논문과 비슷
  equation normalization
  dataset에 normaliztion을 해놓고 문제를해결.
  does the normalization utrilizes informations in language?
  
  GPT2 GPT3 
  
  multilinuality? 회의적 (영어로 한걸 중국어로 배우는게 제로샷으로 성능은 나오긴하지만, 회의적)
  MathQA
