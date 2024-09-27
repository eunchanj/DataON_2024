## DataON_2024
- 2024 연구데이터 분석활용 경진대회
- 최종발표자료 https://www.figma.com/slides/pOFBYDIzumcvzi8vkOokIO/DataOn_240920-(Copy)?t=TSVFzvNYGcOp6AxH-6

## Review & feedback

### 2024 연구데이터 분석 활용 경진대회 최종발표자료 요약

**팀명**: 5po

**프로젝트명**: "멍의" 헬스케어

**대회 기간**: 2024년 8월 – 2024년 9월

**팀 구성원**:

- 장은찬: 바이오메디컬 데이터 사이언티스트, 팀 리드
- 임준영: 의료 인공지능 엔지니어

---

### 프로젝트 개요

- **목표**:
    - 반려동물 건강 관리에 필요한 빠르고 정확한 상담 도구 개발
    - 대형 언어 모델(LLM) 기반 반려동물 건강 챗봇 구축
- **시장 상황**:
    - 2020년 기준, 반려동물 시장 약 3조 원 규모로 성장
    - 반려동물을 가족처럼 여기는 ‘펫팸족’ 트렌드 확산
    - 반려동물 건강 관리에 대한 수요 증가

### 사용된 데이터

- **DataON**:
    - 한국과학기술정보연구원(KISTI) 제공 동물 질병 텍스트 데이터 활용
- **AI-Hub**:
    - 반려동물(개, 고양이) 건강 정보 데이터셋 사용
    - 주요 256개 질병의 정의, 원인, 증상, 진단, 치료 정보 포함
    - 총 120,365건의 건강 정보와 4,000개의 이미지 사용

### 모델 개발

- **모델 유형**:
    - Retrieval-Augmented Generation (RAG) 시스템 활용
- **데이터 전처리**:
    - 동물 질병 데이터를 문서 형태로 변환하여 모델 학습에 사용
- **사용된 도구**:
    - BM25 및 임베딩 기법 활용
    - FlashrankRerank 알고리즘 적용 (정보 검색 최적화)
    - 모델 생성에 EXAONE 3.0 사용

### 평가

- **평가 방법**:
    - 대형 언어 모델(LLM) 및 수의사 국가시험 문제 적용 성능 비교
    - RAGAS 점수 체계 사용 (정보 검색 및 응답 생성 정확도 평가)
- **결과**:
    - 수의사 상담용 질문에 높은 정확도로 응답 생성

### 다음 단계

- **모델 개선**:
    - 추가 학습 및 파인 튜닝 진행 예정
    - 반려동물 헬스케어 챗봇 앱으로 상용화 검토

### 결론

- 대형 언어 모델 및 RAG 시스템을 통해 반려동물 헬스케어에서 인공지능의 가능성 확인
- 반려동물 보호자를 위한 효율적인 건강 상담 도구로서 상용화 가능성 높음

### FeedBack

1. 최종 결과: 최종 발표까지, 수상 X, 11팀 발표평가 5팀 수상
2. 최종발표가 KISTI 본원 (대전)에서 시행 
3. 대부분 대학원생들의 참여 및 평가도 교수님 스타일로 평가 → 연구 방법 및 정성 부분에 많은 가중치가 있을 것으로 추정됨
4. 최신 트랜디한 기술에 대한 평가는 미흡하지 않나 생각이 들음
5. 아무래도 대회 취지가 연구 관점에 초점 따라서 서비스 측면에서의 어필은 적합한 대회가 아님 → 서비스에 초점이 맞춰진 경진대회 참여가 현재로써는 더 큰 경험이 될 가능성 높음
6. Figma로 발표자료 만들었는데 굉장히 깔끔하게 만들어짐 앞으로 활용해도 좋을 듯
