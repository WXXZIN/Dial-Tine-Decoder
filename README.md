# Dial Tone Decoder

## 📝 개요

이 프로젝트는 전화기의 다이얼 톤을 디코딩하는 기능을 제공합니다. 주어진 `wav` 파일에서 DTMF(이중 톤 다중 주파수) 신호를 분석하여 다이얼된 숫자들을 출력합니다. 이를 통해, 다이얼 톤을 쉽게 디코딩하고 번호를 추출할 수 있습니다.

## 🛠 기술 스택

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

## 💻 실행 방법

### 1. **설치**

먼저 이 프로젝트를 로컬에 클론하고 필요한 라이브러리들을 설치합니다.

```bash
$ git clone https://github.com/WXXZIN/Dial-Tone-Decoder.git
$ cd Dial-Tone-Decoder
$ pip install numpy scipy ipython matplotlib dtmf-decoder
```
<br />

### 2. **wav 파일 준비**
다이얼 톤을 포함하는 wav 파일을 프로젝트 디렉토리에 위치시킵니다. 예시 파일 이름은 dial-tone.wav로 설정해두었으므로, 동일한 경로에 파일을 배치해주세요.

<br />

### 3. **프로젝트 열기**
Google Colab, Jupyter Notebook, VS Code를 사용하여 프로젝트를 엽니다.

<br />

### 4. **프로젝트 실행**
dial_tone_decoder.ipynb 파일을 열고 각 셀을 순차적으로 실행하여 다이얼 톤을 디코딩합니다.

<br />

### 5. **결과 확인**
```bash
Decoded Numbers: 0 5 4 6 4 2 7 3 1 6
```
