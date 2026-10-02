# 라이트 형제

N.O.V.A. 2026 대화형 의료 진단 AI 에이전트 대회 참가팀 '라이트 형제'입니다. 저희 팀은 2명으로 구성되어 있습니다.
저희는 어릴 적 부모님의 해외 병원 봉사활동으로 인해 어릴 적부터 해외 경험이 있었으며 의료 도메인에 관심이 많았습니다. AI, LLM, RAG, DL, Vision 등의 프로젝트와 현장 경험을 기반으로 의미있는 Docter Agent를 개발하고 싶습니다.

| 구성 | 이름 | 관련 자료 |
| --- | --- | --- |
| 팀장 | 박경빈 | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/overjoy1008?tab=repositories) [![Portfolio](https://img.shields.io/badge/Portfolio-4285F4?style=flat-square&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1MVLfTg1Am75TnWkmBLbALk2cbl-irDIK/view?usp=sharing) |
| 팀원 | 박경륜 | [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Jeremy-0204) |

**Our Project Goal:**
- 대화에서 증상과 시간 경과를 추출하는 기록 Agent / 의료 근거를 검색해 진단 후보를 갱신하는 추론 Agent / 후보를 구별할 질문과 검사를 고르는 행동 Agent 등 구현하기
- 공개 증례의 정보를 단계별로 나눠 ‘현재 정보-다음 행동’ 기반의 행동 판단 데이터셋 만들기
- 대화 내역을 기반으로 자동 축적되는 검색용 지식 DB를 통해 RAG 파이프라인 구축하기

## 공동 portfolio.

### [SKT AI Fellowship — RAG 기반 XR 교육 서비스](https://github.com/SKT-AI-Fellowship-Metaphor/VR-Dinosaur-Museum)
- **프로젝트 개요:** Unity·Meta Quest 3 기반 XR 학습 환경과 음성 질의, 3D 콘텐츠 생성, LLM/RAG 답변 기능을 연결한 교육 서비스 공동 개발
- **박경빈 역할:** VR 학습 환경 구현, 음성 질문(STT)·3D 모델 생성·LLM 답변 서버의 API 연동
- **박경륜 역할:** RAG 파이프라인과 sLLM 기반 질의응답 시스템 구현, 검색 결과 및 context 구성 최적화
- **성과:** LLM 입력 context 약 30,000토큰에서 1,000토큰으로 축소, 약 96.67% 절감

## 박경빈 portfolio.

### 컴투스 인턴 — RAG 사내 전문가 검색 챗봇

- **역할·기술:** LLM 기반 데이터 가공, 임베딩 모델 학습, FastAPI·Vector DB 기반 검색 서비스 및 자동 갱신 파이프라인 개발
- **문제·접근:** 직원 DB에 부족한 구체적 업무 경험 정보를 주간보고서로 보완. 10년치 보고서를 JSON 형식으로 요약·정규화해 학습 데이터와 검색 지식으로 활용
- **성과:** Recall@10 0.04에서 0.47로 개선. 신규 보고서 자동 요약·벡터화·반영 및 서비스 배포, 다른 부서 활용

### [EventSep: 사전 학습 모델 결합 기반의 선택적 음원 분리](https://eventsep-demo.onrender.com/)

- **역할·기술:** 제1저자. 음향 구간 감지·마스킹, U-Net 기반 분리 모델과 Diffusion 기반 생성 모델의 주파수별 앙상블
- **문제·접근:** 생성된 음악에서 자연어로 지칭한 악기나 소리를 선택적으로 편집하기 어려운 문제를 대상으로, GPU와 연구 기간의 제약을 고려해 추가 학습 없이 사전학습 모델 결합
- **성과:** VGGSound 데이터셋 기준 CLAPScore 약 25% 개선

## 박경륜 portfolio.

### 한동대학교 Deep Learning Lab — Traffic Sign Detection & Classification

- **역할·기술:** TT100K 데이터셋 대상 PP-YOLOE+ 객체 탐지와 ResNet 이미지 분류를 결합한 two-stage 인식 파이프라인 개발, COCO 사전학습 모델 fine-tuning
- **문제·접근:** 교통표지판 탐지·분류 성능 개선을 위한 threshold tuning 및 pseudo-labeling 적용
- **성과:** Detection mAP@0.5 0.855, classification accuracy 99.5% 달성. F1 score 0.760에서 0.896으로 개선, Precision 0.825 및 Recall 0.980 달성

### STRADVISION 연구 인턴 — 실시간 Ego-Vehicle Binary Segmentation

- **역할·기술:** 약 3.3만 쌍의 멀티카메라 데이터 처리부터 학습·평가까지 end-to-end 파이프라인 구축. PIDNet-S 기반 Teacher와 Knowledge Distillation 기반 경량 Student 모델 실험
- **문제·접근:** 자율주행 주차 환경의 차량 영역 분할을 대상으로, 경량 architecture별 정확도와 연산량 비교를 통한 실시간 배포 가능성 검토
- **성과:** Teacher mIoU 0.9801 달성, 최고 0.9812
