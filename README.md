# RAG (Retrieval-Augmented Generation) 마스터하기

이 프로젝트는 RAG(Retrieval-Augmented Generation)의 핵심 개념과 구현 방법을 단계별로 학습할 수 있도록 구성된 튜토리얼입니다.

## 프로젝트 구조

### 1. DataLoader (데이터를 어떻게 추출할 것인가?)
- 데이터 추출의 기본 개념과 방법 학습
- 다양한 데이터 소스에서 데이터를 추출하는 방법

### 2. TextSpliter (추출한 데이터를 어떤 단위로 나눌 것인가?)
- 텍스트 분할의 중요성과 방법
- 다양한 분할 전략과 최적의 청크 크기 결정

### 3. Embedding (나눈 데이터를 임베딩하기)
- 임베딩의 개념과 중요성
- 다양한 임베딩 모델과 벡터 데이터베이스 활용

### 4. Retriever (어떻게 검색할 건데?)
- 검색 시스템의 구현
- 관련성 있는 문서를 효율적으로 검색하는 방법

### 5. Summarization (요약 문서의 성능이 더 잘나온다!)
- 문서 요약 기법
- 요약을 통한 RAG 성능 향상 방법

### 6. AgenticRAG (Agentic)
- LangChain을 활용한 RAG 구현
- 순차적 학습을 위한 Jupyter Notebook:
  - `00-LangChain.ipynb`: LangChain 기본 개념
  - `01-NaiveRAG.ipynb`: 기본 RAG 구현
  - `02-RelevanceCheck.ipynb`: 관련성 검사
  - `03-WebSearch.ipynb`: 웹 검색 통합
  - `04-QueryRewrite.ipynb`: 쿼리 재작성
  - `05-AgenticRAG.ipynb`: 에이전트 기반 RAG 구현

## 시작하기

### 환경 설정
1. Python 3.11 가상환경 생성:
```bash
python3.11 -m venv venv
```

2. 가상환경 활성화:
```bash
source venv/bin/activate
```

3. 필요한 패키지 설치:
```bash
pip install -r requirements.txt
```

### Jupyter Notebook 실행
```bash
jupyter notebook
```

## 학습 순서
1. DataLoader → TextSpliter → Embedding → Retriever → Summarization 순서로 기본 개념 학습
2. AgenticRAG 디렉토리의 Notebook을 순서대로 실행하여 실습

## 주요 기술 스택
- Python 3.11
- LangChain
- OpenAI API
- FAISS
- Jupyter Notebook
- 기타 필요한 라이브러리들 (requirements.txt 참조)
