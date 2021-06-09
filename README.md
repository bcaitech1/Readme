부스트캠프 AI Tech 1기의 GitHub에 오신 것을 환영합니다!  
부스트캠프는 좋은 경험과 습관을 가진 지속 가능한 개발자를 목표로 서로에게 배우고 문제를 해결하며 성장합니다.  
이 곳에서는 부스트캠프 AI Tech 에 참여한 학생(캠퍼)들의 프로젝트 결과를 확인할 수 있습니다.

----------------------


## 부스트캠프 AI Tech 1기 소개

부스트캠프 AI Tech 에서는 AI 로 비즈니스 가치를 창출하는 AI 엔지니어를 목표로 지난 5개월 동안 인공지능과 딥러닝에 대한 기초와 AI 모델을 구현하고 개선하는 일련의 실무 과정을 경험합니다.

- 기간 : 2021년 1월 18일 ~ 21년 6월 22일
- 학습 시간 : 800++ 시간 (100일간 풀타임 10:00 ~19:00)
- U Stage(이론) : 2개월 간, AI 모델 개발과 서비스 적용에 필요한 기초 지식을 학습하고 도메인 별로 널리 쓰이는 backbone 모델을 다룹니다.
- P Stage(프로젝트) : P Stage 1부터 4까지 총 9개의 주제(문제 상황)와 데이터셋이 제공되며, 각 Stage에서는 대회 형태로 본인이 선택한 주제의 AI 모델을 개발합니다.

----------------------
  
## 부스트캠프 AI Tech P Stage  프로젝트 소개 

### P Stage1 : 이미지 분류 (Image Classification)
인물 사진에서 사람이 마스크를 쓰고 있는지, 쓰지 않았는지, 정확히 쓴 것이 맞는 지 자동으로 가려낼 수 있는 모델을 구현합니다.
- Metric : Accuracy, F1-score
 
### P Stage2 : 정형 데이터 분류 (Tabular Classification)
온라인 상점 이용자의 log 데이터를 이용해, 특정 사용자의 다음달 예상 구매액이 300만원을 넘을 지 예측하는 모델을 구현합니다.
- Metric : AUC
 

### P Stage2 : 한국어 언어모델 학습 및 다중과제 튜닝 (KLUE)
자연어 문장에서 단어간의 관계를 추론하여 정보를 요약하고, 중요한 성분을 파악하는 모델을 구현합니다.
이를 통해 질문에 답변하는 AI를 만들 수 있습니다.
- Metric : accuracy
 
### P Stage3 : 객체 영역 구분 (Image Segmentation) 및 객체 검출 (Object Detection)
쓰레기가 찍힌 사진들 속에서 물체를 분류하는 모델을 만들고, 분류된 결과를 기반으로 쓰레기를 구분하여 분리수거를 할 수 있는 모델을 구현합니다.
- Metric : Dice Coefficient / mAP
 
### P Stage3 : Dialogue State Tracking (DST)
사람간의 대화에서 정보를 추론하고, 대화 상태를 추적하는 모델을 구현합니다.
이를 통해 숙소 예약을 받는 것과 같은 AI를 만들 수 있습니다.
- Metric : Joint Goal Accuracy


### P Stage3 : 기계 독해 (Machine Reading Comprehension)
질문 데이터 없이 knowledge resource 만을 학습하여 다양한 질문에 답변하는 AI를 구현합니다.
어떤 질문이 입력될지 알 수 없어 어려우며, retriver와 reader 두 모델을 직접 구현해야 합니다.
- Metric : Exact Match score

### P Stage4 : Deep Knowledge Tracing (DKT)
교육 서비스(“아이스크림 에듀“)의 실제 이용자 데이터를 통해, 특정 이용자가 새로운 문제를 맞출지 틀릴지 예측하는 모델을 구현합니다.
- Metric : auroc

 
### P Stage4 : 수식인식기
영상처리와 자연어처리 알고리즘의 콜라보로, 수학 수식이 적힌 10만장의 이미지에서 글자와 기호를 인식하고, 순서를 파악하여 LaTeX text 로 변환하는 모델을 구현합니다.
기존 OCR과 다르게 수식을 읽는 방향이 다양하고, 동일한 기호에도 다양한 변형을 극복해야 하는 어려움이 있습니다.
- Metric : ACC, WER 

 
### P Stage4 : 모델최적화 (CPU,GPU 향 최적화)
작은 규모의 Auto ML을 활용하여 작고 빠른 이미지 분류 모델을 만드는 프로젝트입니다. 제한된 자원을 가지고 이미지에서 재활용 쓰레기를 분류하는 AI를 경량화합니다.
- Metric : MACs, F1
