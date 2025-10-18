# 타이타닉 데이터 분석을 통한 20세기 초 세계사 탐구 프로젝트

## 1. 프로젝트 개요

본 프로젝트는 타이타닉 호의 승객 데이터를 분석하여 20세기 초의 사회 구조, 경제 상황, 국가 간의 관계 등 세계사적 맥락을 탐구하는 것을 목표로 합니다. 데이터 분석 결과를 바탕으로 WordMCP를 사용해 Word 보고서를 작성하여 학교 과제(과세특)로 제출하는 것을 최종 목표로 합니다.

## 2. 사용 데이터

- **`sns.load_dataset('titanic')`**: 타이타닉 호 승객들의 정보를 담고 있는 데이터 파일입니다.
  - 주요 데이터 항목: 승객 등급(Pclass), 성별(Sex), 나이(Age), 탑승 항구(Embarked), 요금(Fare), 생존 여부(Survived) 등

## 3. 분석 내용 및 방법

- **분석 도구**: `main.ipynb` Jupyter Notebook 파일에서 Python을 사용하여 데이터 분석을 수행합니다.
- **주요 라이브러리**: `pandas`, `numpy`, `matplotlib`, `seaborn` 등을 사용하여 데이터를 처리하고 시각화합니다.
- **분석 관점**:
  - 승객의 사회적 계급(Pclass)과 생존율의 관계를 통해 당시의 계급 사회를 조명합니다.
  - 국적 또는 탑승 항구(Embarked)에 따른 생존율 차이를 분석하여 국가 간의 위상 및 관계를 추론합니다.
  - 연령대 및 성별에 따른 생존율 분석을 통해 당시의 사회적 통념과 가치관을 탐구합니다.

## 4. 최종 산출물

- **Word 보고서**: 데이터 분석 결과를 종합하여 '타이타닉 데이터로 본 20세기 초의 세계'라는 주제의 보고서를 작성합니다. 이 과정에서 Word MCP를 활용하여 보고서 생성을 자동화하고 체계적으로 구성합니다.

## 5. 프로젝트 실행 방법

1.  **저장소 복제**
    ```bash
    git clone https://github.com/An0jin/Titanic.git
    cd Titanic
    ```

2.  **필요한 라이브러리 설치**
    ```bash
    pip install pandas numpy matplotlib seaborn openpyxl
    ```

3.  **Jupyter Notebook 실행**
    ```bash
    jupyter notebook main.ipynb
    ```

## 6. 파일 구조

```
. (root)
├── main.ipynb       # 데이터 분석 및 시각화를 위한 Jupyter Notebook
└── README.md        # 프로젝트 설명 파일
```
타이타닉 데이터 분석으로 세계사 세특 쓰기
