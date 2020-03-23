# Portfolio

이광용 포트폴리오

<img width="1382" alt="스크린샷 2020-03-23 오후 7 20 27" src="https://user-images.githubusercontent.com/62536330/77306697-61d3f400-6d3b-11ea-8e4d-059aaafb258a.png">

<h3>개인 정보</h3>

- Github : https://github.com/LeeGwang95/

- Gmail : cf012712@gmail.com

- NaverMail : cf0127@naver.com

- Youtube(Project) : https://www.youtube.com/channel/UCjyMEmXvF5DJeXRpdIy4zYA

<h3>보유 기술</h3>

- C, Python, Java

- Tensorflow, Spring, Flask, ELK

- Git

<h3>경력 및 자격증</h3>

- Wezone (2019) in Korea

  It 개발팀 인턴
  
  프레임워크 교육 및 관련 기자재 및 고객명단 데이터베이스화 작업
  
- Web Presence in China (2018)  in Vancouver

  It department 인턴
  
  머신러닝, 프레임워크 교육 및 Input&Ouput Test, 데이터베이스화 작업
  
  mini WPIC 프로젝트
  
- 교내 스터디 동아리 '#include'

- OCP(11g), Sqld, 정보처리기사
  
<h3>학력</h3>

- 동탄고등학교

- 명지대학교 컴퓨터공학과 졸업

  
<h3>교외 교육</h3>

GBC(Gastown Business College)
- 2018.05 ~ 2018.09
- Business, English Culture, Economy etc  

<h3>수상</h3>

- 교내 공과대학 캡스톤 경진대회 (금상)
- 교내 스터디 동아리 경진대회 (금상)

=========================================================================

# 주요 프로젝트

<h2><a href = "https://github.com/LeeGwang95/AIRoomMusic"> LSTM을 활용한 AI 작곡 플랫폼 </a></h2>

- AI ROOM MUSIC

- 2019년 캡스톤 수업 프로젝트 및 교내 공과대학 경진대회 프로젝트. 

<h3> Why? </h3>

성장하는 음악산업과 4차산업혁명에 있어서 해외에서는 AI작곡 플랫폼이 등장하기 시작 하지만 한국에는 아직 시도가 없어 최대한 쉬운 방식으로 AI작곡 플랫폼 제안을 통하여 영화, 게임, 1인 미디어 산업에 있어서 필요한 음악을 제공.

<h3> How? </h3>

- 수집 : Kaggle, git 등 다양한 매체에서 MIDI파일 저장(classic이 많았음 저작권)

- 저장 : 프로젝트 파일안에 midi라는 파일을 두고 이를 읽어와서 파싱하는  과정을 거침 그과정속에서 노트와 코드로서 저장을함. 데이터를 이는 뮤직21라이브러리의 예제들을         이용 

- 분석 : LSTM 에 드랍아웃(오버피팅방법),덴스(뉴런과 결합하여 입출력 담당),액티베이션(윤활제)와 같은 좀더 유연하게 만드는 레이어들을 이용하여 LSTM을 구축 케라스 를         선택했고 그 이유는 초보자 수준에서도 단순히 레이어를 쌓는 방식을 이용. (인풋,가중치,연산,활성화함수)

- 시각화 : HTML환경에서 부투스트랩을 이용하여 빠르고 간결한 템플릿을 구성 + Youtube APi 사용 Get post메소드 이용 인자값을 던져주는 방식 

<h3> Trouble Shooting </h3>

- 문제 : 많은 시간을 요구하는 학습시간(100곡 당 약 28시간)

-> 해결 : Tensorflow GPU를 통하여 3분의 1정도 시간 절약 및 학습 데이터 파일을 수시로 자동 저장 하도록 설정

- 문제 : RNN 방식의 한계

-> 해결 : 많은 데이터를 취급하기에 기존의 RNN 방식이 한계가 있어서 LSTM 방식 적용

- 문제 : Exploding 현상

-> 해결 : 일정량의 학습량 및 하이퍼 파라미터를 설정 ( 비슷한 LSTM을 주제로 하는 논문을 참조) 

- 문제 : 다양한 미디 채널 확보 (다채로운 음악) 

->  해결 : 악기마다 학습을 다르게 하여 이를 합치는 방식으로 해결 (ex. 베이스 별 학습, 기타 별 학습, 피아노 학습)

- 문제 : 학습 음악 저작권 관련

-> 해결 : 대부분의 80년 이상된 클래식 곡으로 학습 및 무료 저작권 음악 사용

<h3> Image </h3>

<img width="1161" alt="스크린샷 2020-03-23 오후 7 13 43" src="https://user-images.githubusercontent.com/62536330/77306117-85e30580-6d3a-11ea-9a41-f3e11c9c76bf.png">


---------------------------------------------------------------------------

<h2><a href = "https://github.com/LeeGwang95/HowMuchFish"> 선형회귀를 통한 수산물 가격 예측 플랫폼 </a></h2>

- How Much Fish ? 

- 2019년 팀프로젝트2 수업 프로젝트 


<h3> Why? </h3>

우리나라는 세계수산물 소비 1위국가인데 농산물에 비하여 수산물은 뚜렷한 4차산업혁명과의 결합이 없었습니다. 이에 대한 관심은 적었고 폭등하는 수산물 가격에 정부의 많은 예산이 소비되는 것을 확인하였습니다. 이에 하나의 대시보드로서 가격을 예측하여 대비하고 안정화 한다면 새로운 플랫폼이 될 것이라 생각하였습니다.

<h3> How? </h3>

데이터 수집에 있어서는 농수산물유통정보 기상청 합쳐서 데이터를 만듬 csv 파일로만들고 이를 텐서플로우에서 넘파이를 사용하여 플레이스 홀더를 각각 설정. 선형회귀를 사용했는데 경사하강법으로 이를 예측 하였습니다.

-hypothesis = tf.matmul(X,W) +b

-Cost = tf.reduce_mean(tf.square(hypothesis - Y)

-평균제곱 오차법 optimizer = tf.train.GradientDescentOptimizer(learning_rate=0.000005)

-선형 회귀란? 독립 변수 x를 사용해 종속 변수 y의 움직임을  예측 하는 방식

<h3> 아쉬운 점 및 느낀점 </h3>

- 많은 양의 데이터를 확보 할 수 없었던 점

-> 기상청 및 농수산 유통센터에서 제공하는 데이터는 대부분 2~3년 된 데이터일 뿐 만 아니라 유실된 경우가 많았음.

- 간단한 선형회귀를 사용한 점

-> 첫 머신러닝 프로젝트였기에 간단한 경사하강법을 이용한 선형회귀를 사용 ( 이후에 AI 작곡 프로젝트에는 다중 선형회귀 및 LSTM 사용)

- 더 높은 loss에 대하여

-> 로스는 12프로로 88프로이상의 정학도를 보였고 6월 당시 일주일 데이터 +-50원의 오차로 모두 맞혔지만 몇 십원 단위도 수산물 시장에는 중요하므로 더 좋은 모델을 개발    했어야 했다는 점

- 많은 종류의 품목을 선택 못한 점.

-> 애초에 계획은 수산물 1품종, 해조류 1품종, 어패류 1품종을 할려 했지만 수산물의 몇 품종 외에는 데이터를 구할 수 없었음.

- 느낀점

-> 처음으로 기획 및 개발을 주도한 프로젝트로서 부족하지만 프론트 백앤드 모두를 경험할 수 있었습니다. 이를 계기로 프로젝트를 기획 및 개발 할 수 있는 능력을 공부 중    입니다. 

<h3> Image </h3>

<img width="880" alt="스크린샷 2020-03-23 오후 7 15 41" src="https://user-images.githubusercontent.com/62536330/77306224-b4f97700-6d3a-11ea-88d8-b78ddaef6709.png">


