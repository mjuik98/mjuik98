# 🌌 Welcome to mjuik98's Universe
> **문제를 끝까지 파고들어 실제로 동작하는 AI 서비스를 만드는 엔지니어, 최귀빈입니다.**

안녕하세요.
LLM/RAG, 생성형 이미지, 추천 시스템을 중심으로 서비스를 직접 구현하고 있는 **AI 엔지니어 최귀빈(mjuik98)** 입니다.<br>
6년간의 현장 리더 경험으로 쌓은 책임감과 실행력을 바탕으로, 모델 성능 개선부터 서비스 구조화, 배포 가능한 형태의 결과물 정리까지 꾸준히 해왔습니다.

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=mjuik98&theme=tokyonight)](https://git.io/streak-stats)

---

## 🔭 About Me
- **Background**: 대한민국 공군 중사 전역 (2016. 01. 10 ~ 2021. 12. 31)
- **Status**: Codeit AI 엔지니어 부트캠프 4기 (2025. 07. 03 ~ 2026. 01. 29)
- **Focus**: LLM, RAG, Generative AI, Recommendation, Computer Vision
- **Interested In**: Retrieval 품질 개선, 생성형 시스템 안정화, 서비스형 AI 백엔드 구현

---

## 🚀 Key Projects

### 🧾 [문서 기반 RAG 지식도우미](https://github.com/mjuik98/RAGKnowledgeAssistant.git)
**공공 문서를 바탕으로 근거와 출처를 함께 제시하는 한국어 질의응답 시스템**
- PDF/TXT/DOCX 문서 수집, 파싱, 청크 분할, 색인 파이프라인 구현
- 하이브리드 검색, 리랭킹, no-answer 정책, prompt injection guard를 포함한 RAG 파이프라인 구성
- FastAPI API, Streamlit 데모, 평가 스크립트, Docker 환경까지 포함해 실행 가능한 서비스 형태로 정리

### 🎬 [CineMatch 개인화 추천 시스템](https://github.com/mjuik98/CinematchPersonalizedRecommender.git)
**사용자 이력과 콘텐츠 메타데이터를 결합한 multi-stage 영화 추천 시스템**
- 협업 필터링 기반 후보 생성, 메타데이터 기반 랭킹, MMR 기반 재정렬 구조 구현
- cold-start 추천과 추천/피드백 로그 저장 구조 설계
- HitRate, NDCG, MRR, Coverage, Diversity 등 오프라인 평가 지표를 구성해 추천 품질 검증

### 📑 [가족 식사 공유&기록](https://github.com/mjuik98/FamilyMeal)
**가족 간의 식사 기록을 공유하고 소통하며 올바른 식습관을 형성하도록 돕는 웹 서비스**
- Next.js 기반의 부드러운 애니메이션과 반응형 디자인으로 직관적인 사용자 경험 제공
- 식사 사진 업로드(+확대), 댓글(+답글), 좋아요(이모지) 기능을 통해 실시간 가족 커뮤니케이션 강화
- 주간 식사 통계 시각화 및 과거 기록(Archive) 관리 기능 구현

### 🎨 [AdGen_AI](https://github.com/Dongjin-1203/AdGen_AI)
**이미지 1장으로 가상 피팅 이미지, 광고 캡션, 웹페이지를 생성하는 AI 광고 서비스**
- SDXL/RealVisXL, IDM-VTON, ControlNet, IP-Adapter 기반 광고 이미지 생성 파이프라인 구현
- Vision AI 메타데이터 기반 PromptEngine을 설계해 Resort / Retro / Romantic 3종 스타일 프리셋 자동 생성 구현
- SDXL VAE의 FP16 디코딩 이슈로 발생한 격자 무늬 아티팩트를 float32 upcasting 및 Fixed VAE 교체로 해결

### 📑 [입찰메이트 RAG 시스템](https://github.com/Lee-keonhee/codeit_RAG)
**LangGraph 기반 지능형 B2G 입찰 문서 검색 및 질의응답 시스템**
- 정보 요청, 비교, 요약, 조건 추출, 유사 문서 검색까지 5개 intent 지원
- 주제 변경 감지, 다중 필터 병합, 하이브리드 검색, 리랭킹, retrieval/answer evaluation을 포함한 RAG 파이프라인 설계
- intent 및 retrieval 평가 결과에 따라 재검색 또는 답변 생성으로 분기되는 conditional routing 로직 구현

---

## 🛠️ Technical Artifacts

### 💻 Languages
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JASS](https://img.shields.io/badge/JASS-D97757?style=for-the-badge&logo=none&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)

### ⚡ Tools & IDE
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Antigravity](https://img.shields.io/badge/Antigravity-8A2BE2?style=for-the-badge&logo=google-gemini&logoColor=white)

### 🧠 AI / ML & Infra
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-000000?style=for-the-badge&logo=meta&logoColor=white)
![Chroma](https://img.shields.io/badge/Chroma-FF0000?style=for-the-badge&logo=chroma&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=google-colab&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

### 📫 Contact
- **Email**: mjuik98@gmail.com

<br>
<p align="center">Thanks for stopping by.</p>
