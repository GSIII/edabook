---
title: PyCon Ireland 연도별 기술 키워드 트렌드 분석 (2017–2024)
author: 이하경
date: 2025-05-25
category: PyCon Ireland (2017–2024)
layout: post
mermaid : true
---

작성자 : 이하경

PyCon Ireland는 매년 아일랜드 파이썬 커뮤니티의 현재와 미래를 조망할 수 있는 중요한 행사입니다. 본 포스트에서는 2017년부터 2024년까지 PyCon Ireland에서 발표된 세션들의 주요 기술 키워드를 분석하여, 지난 몇 년간 아일랜드 파이썬 생태계에서 어떤 기술들이 주목받고 변화해 왔는지 그 트렌드를 살펴봅니다. TF-IDF(Term Frequency-Inverse Document Frequency) 분석을 통해 각 연도별로 의미 있는 기술 키워드를 추출하고, 이를 바탕으로 기술 동향의 흐름을 파악했습니다.

## PyCon Ireland 키워드를 통해 본 주요 기술 트렌드 변화

PyCon Ireland의 연도별 발표 키워드 분석 결과, 다음과 같은 주요 기술 트렌드의 변화를 관찰할 수 있었습니다:

*   **웹 기술의 꾸준한 진화:** `Django`, `Flask`와 같은 전통적인 웹 프레임워크는 지속적으로 중요하게 다뤄졌으며, 최근에는 `FastAPI`와 같이 현대적이고 성능 지향적인 프레임워크에 대한 관심이 높아지고 있음을 키워드를 통해 확인할 수 있습니다.
*   **데이터 과학에서 AI 시대로의 명확한 이행:** 초기 "데이터 분석", "머신러닝" (`Machine Learning`), "신경망" (`Neural Networks`) 관련 키워드에서 시작하여, "자연어 처리" (`NLP`), "딥러닝" (`TensorFlow`, `JAX`)으로 전문화되었으며, 2024년에는 `AI`, `LLMs` (대규모 언어 모델), `RAG` (검색 증강 생성), `Vector DB` (벡터 데이터베이스)와 같은 키워드가 급부상하며 AI 시대로의 전환을 명확히 보여주었습니다.
*   **데브옵스 및 인프라 기술의 고도화:** `Docker`, `Serverless`와 같은 초기 키워드에서 `Kubernetes`로, 그리고 클라우드 플랫폼(`AWS`, `Sagemaker`) 및 `MLOps` 관련 키워드로의 변화는 인프라 관리 및 배포 기술의 발전을 시사합니다.
*   **성능과 전문화 도구에 대한 탐구:** `asyncio` (비동기 프로그래밍), `Rust` (성능 최적화를 위한 통합), `Arrow` (Apache Arrow, 고효율 데이터 포맷), `DuckDB` (분석용 DB)와 같은 키워드의 등장은 파이썬 애플리케이션의 성능 향상과 특정 문제 해결을 위한 전문 도구에 대한 관심이 증가하고 있음을 나타냅니다.

## PyCon Ireland 연도별 상세 기술 키워드 분석

PyCon Ireland에서 나타난 주요 기술 키워드의 연도별 변화를 통해 트렌드를 더 자세히 살펴보겠습니다.

### 2017년: 웹 프레임워크와 초기 머신러닝 키워드의 등장

*   **주요 기술 키워드:** `django`, `graphql`, `lmdb`, `neural`, `convolution`, `serverless`, `docker`, `micropython`
*   **트렌드 요약:** `django`를 중심으로 한 웹 개발이 활발했으며, `neural` (신경망) 등 초기 머신러닝 관련 키워드와 `serverless`, `docker`와 같은 데브옵스 기술 키워드가 등장하기 시작했습니다.

### 2018년: 데이터 과학 및 시각화 키워드의 부상

*   **주요 기술 키워드:** `data`, `science`, `visualisation`, `machine learning`, `asynchronous`, `functional`, `pypi`
*   **트렌드 요약:** `data science` (데이터 과학), `visualisation` (시각화), `machine learning` (머신러닝) 키워드가 두드러지며 데이터 중심 기술에 대한 관심이 높아졌습니다. `asynchronous` (비동기) 프로그래밍 관련 키워드도 주목받았습니다.

### 2019년: 머신러닝 심화 및 Kubernetes 키워드 확산

*   **주요 기술 키워드:** `tensorflow`, `nlp`, `kubernetes`, `django`, `flask`, `testing`, `database`
*   **트렌드 요약:** `tensorflow`, `nlp` (자연어 처리) 등 머신러닝 분야의 심도 있는 기술 키워드가 나타났고, 데브옵스 영역에서는 `kubernetes` 키워드가 중요하게 다뤄졌습니다.

### 2023년: 고급 머신러닝, 데이터 엔지니어링, FastAPI 키워드의 활성화

*   **주요 기술 키워드:** `jax`, `nns` (신경망), `arrow` (Apache Arrow), `fastapi`, `asyncio`, `aws`, `micropython`, `pandas`
*   **트렌드 요약:** `jax`와 같은 고급 머신러닝 라이브러리, `arrow`와 같은 데이터 엔지니어링 기술, 그리고 API 개발을 위한 `fastapi` 키워드가 활발하게 논의되었습니다. `aws` (클라우드)의 언급도 증가했습니다.

### 2024년: AI 및 LLM 관련 키워드의 폭발적 증가

*   **주요 기술 키워드:** `ai`, `llms`, `vector` (벡터 DB), `rag`, `genai` (생성형 AI), `rust`, `sagemaker`, `duckdb`, `nicegui`, `pipelines`
*   **트렌드 요약:** `ai`, `llms`를 필두로 한 생성형 AI 관련 키워드가 PyCon Ireland의 핵심 주제로 부상했습니다. 성능 향상을 위한 `rust` 통합, 클라우드 MLOps 플랫폼인 `sagemaker`, 분석 데이터베이스 `duckdb` 등 전문화된 기술 키워드가 다수 등장했습니다.

## 결론: PyCon Ireland 키워드가 말해주는 파이썬의 미래

PyCon Ireland의 연도별 기술 키워드 트렌드 분석은 아일랜드 파이썬 커뮤니티가 웹 기술이라는 견고한 기반 위에서 데이터 과학, 머신러닝을 거쳐 현재 AI 시대로 빠르게 나아가고 있음을 명확하게 보여줍니다. 데브옵스 기술 역시 지속적으로 발전하며 이러한 변화를 뒷받침하고 있습니다.

앞으로 PyCon Ireland에서는 AI 기술의 심층적인 탐구와 더불어, 파이썬의 성능 한계를 극복하기 위한 노력, 그리고 대규모 데이터 처리 및 분석을 위한 고도화된 엔지니어링 기술 관련 논의가 더욱 활발해질 것으로 예상됩니다.


## PyCon Ireland 기술 키워드 트렌드 시각화 (2017–2024)

아래는 PyCon Ireland에서 나타난 주요 기술 키워드의 연도별 변화를 Mermaid 타임라인으로 시각화한 것입니다.

```mermaid
timeline
    title PyCon Ireland 기술 키워드 트렌드 변화 (2017-2024)
    2017
        : 웹 개발 : Django, GraphQL
        : 초기 데이터 과학/ML : LMDB, Neural, Convolution, Text Processing, Classification
        : 데브옵스 & 인프라 : Serverless, Docker
        : 핵심 & 생태계 : Testing, Micropython, CFFI
    2019
        : 데이터 과학 & 시각화 : Data Science, Visualisation, Machine Learning, Statistical, NumPy
        : 웹 개발 : Django, Flask, API
        : 프로그래밍 패러다임 : Asynchronous, Functional
        : 핵심 & 생태계 : PyPI, Code
    2020
        : 데이터 과학/ML : TensorFlow, NLP, Machine Learning, Pandas
        : 데브옵스 & 인프라 : Kubernetes
        : 웹 개발 : Django, Flask, Webpack, API
        : 핵심 & 생태계 : Testing, Micropython
        : 기타 기술 : Blockchain
    2023
        : 고급 ML & 데이터 : JAX, NNs (신경망), Arrow, Pandas, NLP
        : 웹 & API : FastAPI, SQLAlchemy
        : 프로그래밍 & 성능 : asyncio, Micropython
        : 클라우드 & 인프라 : AWS
        : 핵심 & 생태계 : Jupyter Notebooks
    2024
        : AI / LLMs : AI, LLMs, Vector DB, RAG, GenAI, Inference
        : 성능 & 시스템 : Rust
        : 데이터 엔지니어링 & DB : Pipelines, Database, SQL, SQLAlchemy, DuckDB
        : 클라우드 & MLOps : Sagemaker, AWS, Deployment, Docker
        : 웹 개발 : Django, NiceGUI
        : 핵심 & 생태계 : Type Hinting, Testing
