# Portfolio
이광용 포트폴리오

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

=========================================================================

# 주요 프로젝트

<h2><a href = "https://github.com/LeeGwang95/AIRoomMusic"> LSTM을 활용한 AI 작곡 플랫폼 </a></h2>

- 2019년 캡스톤2 수업 프로젝트 및 교내 공과대학 경진대회 프로젝트. 

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



