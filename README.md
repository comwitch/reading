# reading

this is something what i think in generally studying

WGAN 설명과 관련.
-----------------
자세한 설명과 논문들을 참고하기 위해서는 다음 파일들을 attach 하였기 때문에 참고하면 될 거 같습니다.  
[OHWGAN_1.PDF](https://github.com/comwitch/reading/files/7014041/OHWGAN_1.PDF) ==> 고려대학교 이과대학 오승상 교수님의 wgan 발표자료  
[1701.07875.pdf](https://github.com/comwitch/reading/files/7014045/1701.07875.pdf) ==> wgan paper (Martin Arjovsky1, Soumith Chintala, and L´eon Bottou)  

## then, what is WGAN? 

wasserstein GAN ?  
  
  
Wasserstein distance를 이용해서 만듦.  
regular gan의 경우 convergence를 보장할 수가 없다. 그리고 discriminator관련해서 gradient가 구하기 힘든데, wasserstein의 function(WGAN critic)을 이용하면 gradient를 smoother하게 해줍니다.  
  
metric = 일반적으로 생각하는 수학적인 개념  
divergence = metric 성질의 1번만 만족하는 함수  
  
wasserstein GAN는 가능한 분포에서 분포를 옮기는데 필요한 cost중 가장 적을값(infimum)을 Wasserstein GAN이라고 한다.(delta 는 y축의두께)  
  
  
  # 8월 27일 세미나 (오승상교수님)
  참고자료 : [Oh DQN.pdf](https://github.com/comwitch/reading/files/7064128/Oh.DQN.pdf)
  참고자료 : [Oh Q-learning.pdf](https://github.com/comwitch/reading/files/7064130/Oh.Q-learning.pdf)

## DQN, Double Q-learning, Duel Q-learning
 
