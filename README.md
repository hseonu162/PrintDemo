<p align="center">
  <img src="https://raw.githubusercontent.com/willmcgugan/rich/master/imgs/logo.svg" alt="Rich Library Logo" width="250"/>
</p>

<h1 align="center"> 🐍 Python Terminal Output Masterclass 🎨</h1>

<p align="center">
  <strong>파이썬의 기본 <code>print()</code> 함수부터 터미널을 예술로 만드는 <code>rich</code> 라이브러리까지, 터미널 출력의 모든 것을 마스터하는 예제 프로젝트입니다.</strong>
</p>

<p align="center">
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/python-3.7%2B-blue?style=for-the-badge&logo=python" alt="Python Version"></a>
  <a href="https://github.com/willmcgugan/rich"><img src="https://img.shields.io/badge/built%20with-rich-ff69b4?style=for-the-badge&logo=python" alt="Built with Rich"></a>
  <a href="https://code.visualstudio.com/"><img src="https://img.shields.io/badge/IDE-VSCode-blueviolet?style=for-the-badge&logo=visualstudiocode" alt="IDE"></a>
</p>

---

## 📖 목차

1.  [**프로젝트 개요**](#-프로젝트-개요)
2.  [**핵심 학습 목표**](#-핵심-학습-목표)
3.  [**파일 상세 설명**](#-파일-상세-설명)
    -   [`main_print_v1.py`](#-main_print_v1py---기본-print-함수의-모든-것)
    -   [`main_print_v1.ipynb`](#-main_print_v1ipynb---인터랙티브-학습-노트북)
    -   [`main_print_v2.py`](#-main_print_v2py---rich-라이브러리로-터미널-꾸미기)
4.  [**프로젝트 설정 및 실행**](#-프로젝트-설정-및-실행)
    -   [사전 준비물](#-사전-준비물)
    -   [설치 및 실행 단계](#-설치-및-실행-단계)
5.  [**코드 심층 분석 및 결과**](#-코드-심층-분석-및-결과)
    -   [V1: 기본 `print()` 완전 정복](#v1-기본-print-완전-정복)
    -   [V2: `rich`로 만드는 화려한 출력](#v2-rich로-만드는-화려한-출력)

---

## 🚀 프로젝트 개요

이 프로젝트는 파이썬 개발의 가장 기본이 되는 **터미널 출력**을 주제로 합니다. 단순한 텍스트 출력에서 벗어나, 데이터를 효과적으로 표현하고, 가독성을 높이며, 시각적으로 아름다운 결과물을 만드는 방법을 단계별로 학습할 수 있도록 구성되었습니다.

-   **1단계:** 파이썬 내장 `print()` 함수의 숨겨진 기능까지 파헤쳐 봅니다.
-   **2단계:** 강력한 터미널 UI 라이브러리인 `rich`를 사용하여 CLI(Command Line Interface) 환경을 풍부하게 만드는 방법을 배웁니다.

---

## 🎯 핵심 학습 목표

-   다양한 포맷팅 방식(f-string, `.format()`, %-포맷팅)의 차이를 이해하고 상황에 맞게 사용합니다.
-   `print()` 함수의 `sep`, `end` 옵션을 활용하여 출력 형식을 자유자재로 제어합니다.
-   `rich` 라이브러리를 사용하여 텍스트에 색상과 스타일을 적용합니다.
-   `Panel`과 `Table` 객체를 활용하여 정보를 구조화하고 시각적으로 강조하는 방법을 익힙니다.

---

## 📂 파일 상세 설명

### 📄 `main_print_v1.py` - 기본 `print()` 함수의 모든 것

파이썬에 내장된 `print()` 함수의 핵심 기능과 다양한 활용법을 11가지 예제로 정리한 스크립트입니다. 변수 출력, 포맷팅, 옵션 제어 등 기본기를 다지는 데 최적화되어 있습니다.

### 📓 `main_print_v1.ipynb` - 인터랙티브 학습 노트북

`main_print_v1.py`와 100% 동일한 코드를 담고 있는 **Jupyter Notebook** 파일입니다. VSCode와 같은 환경에서 코드 셀을 하나씩 실행하며 각 라인의 출력 결과를 즉시 확인할 수 있어, 대화형 학습 및 코드 실험에 매우 유용합니다.

### 🎨 `main_print_v2.py` - `rich` 라이브러리로 터미널 꾸미기

단조로운 흑백 터미널을 화려하게 변신시키는 `rich` 라이브러리의 강력함을 보여주는 스크립트입니다. 이 파일을 통해 단순한 텍스트 출력이 어떻게 정보 전달력이 높은 시각적 결과물로 바뀔 수 있는지 경험할 수 있습니다.

---

## 🛠️ 프로젝트 설정 및 실행

### ✅ 사전 준비물

-   **Python** (버전 3.7 이상 권장)
-   **Visual Studio Code** (또는 다른 코드 에디터)
-   VSCode 사용자라면 **Python** 및 **Jupyter** 확장 프로그램 설치를 권장합니다.

### 👣 설치 및 실행 단계

1.  **프로젝트 다운로드 또는 복제 (Clone):**
    ```bash
    # (이 프로젝트가 Git 저장소에 있다면)
    # git clone <저장소_URL>
    # cd <프로젝트_폴더>
    ```

2.  **가상 환경 설정 (강력 추천):**
    프로젝트별로 독립된 개발 환경을 만들어 패키지 충돌을 방지합니다.
    ```bash
    # 가상 환경 생성
    python -m venv venv

    # 가상 환경 활성화
    # Windows
    venv\Scripts\activate
    # macOS / Linux
    source venv/bin/activate
    ```

3.  **의존성 패키지 설치 (`rich`):**
    `main_print_v2.py`를 실행하기 위해 `rich` 라이브러리를 설치합니다.
    ```bash
    pip install rich
    ```

4.  **스크립트 실행:**
    이제 각 파일을 터미널에서 실행할 수 있습니다.
    ```bash
    # 기본 print 예제 실행
    python main_print_v1.py

    # Rich 라이브러리 예제 실행
    python main_print_v2.py
    ```

---

## 🔬 코드 심층 분석 및 결과

### V1: 기본 `print()` 완전 정복

`main_print_v1.py`는 단순 출력부터 복잡한 포맷팅까지 `print` 함수의 핵심을 다룹니다. 특히 **f-string**은 Python 3.6부터 도입된 가장 현대적이고 강력한 문자열 포맷팅 방법입니다.

```python
# 예시: f-string 내에서 연산과 함수 호출
print(f"Next year age: {age + 1}")
print(f"Score (rounded): {round(score)}")