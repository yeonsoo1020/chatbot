# 폐암 및 유방암 상담 챗봇

## 📌 프로젝트 개요
본 프로젝트는 폐암 및 유방암 관련 정보를 제공하는 의료 상담 챗봇을 개발하는 것을 목표로 하여, 챗봇의 역할에 따라 The Empathetic Expert, The Mindful Companion, Health Digital Coach, The Health Curator으로 나누어 구현하였습니다.

- 진행기간 : `2025.01` ~ `2025.03`
- 팀프로젝트(5인)

## 📝 역할
Mindful Companion 챗봇 구현

https://chatbot-mindful-companion.streamlit.app/

## 🔍 기능 개요
**RAG(Retrieval-Augmented Generation) 기법 적용**
- **미국 국립암연구소(NCI) PDQ 문서 기반 검색** → 공식 의료 정보를 바탕으로 신뢰성 높은 답변 제공  
- **최신 정보 반영** → GoogleSerper API를 활용한 웹 검색 기능 추가  
- **ReAct Agent 기반 응답 최적화** → 질문을 분석하여 최적의 검색 방식을 자동 선택
- **역할 프롬프트** → "Mindful Companion" 역할을 프롬프트로 지정하여, 감정적 지원과 심리적 안정에 초점을 맞추도록 구현
- GPT-4o-mini API 활용


[![Image](https://github.com/user-attachments/assets/cc0521f1-6013-4372-ad7b-37abb720bd68)](https://github.com/user-attachments/assets/cc0521f1-6013-4372-ad7b-37abb720bd68)
