# Streamlit 간단 정수 계산기

Streamlit을 활용하여 두 정수와 연산자를 입력받아 결과를 출력하는 간단한 웹 기반 계산기 애플리케이션입니다.

## 주요 기능
- **입력**: 첫 번째 정수, 연산자(+, -, *, /), 두 번째 정수를 각각 한 줄씩 입력
- **예외 처리**:
  - 정수가 아닌 값 입력 시 오류 메시지 출력
  - +, -, *, / 외의 연산자 입력 시 오류 메시지 출력
  - 0으로 나누기 시 오류 메시지 출력
- **결과 출력**: 계산 결과를 화면 하단에 표시

---

## 실행 방법

### 1. 가상환경 설정 (선택 사항)
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

### 2. 패키지 설치
`requirements.txt` 파일에 정의된 라이브러리를 설치합니다.
```bash
pip install -r requirements.txt
```

### 3. Streamlit 앱 실행
```bash
streamlit run app.py
```
*(기본 파일명이 `app.py`가 아닌 경우 해당 파이썬 파일명으로 변경하여 실행하세요.)*

---

## 프로젝트 구조
```text
.
├── app.py           # Streamlit 계산기 메인 코드
├── requirements.txt # 필요 라이브러리 목록
└── README.md        # 프로젝트 설명 문서
```