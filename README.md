# 🇰🇷 Korean CSAT-Math Benchmark for LLMs

[![LICENSE](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

대규모 언어 모델(LLM)의 한국 대학수학능력시험(CSAT) 수학 영역에 대한 문제 해결 능력을 평가하기 위한 벤치마크 데이터셋 및 평가 도구 모음입니다. 🧠

이 프로젝트는 LLM의 복합적인 추론, 수리 능력 및 한국어 이해 능력을 종합적으로 측정하는 것을 목표로 합니다.

## 🚀 시작하기 (Getting Started)

1.  **저장소 복제:**
    ```bash
    git clone [https://github.com/your-username/korean-csat-math-benchmark.git](https://github.com/your-username/korean-csat-math-benchmark.git)
    cd korean-csat-math-benchmark
    ```

2.  **필요한 라이브러리 설치:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **예제 노트북 실행:**
    `notebooks/getting_started.ipynb` 파일을 통해 데이터 로드부터 평가 실행까지의 기본적인 사용법을 확인하실 수 있습니다.

## 📂 디렉토리 구조
```bash
korean-csat-math-benchmark/
├── data/              # 연도별 수능 수학 문제 데이터 (JSON, Images)
├── src/               # 평가 실행을 위한 소스 코드
├── results/           # 모델별 평가 결과
├── notebooks/         # 사용법을 안내하는 주피터 노트북
├── .gitignore         # Git 추적 제외 파일 목록
├── LICENSE            # 프로젝트 라이선스
├── README.md          # 프로젝트 설명 (현재 파일)
├── requirements.txt   # 파이썬 의존성 목록
└── LEADERBOARD.md     # 모델별 성능 순위 리더보드
```

## 📊 리더보드 (Leaderboard)

주요 LLM들의 평가 결과는 [LEADERBOARD.md](LEADERBOARD.md) 파일에서 확인하실 수 있습니다.

## 🤝 기여하기 (Contributing)

이 프로젝트는 언제나 여러분의 기여를 환영합니다! 문제 데이터의 오류 수정, 새로운 연도 데이터 추가, 평가 스크립트 개선 등 어떤 형태의 기여든 좋습니다. 자세한 내용은 `CONTRIBUTING.md`(추가 예정) 파일을 참고해 주세요.

## 📜 라이선스 (License)

이 프로젝트는 [MIT License](LICENSE)를 따릅니다.