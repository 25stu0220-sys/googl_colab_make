# googl_colab_make# 🧠 구글 코랩 완전 가이드 (Google Colab Complete Guide)

> 설치 없이 GPU까지 돌릴 수 있는 클라우드 기반 Python 노트북 환경, **Google Colaboratory**를 쉽고 빠르게 마스터해보세요!

---

## 📌 목차

| No | 주제 | 설명 |
|----|------|------|
| 1 | [Colab이란?](#colab이란) | Colab 소개와 특징 |
| 2 | [시작하기](#시작하기) | Colab 사용 전 준비 사항 |
| 3 | [기능 요약](#기능-요약-표) | 주요 기능 표로 정리 |
| 4 | [자주 쓰는 코드](#자주-쓰는-코드-예시) | 실전 코드 예시 |
| 5 | [단축키 & 팁](#단축키--팁) | 유용한 단축키 모음 |
| 6 | [FAQ](#faq) | 자주 묻는 질문 정리 |

---

## 💡 Colab이란?

| 항목 | 내용 |
|------|------|
| 개발사 | Google |
| 실행 환경 | 웹 브라우저 (Chrome 권장) |
| 언어 지원 | Python (기본), R도 가능 |
| 저장 방식 | Google Drive 연동 |
| 하드웨어 | CPU / GPU / TPU 선택 가능 |
| 파일 형식 | `.ipynb` (Jupyter Notebook 동일) |

---

## 🚀 시작하기

| 단계 | 설명 |
|------|------|
| 1단계 | 접속: [colab.research.google.com](https://colab.research.google.com) |
| 2단계 | 새 노트북 생성 (`파일 → 새 노트북`) |
| 3단계 | 런타임 설정 (`런타임 → 런타임 유형 변경`) |
| 4단계 | 저장: Google Drive에 자동 저장 |

---

## ⚙️ 기능 요약 표

| 기능 | 설명 | 코드 예시 |
|------|------|-----------|
| Google Drive 연결 | 내 드라이브 데이터 사용 | `drive.mount('/content/drive')` |
| 외부 파일 업로드 | 로컬 파일 올리기 | `files.upload()` |
| GPU 사용 | 빠른 연산 처리 | 런타임 설정에서 GPU 선택 |
| 셸 명령어 실행 | 리눅스 명령어 사용 | `!ls`, `!pip install` |
| 시각화 | 그래프 출력 | `matplotlib`, `seaborn` 사용 가능 |
| Markdown 문서화 | 설명 추가 | 텍스트 셀에 Markdown 작성 |

---

## 📦 자주 쓰는 코드 예시

| 목적 | 코드 |
|------|------|
| 드라이브 마운트 | `from google.colab import drive`<br>`drive.mount('/content/drive')` |
| 파일 업로드 | `from google.colab import files`<br>`files.upload()` |
| 패키지 설치 | `!pip install 패키지명` |
| 셸 명령어 | `!ls`, `!pwd`, `!nvidia-smi` |
| 시간 측정 | `%time`, `%timeit` |
| 한글 폰트 설정 (matplotlib) | `matplotlib.font_manager` 이용 |

---

## ⌨️ 단축키 & 팁

| 단축키 | 기능 |
|--------|------|
| `Ctrl + Enter` | 현재 셀 실행 |
| `Shift + Enter` | 현재 셀 실행 후 다음 셀로 이동 |
| `Ctrl + M B` | 아래에 새 코드 셀 삽입 |
| `Ctrl + M M` | 셀을 마크다운 셀로 전환 |
| `%load_ext autoreload` | 자동 코드 반영 |
| `!rm -rf 경로` | 파일/폴더 삭제 |

---

## ❓ FAQ

| 질문 | 답변 |
|------|------|
| Colab은 무료인가요? | 기본은 무료. Colab Pro(유료)도 있음 |
| GPU는 얼마나 쓸 수 있나요? | 무료 기준 하루 12시간 내외 (변동 가능) |
| 세션이 자꾸 꺼져요 | 일정 시간 미사용 시 자동 종료됨 (백업 필수) |
| 데이터를 어디 저장하나요? | Google Drive 또는 로컬 다운로드 |
| GitHub 노트북 여는 법은? | `파일 → GitHub에서 열기` 이용 |

---

## 📚 참고자료

- [Google Colab 공식 페이지](https://colab.research.google.com)
- [Colab 사용자 FAQ](https://research.google.com/colaboratory/faq.html)
- [Jupyter Notebook 소개](https://jupyter.org/)
- [파이썬 공식 문서](https://docs.python.org/3/)

---

> 🛠 이 문서는 지속적으로 업데이트됩니다. 개선 제안은 Pull Request 또는 Issue로 남겨주세요!
