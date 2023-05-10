# LIKELION AIS 8th FINAL-PROJECT
![슬라이드1](https://user-images.githubusercontent.com/124337933/237030435-a9bb8d38-5790-4849-8aab-0b361de1a158.JPG)
# 결과물
![프레젠테이션1](https://github.com/hapvpy/Recipe-Recommendation-Chatbot/assets/124337933/4a1f671d-34c4-4c6e-addd-1794b9b76fa6)

<br>

# 팀 소개 <br>
### 3️⃣ 조이름은 최강록으로 하겠습니다. 근데 이제 바질을 곁들인 <br><br>

<b> 🍕 주제 </b>: 냉장고 안 재료로 만들 수 있는 <b>레시피를 추천해주는 챗봇</b> <br>
<b> 🍔 활용 데이터 </b>: '🍽️[우리의 식탁](https://wtable.co.kr/recipes)' 레시피 데이터 크롤링 <br>
<b> 🍟 프로젝트 기간 </b>: 2023.04.26 ~ 2023.05.09 <br>

<br><br>

🦁 <b> 팀 최강록. 팀워크를 곁들이다.</b>
|![image](https://user-images.githubusercontent.com/124337933/237033354-ae3e2661-0d0b-487d-98d3-4f8b0bc6fc42.png)|![image](https://user-images.githubusercontent.com/124337933/237033386-393492bf-bc05-468e-b160-0dbf63cde6c9.png)|![image](https://user-images.githubusercontent.com/124337933/237033411-cd779a5f-d45b-41c1-8ef1-49e4453539c9.png)|![image](https://user-images.githubusercontent.com/124337933/237033439-66e815de-35e4-4834-8493-387309a5e2d0.png)|![image](https://user-images.githubusercontent.com/124337933/237033456-12825d94-c382-4bec-823b-c44898fcaf1e.png)|![image](https://user-images.githubusercontent.com/124337933/237033473-360923ae-c41a-4b7a-948e-b2a4483a05d5.png)|
|:---:|:---:|:---:|:---:|:---:|:---:|
| ✨ 팀장 | 👨🏻‍💻 팀원 | 👨🏻‍💻 팀원 | 🎨 PPT | 👨🏻‍💻 팀원 | 🎙️ 발표 |
|  최민규 |  강다솔 |  김강섭 |  김연선 |  김지원 |  김현아 |
|추천시스템&챗봇|streamlit|추천시스템&챗봇|추천시스템&챗봇|추천시스템&챗봇|필터링&streamlit|

<br><br>

🦁 <b>주제 선정의 배경</b>
#### 1️⃣ 경제적인 측면
``````
💡 경기불황 - 배달료 및 외식비 상승

   코로나19로 인한 팬데믹이 서서히 종식되고 외부활동이 자유로워졌으나 
   경기불황으로 인한 외식비 상승과 배달비 인상으로 소비자의 부담은 커지고 있음
``````
|![image](https://user-images.githubusercontent.com/124337933/237038915-0b19d6e9-e0a1-4658-9092-496550049e6f.png)|![image](https://user-images.githubusercontent.com/124337933/237039719-e943689f-96ad-44b7-ab48-a65e961ad7f2.png)|
|---|---|
|<font color= 'gray'> 자료: 한국소비자원 가격정보 종합포털 ‘참가격’ <br>(2022년 12월 서울시 기준, 전년 동월 대비, %) </font>| 자료: 모바일 인덱스, 오픈서베이 |

#### 2️⃣ 생활 편의의 측면
``````
💡 집밥을 직접 해먹지 않는 이유❓  

   "귀찮아서"  "요리할 시간 부족"  "요리가 어려워서"
``````
<br><br>

🦁 <b>프로젝트 진행 과정</b> <br><br>
![image](https://user-images.githubusercontent.com/124337933/237034927-aa1738ce-18f1-4809-b0cd-f9ee50663fe7.png)


<hr>
<br>

## 프로젝트 소개
![슬라이드8](https://user-images.githubusercontent.com/124337933/237046550-7394be62-f969-4aff-9791-aa4139c75810.JPG)
``````
🤔 "남은 식재료들을 어떻게 잘 활용할 수 있을까?"

   라는 고민으로 프로젝트가 시작되었고 집밥이 귀찮은 사람들, 요리가 어려운 사람들, 시간이 부족한 사람들을 위해
   적절한 요리 레시피를 추천해주는 ChatBot을 만들어 사용자에게 "효율성"과 "편리함"을 제공하고자 하였습니다.
``````

<br><br>

## 데이터 수집 및 전처리
![슬라이드10](https://user-images.githubusercontent.com/124337933/237047249-613c9df1-c3ed-4516-950e-001d5e388696.JPG)
![슬라이드11](https://user-images.githubusercontent.com/124337933/237047273-1705306e-1bee-4c3d-b213-8c3785555064.JPG)
``````
👩🏻‍💻 초기목적은 여러 사이트에서 데이터를 크롤링하여 규모를 키우고, 데이터 형식을 지정하여 진행하고 싶었으나
   일정 형식으로 통일하는 과정에서의 시간 소요가 클 것으로 판단되어 하나의 사이트를 선정하기로 하였습니다.
   가장 일관성 있는 데이터를 가진 '우리의 식탁'이 선정되었고, 빨간 박스에 해당되는 데이터들을 크롤링해왔습니다.
``````
<br><br>

## EDA
![슬라이드12](https://user-images.githubusercontent.com/124337933/237047364-710c29eb-5d74-4a37-8997-0bf66362aa7b.JPG)
![슬라이드13](https://user-images.githubusercontent.com/124337933/237047373-8c5e8ae6-6308-44bc-a4ea-d224cf979392.JPG)
![슬라이드14](https://user-images.githubusercontent.com/124337933/237047387-7bf2d7db-5081-4d20-9cb8-904ec0ebfb52.JPG)
![슬라이드15](https://user-images.githubusercontent.com/124337933/237047426-413abde5-1f38-44fb-976c-20a33ffbfcec.JPG)
``````
💡 프로젝트의 핵심! ChatBot과 추천기능 플로우 도식화.  ➡ 이를 기능 추가와 수정 등을 판단하는 근거로 삼음.

   1. 사용자 쿼리의 의도를 이해하고 이를 내부 모델로 전달하는 ChatGPT
   2. 전달된 의도 값에 따라 다른 출력을 내는 사전 학습된 내부 SentenceTransformers 모델
``````
<br><br>

## Filtering
![슬라이드16](https://user-images.githubusercontent.com/124337933/237047547-6df942e6-78f6-4bdb-8c83-b8470982b4c2.JPG)
``````
👩🏻‍💻 초기 계획 : 즉각적인 상호작용을 통해 사용자가 쿼리를 입력하면 모델이 스스로 '제거할 재료', '포함할 재료', 
            '알레르기 식품' 등을 분류하여 추천해주는 ChatBot 형태 구현
            ➡️ 파인튜닝과 임베딩 등을 추가적으로 진행해야 했음
            
💡 변경내용 : 사용자도 보다 간단하게 사용할 수 있는 "Streamlit Button" 위젯을 만들어 일부 내용 사전에 필터링하기!
             - 알레르기 식품, 요리 종류, 난이도, 소요시간 등에 대한 정보를 사용자는 사전에 전달할 수 있음.
             - 이후에 ChatBot과 대화하며 추천되는 레시피는 필터링된 데이터를 기반으로 추천됨.
``````
<br><br>

## 추천시스템 구현
![슬라이드17](https://user-images.githubusercontent.com/124337933/237047797-2d09ff92-7f3a-4f13-862f-fd5c2c8e7eff.JPG)
``````
🤔❓ 추천시스템의 베이스 모델 설명

   1. 사용자가 재료나 테마가 포함된 문장을 입력
   2. 사전학습된 모델로 전이학습을 진행한 SentenceTransformer가 사용자 입력 문장을 벡터화
   3. 이를 기존에 작업해둔 임베딩 벡터와 코사인 유사도를 비교
   4. 가장 유사한 상위 n개의 레시피를 "중복없이" 추천
``````

<br><br>

## 챗봇 구현
![슬라이드18](https://user-images.githubusercontent.com/124337933/237047854-0e012518-3cc3-473f-9fbd-62cffafe8c25.JPG)
``````
ChatBot 형태 구현을 위한 "OpenAI API" 연동

🧠 OpenAI 모델의 역할 : 
   유저가 전달한 문장의 "의도"를 파악하고 이를 추천 베이스 모델에 전달하여,
   의도에 따라 다른 함수를 작동시켜서 추천, 설명, 방법 등이 출력되도록 함.
   ex) 문장에 "추천"이 포함되면 "추천" 함수를 사용하여 유사도가 높은 레시피를 출력합니다.
``````
<br><br>

## Streamlit으로 대시보드 구현
![슬라이드19](https://user-images.githubusercontent.com/124337933/237047971-f1398763-e1c5-496e-847f-d53bb893cb51.JPG)
``````
1️⃣ 사용자가 버튼 위젯을 사용하여 사전 정보를 입력하고 데이터를 필터링합니다.
2️⃣ 채팅창 페이지에서 사용자는 원하는 레시피를 ChatBot에게 요청합니다.
3️⃣ 사용자는 ChatBot이 추천한 레시피를 보며 부족한 재료가 있을 경우 링크를 통해 쉽게 구매할 수 있습니다.
``````
<br><br>

## 최종결과물 및 회고
![슬라이드20](https://user-images.githubusercontent.com/124337933/237048071-9eef1934-ac87-452e-9892-e458ebad014f.JPG)
![슬라이드21](https://user-images.githubusercontent.com/124337933/237048086-15f0a755-a3c2-44d0-aeb9-0cab30856ba0.JPG)
![슬라이드22](https://user-images.githubusercontent.com/124337933/237048099-afe2d5b7-3b19-4bf9-8968-e97fe44b432e.JPG)
<br><br>

![슬라이드24](https://user-images.githubusercontent.com/124337933/237048126-8ac3c7e1-94d4-4da7-9bfd-1ef2fba01921.JPG)

