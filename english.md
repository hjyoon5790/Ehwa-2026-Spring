# 🎓 2026 Spring 캡스톤디자인 프로젝트 요약

> 이화여자대학교 컴퓨터공학 전공 캡스톤디자인 | 2026 Spring  
> 전체 18팀 (4팀 결번) | 연구 트랙 5팀 · 산학 트랙 13팀

---

## 📋 전체 목록

| 팀번호 | 팀명 | 트랙 | 서비스명 | 한 줄 요약 |
|:---:|:---:|:---:|:---:|:---|
| 1 | 이사장님 | 🔬 연구 | CyCLIP | 위성 종류가 달라도 태풍을 정확히 분류하는 AI |
| 2 | Sudo | 🏢 산학 | 온케어 | 사진 찍으면 영양 분석, 만성질환 맞춤 건강관리 앱 |
| 3 | Alltology | 🔬 연구 | — | 온톨로지로 LLM 할루시네이션 줄이기 연구 |
| 5 | 규교굥 | 🏢 산학 | Do Not Open This Box. | AI NPC 손님과 대화하는 공포 골동품 게임 |
| 6 | Greenfield | 🏢 산학 | Histour | 역사 인물과 AI 대화하며 한국 역사 장소 여행 |
| 7 | reverdir | 🏢 산학 | — | 매칭·미션·투표·공개까지 마니또 활동 전 과정 앱 |
| 8 | 하면된다 | 🏢 산학 | Vintic | AI 가격 검증 + 정시 경매 빈티지 거래 플랫폼 |
| 9 | Cloud9 | 🏢 산학 | Canary | 퀀트 자동매매 전략 이상 탐지 실시간 모니터링 |
| 10 | 212223 | 🏢 산학 | — | 프롬프트 자동 최적화 + LLM API 비용 실시간 비교 |
| 11 | 알고리듬 | 🏢 산학 | SpeedSchedule | AI 기반 시험 감독·시프트 스케줄 자동 배정 |
| 12 | 404 | 🏢 산학 | 여기지! | 여성 1인 여행자 안전 지도 + 동행 매칭 |
| 13 | Semicolone; | 🏢 산학 | Flow | AI 대화를 내 지식으로 저장·정리하는 PKM 플랫폼 |
| 14 | def | 🔬 연구 | — | Apple Silicon에서 AI 병목 찾고 스스로 최적화하는 에이전트 |
| 15 | 햄부기 | 🔬 연구 | — | Vision Transformer 경량화로 엣지 장치에서 AI 구동 |
| 16 | 퓨터 | 🏢 산학 | — | 대화할수록 성격 바뀌는 AI 캐릭터 영어 회화 학습 |
| 17 | SPY | 🏢 산학 | Moni | 소비 패턴 분석 + 감정형 피드백 소비 코칭 앱 |
| 18 | 디바트 | 🔬 연구 | — | 작품 이미지 → AI 도슨트 해설 자동 생성 + 음성 변환 |
| 19 | Logue | 🏢 산학 | Logue | 자연어로 DB 조회하는 AI 데이터 분석 인터페이스 |

---

## 🔬 연구 트랙

### Team 1 · 이사장님 — CyCLIP

> **위성 종류가 달라져도 태풍을 정확히 분류하는 AI**

기상 위성은 종류마다 찍히는 방식이 다르다. Himawari로 학습한 AI를 GOES 위성 사진에 쓰면 성능이 뚝 떨어지는 문제가 생긴다. 이 팀은 **테스트 시점에 프롬프트를 조정(TPT)** 하는 방식으로, 카메라 기종이 바뀌어도 같은 물체를 알아보듯 센서가 달라져도 태풍을 안정적으로 분류하는 모델을 만든다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 황의원 교수님 |
| 팀구성 | 설영은, 신지민, 윤희서 |
| 핵심 기술 | CLIP 기반 VLM, Test-Time Prompt Tuning, Cross-Sensor Domain Adaptation |
| 개발환경 | Python / PyTorch / GPU 서버 |
| GitHub | [chairwomans-capstone](https://github.com/chairwomans/chairwomans-capstone) |

---

### Team 3 · Alltology

> **온톨로지를 붙이면 LLM이 덜 틀린다 — 실험으로 증명**

LLM이 그럴듯한 거짓말(할루시네이션)을 하는 문제를 해결하기 위해, 개념 간 관계를 명시한 **온톨로지** 지식 체계를 LLM에 붙였을 때 얼마나 정확도가 올라가는지 실험하고 비교하는 연구 논문을 작성한다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 황의원 교수님 |
| 팀구성 | 박세령, 이다영, 손현경 |
| 핵심 기술 | 온톨로지, LLM 파라미터 확장, RAG 비교 실험 |
| 개발환경 | Python / FastAPI / Vue 3 / OpenAI API |
| GitHub | [Graduation-Project](https://github.com/Ontology0/Graduation-Project) |

---

### Team 14 · def

> **Mac mini에서 AI가 스스로 병목을 찾고 고친다**

클라우드 없이 내 컴퓨터(Apple Silicon)에서 AI를 돌릴 때 어디서 느려지는지(CPU·GPU·메모리 병목) AI 에이전트가 실시간으로 감지하고, 스스로 전략을 바꿔 성능을 끌어올리는 **자율 최적화 프레임워크**를 만든다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 심재형 교수님 |
| 팀구성 | 서혜원, 신은서, 이재린 |
| 핵심 기술 | MLX, LangChain Agent, Local LLM (Llama 3 / Ollama), Streamlit 대시보드 |
| 개발환경 | macOS / Mac mini (Apple Silicon) / 외부 API 없음 |
| GitHub | [def](https://github.com/capstone-2026-ewha/def) |

---

### Team 15 · 햄부기

> **거대한 AI 모델을 작은 엣지 장치에서 돌리도록 가볍게 줄이기**

Vision Transformer(ViT) 같은 무거운 이미지 인식 모델을 Jetson AGX Orin 같은 소형 장치에서 돌릴 수 있도록 **가지치기(Pruning)·경량화** 파이프라인을 구축하고, 속도·정확도·에너지 효율을 측정해 성능을 분석한다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 심재형 교수님 |
| 팀구성 | 신성현, 송영채, 장수연 |
| 핵심 기술 | PyTorch Pruning, TensorRT, ONNX, Hugging Face ViT, Jetson AGX Orin |
| 개발환경 | Windows PC + Jetson AGX Orin / TensorBoard 시각화 |
| GitHub | [Hambugy](https://github.com/Ewha-Capstone-Project/Hambugy) |

---

### Team 18 · 디바트(deep-art)

> **작품 사진을 넣으면 AI가 도슨트 해설을 만들고 음성으로 읽어준다**

전문 도슨트를 고용하기 어려운 소규모 전시를 위해, 작품 이미지와 정보를 입력하면 AI가 해설문을 자동 생성하고 TTS로 음성 변환까지 해주는 서비스. 시각장애인을 위한 **배리어프리 모드**도 함께 제공한다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 박현석 교수님 |
| 팀구성 | 최현서, 이나겸, 김나경 |
| 핵심 기술 | Multimodal LLM (이미지 분석), RAG 기반 콘텐츠 생성, Google Cloud TTS |
| 개발환경 | React + TypeScript / FastAPI / PostgreSQL / OpenAI API |
| GitHub | [deep-art](https://github.com/ewha-deep-art/deep-art) |

---

## 🏢 산학 트랙

### Team 2 · Sudo — 온케어(On-Care)

> **음식 사진 한 장으로 식단 기록, 만성질환 맞춤 건강관리**

고혈압·당뇨 등 만성질환자가 음식 사진을 찍으면 YOLO 기반 AI가 영양소를 자동 분석하고, LLM이 질환에 맞는 식단·운동 계획을 개인화해 추천한다. 포인트 보상·streak 시스템으로 꾸준한 사용을 유도한다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 황의원 교수님 |
| 팀구성 | 최지수, 박서연, 신수빈 |
| 핵심 기술 | YOLOv8 (음식 인식), GPT-4 챗봇, FCM 알림, 공공데이터 식품 영양 DB |
| 개발환경 | Flutter (iOS/Android) / FastAPI / MySQL |
| GitHub | [sudo-capstone-project](https://github.com/CSE-Sudo-26/sudo-capstone-project) |

---

### Team 5 · 규교굥 — Do Not Open This Box.

> **평범한 골동품 가게 → 금지된 상자를 열면 공포 게임으로 변한다**

할머니의 골동품 가게를 물려받아 운영하는 시뮬레이션 게임. 어느 날 수상한 상자를 발견하면서 공포 게임으로 전환된다. AI NPC 손님과 **선택지 없이 자유롭게 타이핑으로 대화**할 수 있어 몰입감이 극대화된다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 윤명국 교수님 |
| 팀구성 | 정혜교, 윤민주, 박남규 |
| 핵심 기술 | Unity 3D, 생성형 AI NPC, Local LLM |
| 개발환경 | Unity / Blender / Clip Studio / FastAPI (필요 시) |
| GitHub | [Start2026_1](https://github.com/muffinhead03/Start2026_1) |

---

### Team 6 · Greenfield — Histour

> **한국 역사 인물과 AI로 대화하며, 실제 역사 장소를 스토리 기반으로 여행**

외국인 관광객과 역사에 관심 있는 국내 사용자를 위해, AI가 역사 인물로 빙의해 대화하고 스토리 기반으로 역사 장소를 연결해 여행 코스를 추천한다. 다국어 지원으로 외국인 접근성을 높인다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 컨택 중 |
| 팀구성 | 최준희, 권은재, 김재희 |
| 핵심 기술 | LLM 기반 역사 인물 대화, 다국어 번역, Leaflet 지도 |
| 개발환경 | Next.js / FastAPI / PostgreSQL / OpenAI API |
| GitHub | [greenfield-project](https://github.com/greenfield-2026-capstone/greenfield-project) |

---

### Team 7 · reverdir

> **마니또 활동 전 과정을 앱 하나로 — 매칭부터 정체 공개까지**

동아리·회사·친구 모임의 마니또를 진행자 없이 자동화한다. 익명 매칭, 미션 수행, 익명 채팅, 힌트 제공, 의심·투표, 랭킹, 정체 공개까지 전 과정이 앱 하나에서 돌아간다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 미정 |
| 팀구성 | 전채연, Lyu Dongying, 이은효 |
| 핵심 기술 | FCM 푸시 알림, Kakao Link API, OAuth |
| 개발환경 | Flutter (Android) / Spring Boot / PostgreSQL |
| GitHub | [reverdir_repo](https://github.com/team-capstone-reverdir-2026/reverdir_repo) |

---

### Team 8 · 하면된다 — Vintic

> **AI가 가격이 적정한지 검증하고, 정해진 시간에만 경매가 열리는 빈티지 거래**

빈티지 플랫폼의 두 가지 문제를 해결한다. ① 판매자가 임의로 가격을 매겨 구매자가 적정가를 모르는 문제 → AI가 시세를 검증해 병기. ② 원하는 물건이 언제 올라올지 몰라 무한 스크롤하는 피로 → 정해진 시간에만 경매 오픈.

| 항목 | 내용 |
|------|------|
| 지도교수 | 오세은 교수님 |
| 팀구성 | 김수연, 이예주, 조채윤 |
| 핵심 기술 | GPT-4o Vision (가격 검증), WebSocket (실시간 경매) |
| 개발환경 | Next.js / Spring Boot / MySQL / Docker |
| GitHub | [Team-Hamyeon](https://github.com/hamyeon/Team-Hamyeon) |

---

### Team 9 · Cloud9 — Canary

> **여러 퀀트 전략을 동시에 돌릴 때, 문제 생긴 전략을 즉시 탐지**

개인 자동매매 투자자가 여러 전략을 동시에 운용할 때 어느 전략에서 이상이 생겼는지 실시간으로 감지하고 대시보드로 시각화해준다. WebSocket 기반 실시간 스트리밍과 Slack·이메일 알람 지원.

| 항목 | 내용 |
|------|------|
| 지도교수 | 컨택 중 |
| 팀구성 | 박나림, 임도경, 최은우 |
| 핵심 기술 | 이상 탐지 알고리즘, WebSocket, Binance API, Recharts 대시보드 |
| 개발환경 | React / FastAPI / PostgreSQL / scikit-learn / PyTorch |
| GitHub | [Cloud9-capstone-2026](https://github.com/Cloud9-capstone-2026) |

---

### Team 10 · 212223

> **프롬프트를 AI가 최적화해주고, GPT·Gemini·Claude 비용을 실시간 비교**

AI API를 쓸 때 프롬프트를 잘못 작성하면 비용이 폭등한다. 사용자가 프롬프트를 입력하면 AI가 자동으로 최적화하고, GPT-4·Gemini·Claude 각각에 넣었을 때의 예상 비용을 실시간으로 계산해 비교해준다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 심재형 교수님 |
| 팀구성 | 고윤진, 김나현, 이유진 |
| 핵심 기술 | tiktoken (토큰 계산), LiteLLM, LLMLingua (프롬프트 압축) |
| 개발환경 | React / FastAPI / Firebase Firestore / Vercel |
| GitHub | [graduationproject](https://github.com/0727n1122-beep/graduationproject) |

---

### Team 11 · 알고리듬 — SpeedSchedule

> **시험 감독·시프트 배정을 AI가 자동으로, 엑셀 수작업 없이**

학교 행정에서 시험 감독 배정과 시프트 스케줄을 아직도 엑셀로 수동 작업하는 경우가 많다. AI가 교사 선호도·숙련도·공정성을 반영해 자동 배정하고, 결원 발생 시 대리 근무자를 자동 매칭한다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 컨택 중 |
| 팀구성 | 조상은, 정지유, 이시은 |
| 핵심 기술 | AI 스케줄 최적화 (PyTorch), Redis 캐싱, WebSocket |
| 개발환경 | React / Spring Boot / MySQL → PostgreSQL 전환 검토 / AWS EC2·RDS |
| GitHub | [speedSchedule](https://github.com/speedSchedule) |

---

### Team 12 · 404 — 여기지! (여성 기행 지켜!)

> **여성이 직접 쓴 안전 리뷰를 지도에 표시, 같은 지역 여성끼리 동행 매칭**

여성 혼자 여행할 때의 불안감과 안전 정보 부족 문제를 해결한다. 여성 사용자가 직접 작성한 안전 리뷰를 지도에 시각화하고, 같은 지역을 여행하는 여성끼리 동행을 매칭해준다.

| 항목 | 내용 |
|------|------|
| 지도교수 | — |
| 팀구성 | 이아림, 노유나, 이채원 |
| 핵심 기술 | Google Maps JavaScript API, OpenAI API |
| 개발환경 | React / FastAPI / MySQL |
| GitHub | [capstone-team404](https://github.com/capstone-team404) |

---

### Team 13 · Semicolone; — Flow

> **AI에게 물어본 것들을 내 지식으로 쌓아가는 개인 지식 관리 플랫폼**

ChatGPT 대화는 하고 나면 잊혀진다. Flow는 AI 질문과 답변을 저장·요약·태깅하고, 시간이 지나면 다시 꺼내 보여줘 장기 기억으로 만들어준다. 텍스트 임베딩으로 관련 인사이트를 자동 연결한다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 이미정 교수님 |
| 팀구성 | 신지원, 이채원, 윤현진 |
| 핵심 기술 | OpenAI Embedding (유사 인사이트 연결), 스케줄링 기반 리마인드 |
| 개발환경 | React / Spring Boot / MySQL·PostgreSQL |
| GitHub | [Semicolone](https://github.com/Semicolone) |

---

### Team 16 · 퓨터

> **대화할수록 성격이 변하는 AI 캐릭터와 영어 회화 연습**

기존 영어 학습 앱은 고정된 응답이라 금방 질린다. 이 서비스는 사용자와 대화를 쌓을수록 AI 캐릭터의 성격·말투가 변화해 정서적 유대감이 생긴다. Reddit·YouTube에서 최신 슬랭을 자동 수집해 실용 영어를 가르친다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 심재형 교수님 |
| 팀구성 | 김민주, 백은혜, 이찬희, 최윤서 |
| 핵심 기술 | GPT-4o, Pinecone (벡터 DB), Rive 애니메이션, PRAW (Reddit API) |
| 개발환경 | Next.js / Spring Boot + FastAPI / PostgreSQL |
| GitHub | [capstone](https://github.com/puter8/capstone) |

---

### Team 17 · SPY — Moni

> **소비 패턴 분석 + 감정형 피드백으로 지갑을 지키는 소비 코칭 앱**

예산을 세워도 지키기 어려운 사람들을 위한 앱. 지출 데이터를 시계열로 분석해 소비 패턴을 파악하고, "이번 달 카페 지출이 많았어요"처럼 감정형 피드백을 준다. 예산 지킬 때 보상도 제공한다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 오세은 교수님 |
| 팀구성 | 신희조, 윤수연, 박은수 |
| 핵심 기술 | PyTorch 기반 소비 패턴 예측, OpenAI API (자연어 인사이트), 하이브리드 추천 |
| 개발환경 | Kotlin Android / FastAPI / MySQL |
| GitHub | [SPY-capstoneREPO](https://github.com/SPY-capstone-2026/SPY-capstoneREPO) |

---

### Team 19 · Logue

> **SQL 몰라도 말로 물어보면 DB에서 데이터를 꺼내준다**

기획자·마케터가 데이터를 보려면 매번 개발자에게 부탁해야 한다. Logue는 "지난달 매출 상위 10개 상품 알려줘"처럼 자연어로 질문하면 AI가 SQL을 자동 생성해 DB를 조회하고 결과를 시각화해준다.

| 항목 | 내용 |
|------|------|
| 지도교수 | 하진용 교수님 |
| 팀구성 | 손하늘, 김겨레, 김예원, 민지인 |
| 핵심 기술 | Text-to-SQL, LLM 기반 자연어 쿼리, ECharts 시각화 |
| 개발환경 | Next.js / Spring Boot 3 (Java) + FastAPI / PostgreSQL / AWS |
| GitHub | — |

---

*최종 업데이트: 2026-04-02*
