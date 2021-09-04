# TEXT MINING for PRACTICE 

> 비정형 데이터는 전세계 전체 데이터의 70% 이상을 차지하고 있으며, 비정형 데이터에서 가치를 찾아내는 것이 데이터 분석의 성과를 좌우하고 있습니다. 본 자료는 비정형 데이터 중 텍스트 데이터에 집중하여, 실무에서 활용 가능한 다양한 텍스트 분석기법에 대해 소개합니다. 특히 한국어 텍스트 분석에 집중하여 한국어 처리의 장벽을 넘어 실무에서 무리 없이 텍스트 데이터 분석에 접근할 수 있도록 내용을 구성하였습니다. 이론은 텍스트 분석에 대한 기초개념부터 머신러닝을 활용한 텍스트 분석기법에 대한 개념에 대해 다루며, 실습에서는 이론수업에서 배운 내용을 Python 프로그래밍 언어를 활용하여 실제 적용해볼 수 있도록 코드를 제공합니다. 프로그래밍 언어에 익숙하지 않은 학생들을 위해 Python 기본문법에 대해 반복적으로 학습하며, 완성된 코드를 제공하고 핵심 포인트를 수정하는 방식으로 진행하여 비정형 데이터 분석에 전혀 경험이 없는 학생들도 이해할 수 있도록 내용을 구성하였습니다.

- 본 자료는 텍스트 마이닝을 활용한 연구 및 강의를 위한 목적으로 제작되었습니다.
- 본 자료를 강의 목적으로 활용하고자 하시는 경우 꼭 아래 메일주소로 연락주세요.
- 본 자료에 대한 허가되지 않은 배포를 금지합니다.
- 강의, 저작권, 출판, 특허, 공동저자에 관련해서는 문의 바랍니다.
- **Contact : ADMIN(admin@teanaps.com)**

---
## Notice!
> - 2021년 9월 부로 커리큘럼이 전면 수정되었습니다. 기존자료가 필요하신 분은 관리자 이메일로 요청 바랍니다. 
> - 본 자료는 2019년 부터 연세대학교 텍스트 마이닝(비정형 데이터 분석) 강의자료로 활용되고 있습니다.  

---
## Curriculum

> `WEEK 04`를 제외한 모든 실습은 `Google Colabotory`와 텍스트 마이닝을 위한 `TEANAPS` Python 패키지를 활용하여 구성하였습니다. `Google Colabotory`는 `Jupyter Notebook`을 `Google Drive`에 업로드하여 로컬 환경의 `Jupyter Notebook`과 동일하게 사용할 수 있도록 도와줍니다. `Google Colabotory`의 사용법은 강의자료의 [메뉴얼](https://github.com/fingeredman/text-mining-for-practice/blob/master/lecture-note/text-mining-for-practice-appendix.pdf) 파일을, `TEANAPS`의 사용법 및 설치방법은 [TEANAPS Repository](https://github.com/fingeredman/teanaps)의 [Install](https://github.com/fingeredman/teanaps) 파일을 참고 바랍니다. `WEEK 04` 실습자료는 가상의 웹브라우저를 사용하는 데이터 수집방법(`Selenium`)을 포함하고 있어 클라우드 환경에서의 실습이 어렵습니다. `WEEK 04` 실습은 예외적으로 로컬 환경의 `Jupyter Notebook`을 활용합니다.

#### WEEK 01. 텍스트 마이닝 개요
- 텍스트 마이닝 기본개념 및 유형
- Python 3.7 & Jupyter Notebook
- 실습  
  > _W01-1. 실습환경: Python 3.7 & Jupyter Notebook & Google Colaboratory [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_01/W01-1_text-mining-for-practice_colaboratory.ipynb)_  

#### WEEK 02. 텍스트 마이닝 사례연구
- 텍스트 마이닝 연구/실무 적용사례
- 텍스트 데이터를 위한 Python 프로그래밍
- 실습  
  > _W02-1. 텍스트 데이터를 다루기 위한 Python: 기본문법 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_02/W02-1_text-mining-for-practice_python-basic.ipynb)_  
  > _W02-2. 텍스트 데이터를 다루기 위한 Python: 자료구조 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_02/W02-2_text-mining-for-practice_python-data-structure.ipynb)_  
  > _W02-3. 텍스트 데이터를 다루기 위한 Python: 반복문과 조건문 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_02/W02-3_text-mining-for-practice_python-conditional%26loop.ipynb)_  
  > _W02-4. 텍스트 데이터를 다루기 위한 Python: 함수와 파일입출력 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_02/W02-4_text-mining-for-practice_python-function%26file.ipynb)_  
  > _W02-5. 텍스트 데이터를 다루기 위한 Python: 패턴인식과 정규식 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_02/W02-5_text-mining-for-practice_python-regex.ipynb)_  

#### WEEK 03. 텍스트 데이터 수집 1
- 텍스트 데이터 유형 및 수집방법
- 웹 스크래핑 기초
- 실습  
  > _W03-1. 데이터 크롤링 원리 이해하기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_03/W03-1_text-mining-for-practice_python-crawling-intro.ipynb)_  
  > _W03-2. 정적페이지 수집하기: 실시간검색어, 영화댓글 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_03/W03-2_text-mining-for-practice_python-crawling-practice-1.ipynb)_  
  
#### WEEK 04. 텍스트 데이터 수집 2
- 웹 스크래핑 자동화 및 실전 활용법
- 텍스트 데이터 핸들링
- 실습  
  > _W04-1. 동적페이지 수집하기: 네이버 카페 게시글 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_04/W04-1_text-mining-for-practice_python-crawling-practice-2.ipynb)_  
  > _W04-2. 동적페이지 수집하기: 인스타그램 해시태그 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_04/W04-2_text-mining-for-practice_python-crawling-practice-3.ipynb)_  
  
#### WEEK 05. 텍스트 데이터 전처리
- 형태소분석과 개체명인식
- KoNLPy & NLTK & TEANAPS
- 실습  
  > _W05-1. 한국어 텍스트 데이터 전처리하기: KoNLPy & TEANAPS [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_05/W05-1_text-mining-for-practice_python-korean-nlp.ipynb)_  
  > _W05-2. 영어 텍스트 데이터 전처리하기: NLTK & TEANAPS [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_05/W05-2_text-mining-for-practice_python-english-nlp.ipynb)_  
  > _W05-3. 개체명인식 수행하기: TEANAPS [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_05/W05-3_text-mining-for-practice_python-ner.ipynb)_  

#### WEEK 06. 단어의 가중치를 표현하는 방법
- 단어빈도와 TF-IDF
- 단어 네트워크와 중심성
- 실습  
  > _W06-1. 단어빈도와 TF-IDF 계산하기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_06/W06-1_text-mining-for-practice_python-tf-idf.ipynb)_  
  > _W06-2. 동시출현빈도 계산과 단어 네트워크 생성하기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_06/W06-2_text-mining-for-practice_python-co-word.ipynb)_  

#### WEEK 07. 문서를 벡터로 표현하는 방법
- 단어 단위 임베딩
- 문장/문서 단위 임베딩
- 실습  
  > _W07-1. TEANAPS를 활용해 데이터 시각화하기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_07/W07-1_text-mining-for-practice_python-visualization.ipynb)_  
  > _W07-2. 단어 임베딩 이해하기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_07/W07-2_text-mining-for-practice_python-w2v.ipynb) [(Model Download)](https://drive.google.com/file/d/1qBMDr-WSMt-OG1IO2CXeqVqodKGYIxr2/view?usp=sharing)_  

#### WEEK 08. 분류
- 머신러닝을 활용한 텍스트 데이터 분류
- 텍스트 감성분석
- 실습  
  > _W08-1. 문장의 의도 분류하기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_08/W08-1_text-mining-for-practice_text-classification.ipynb)_  
  > _W08-2. 감성분석 활용하기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_08/W08-2_text-mining-for-practice_sentiment-analysis.ipynb)_  

#### WEEK 09. 군집화
- 텍스트 데이터 군집화
- 토픽모델링
- 실습  
  > _W09-1. K-평균 군집화와 LDA 토픽모델링을 활용해 문서 군집화하기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_09/W09-1_text-mining-for-practice_text-clustering.ipynb)_  

#### WEEK 10. 요약
- 문서요약: 추출요약과 생성요약
- 핵심 키워드 추출
- 실습  
  > _W10-1. 뉴스기사 요약하기: 추출요약 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_10/W10-1_text-mining-for-practice_text-summerization.ipynb)_  

#### WEEK 11. Predictive Analysis
- 예측 모델링을 위한 자질추출
- 텍스트 분류문제를 예측에 활용하는 방법
- 실습  
  > _W11-1. 개봉직후 영화리뷰를 활용해 최종 관객수 예측하기 [(Colab)](https://colab.research.google.com/github/fingeredman/text-mining-for-practice/blob/master/practice-note/week_11/W11-1_text-mining-for-practice_python-movie-viewer-prediction.ipynb)_  

#### WEEK 12. Application
- Question & Answering
- Chat-bot: 질의응답부터 일상대화 까지
- 카카오 i 오픈빌더 
- 실습  
  > _W12-1. 카카오 i 오픈빌더를 활용해 Q/A 챗봇 구축하기_  

---
## References
> 본 강의자료는 아래 문헌들을 참고해 구성되었습니다.
- A Byte of Python [(Link)](https://python.swaroopch.com/)
- 패스트캠퍼스 <텍스트 분석 유치원 1기~5기> 실습자료 [(Link)](https://www.fastcampus.co.kr/data_class_textmining/)
- 텍스트 마이닝(Text Mining), 송민 지음, 청람출판사, 2017
- 파이썬을 이용한 머신러닝, 딥러닝 실전 개발 입문, 쿠지라 히코우즈쿠에, 위키북스, 2017
- Natural Language Processing with PyTorch, 김기현 [(Link)](https://kh-kim.gitbook.io/natural-language-processing-with-pytorch/)

---
## Update History
> 2020.12.05. `WEEK 07~12` 강의자료 및 실습자료 업데이트    
> 2020.11.08. `WEEK 01~06` 강의자료 및 실습자료 업데이트    
> 2020.04.12. 목차 구성 수정  
> 2019.11.23. `TEANAPS v0.4.1` 업데이트 반영  
> 2019.09.29. 목차 구성 수정, `TEANAPS v0.3.1` 업데이트 반영  
> 2019.08.26. 실습자료 `Colabotory` 링크 추가  
> 2019.07.12. 목차 구성 수정, `WEEK 01~12` 강의자료, `WEEK 01~08` 실습자료 업데이트  
> 2019.06.22. 목차 구성 수정, `WEEK 01~03` 실습자료 업데이트  
> 2019.06.17. 목차 구성 수정    
> 2019.06.16. 목차 구성 수정, `WEEK 01~05` 실습자료 업로드    
> 2019.06.14. 목차 구성 수정, `WEEK 01` 실습자료 업로드    
> 2019.06.07. 목차 구성 초안 입력  

<br><br>
---
<center>ⓒ 2021. TEANAPS all rights reserved.</center>
