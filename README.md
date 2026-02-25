# 🎬 Korean Drama RAG QA System

한국 드라마 데이터를 기반으로 RAG(Retrieval-Augmented Generation)와 일반 LLM의 답변 성능을 비교하는 QA 시스템

## 🛠 Tech Stack
- **Model**: Google Flan-T5-base
- **Embedding**: sentence-transformers/all-MiniLM-L6-v2
- **Library**: Transformers, SentenceTransformers, NumPy

## ✨ 주요 기능
- 한국 드라마 21편을 Knowledge Base로 구축
- 질문에 대해 유사도 기반 문서 검색 (Top-K Retrieval)
- RAG 방식 vs 일반 LLM 방식 답변 비교

## 🚀 실행 방법
```bash
pip install transformers sentence-transformers
python llm_rag_qa.py
```

## 📌 예시 질문
```
Which 2018 Korean drama satirizes elite families obsessively pushing their children into top universities?
```
