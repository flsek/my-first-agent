# my-first-agent

OpenAI API를 사용한 간단한 AI 에이전트 프로젝트입니다.

## 설치

이 프로젝트는 Python 3.13 이상이 필요합니다.

```bash
# uv를 사용하여 의존성 설치
uv sync
```

## 환경 설정

`.env` 파일을 생성하고 OpenAI API 키를 설정하세요:

```
OPENAI_API_KEY=your_api_key_here
```

## 사용법

### Python 스크립트 실행

```bash
python main.py
```

### Jupyter Notebook 실행

```bash
jupyter notebook main.ipynb
```

또는 VS Code에서 Jupyter 확장을 사용하여 `main.ipynb`를 열어 실행할 수 있습니다.

## 프로젝트 구조

- `main.py`: 기본 Python 스크립트
- `main.ipynb`: OpenAI API 사용 예제가 포함된 Jupyter Notebook
- `pyproject.toml`: 프로젝트 의존성 및 설정
- `.env`: 환경 변수 (API 키 등)

## 의존성

- `openai>=2.0.0`: OpenAI API 클라이언트
- `ipykernel>=6.30.0`: Jupyter Notebook 지원 (개발 의존성)
