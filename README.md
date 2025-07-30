## 💖 LLM-Based Sentiment Analysis & Happiness Index System  
📅 Jul. 2024 – Aug. 2024  
🎯 *Automated emotional feedback system using user-generated text*

---

### 🧩 Overview  
- 사용자 일기 기반 **실시간 감정 분석 및 행복지수(Happiness Index)** 산출 시스템 구축  
- KeyBERT + BERT 임베딩 + KMeans 군집화 → 감정 키워드를 `Purpose(P)` / `Health(H)` / `Education(E)` 영역으로 자동 분류  
- 감정 분포 및 추이 시각화 + 색상 기반 감정 피드백 인터페이스 구현

---

### 🧠 Key Features  
- **단어 길이별 빈도 분석**: 짧은 감정 키워드의 높은 빈도 → 전처리 및 임베딩 전략 개선  
- **감정 카테고리 분포 분석**:  
  - 긍정: 27.3%  
  - 부정: 72.7% → 사용자의 감정 기록에서 부정 감정이 압도적 비율을 차지  
- **자동 감정 영역 분류 정확도**: 85% 달성 (BERT 임베딩 + 의미기반 클러스터링)  
- **LLM 기반 감성 해석 시스템 완성**: 기존 rule-based 방식 대비 높은 유연성과 정확도 확보  
- **AI 윤리 및 사회 기여 인사이트 확보**: 사용자 정서 진단 및 피드백 기반 AI 서비스 설계 경험

---

### ⚙️ Technical Stack

- **Data & Preprocessing**: `Python`, `Pandas`, `NumPy`  
- **NLP & AI Models**: `KeyBERT`, `BERT`, `Huggingface Transformers`, `KMeans`, `LLM`  
- **Visualization**: 감정 키워드 추이, 긍부정 분포, 감정 색상 매핑  

---

### 🧪 System Architecture (Step-by-Step)

1. **감정 키워드 기반 감성 분석 시스템 설계**  
   - 감정 단어 사전 및 사용자 텍스트 전처리  
   - 감정 비율 시각화 (긍정/부정)

2. **LLM 기반 임베딩 및 감정 의미 클러스터링**  
   - KeyBERT로 키워드 추출 → BERT 임베딩 → KMeans로 3영역 분류  
   - 각 영역에 가중치 부여 → 정량화된 행복지수 산출

3. **정성 지표 분석 및 피드백 시스템 구현**  
   - 감정 키워드 색상 시각화 및 감정 진단 프로토타입 개발  
   - AI 피드백 메시지 제공 기능 포함

---

### 🗂️ Data Summary

- 📚 데이터 유형: 감정 키워드, 분류 정보, 색상 정보  
- 📌 출처: 논문 *"한국어 감정표현단어의 추출과 범주화"*, 감정 단어 사전 848개, 색상 매핑 41개  
- 💡 분석 목적: 정량적 감정 피드백 제공 및 사용자의 정서 흐름 분석  

---
