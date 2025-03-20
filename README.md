# LLM_Study_Notes_AI_Applications

- 본 저장소는 "LLM을 활용한 실전 AI 애플리케이션 개발" 책을 학습하며 정리한 내용과 실습 코드를 담고 있습니다.

## 📚 소개
- 대규모 언어 모델(LLM)을 활용한 AI 애플리케이션 개발에 관한 학습 과정을 기록하고, 책에서 배운 개념과 기술을 실제로 구현해 본 코드를 공유합니다. 이 저장소는 개인 학습 목적으로 만들어졌으며, 같은 주제에 관심 있는 분들과 지식을 나누고자 합니다.

## 🔍 학습 내용

- **LLM 기초 개념**: 대규모 언어 모델의 원리와 특징
- **프롬프트 엔지니어링**: 효과적인 프롬프트 작성 방법과 실험 결과
- **RAG(Retrieval-Augmented Generation)**: 외부 지식 검색 기반 생성 모델 구현
- **파인튜닝 실험**: 간단한 파인튜닝 실습과 결과 분석
- **프로젝트 실습**: 책의 예제를 기반으로 직접 구현한 미니 프로젝트

## 📂 저장소 구조
복사LLM_Study_Notes_AI_Applications/
├── code/
│   ├── basic_examples/
├── notebooks/
│   ├── 01_openai_api_basics.ipynb
├── resources/
│   ├── useful_links.md
│   └── datasets/
├── requirements.txt
└── README.md

## ⚙️ 실행 환경 설정

1. 저장소 클론:

```bash복사git clone https://github.com/your-username/LLM-Study-Notes.git
cd LLM-Study-Notes
```

2. 가상 환경 생성 및 활성화:

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

필요한 패키지 설치:

```bash
pip install -r requirements.txt
```

## 🔑 API 키 설정
- 일부 코드는 OpenAI API 등의 API 키가 필요합니다. 다음과 같이 환경 변수를 설정하세요:

```bash
# .env 파일 생성
echo "OPENAI_API_KEY=your_api_key_here" > .env
```

## 📖 참고 도서
- 이 학습 노트는 다음 도서를 바탕으로 작성되었습니다:

- 제목: "LLM을 활용한 실전 AI 애플리케이션 개발"
- 저자: 허정준
- 출판사: (주)책만

- 원저작자와 출판사의 저작권을 존중합니다. 이 저장소는 개인 학습 목적으로 만들어졌으며, 책의 내용을 직접적으로 복제하지 않고 학습 과정과 개인적인 실험 결과를 담고 있습니다.

## ⚠️ 주의사항

- 이 저장소의 코드와 노트는 개인 학습 용도로 작성되었습니다. 모든 실험과 구현은 원 도서를 바탕으로 한 개인적인 해석과 확장입니다. 상업적 목적으로 사용하지 마세요.

## 📝 학습 일지

- 진행 중...

## 🤝 피드백 환영
- 오류 수정, 개선 제안 또는 질문이 있으시면 이슈를 열어주세요. 함께 배우고 성장하는 과정을 공유하고 싶습니다.

---

작성한 날짜 : 2025.03.20 (목)

마지막 업데이트 : 2025.03.20 (목)
