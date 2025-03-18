# installation_Python

## Python 개발 환경 구축 가이드

1️⃣ Anaconda 설치하기

Anaconda 공식 사이트(https://www.anaconda.com/download)에서 최신 버전 다운로드

설치 진행 후, "Add Anaconda to PATH" 체크!

터미널에서 설치 확인:
conda --version
-------------------------------------------------
2️⃣ VS Code 설치하기

VS Code 공식 사이트(https://code.visualstudio.com/download)에서 다운로드 후 설치

설치 후 터미널에서 실행 확인:
code --version

3️⃣ 가상환경 설정할 파일 만들기

1. 원하는 프로젝트 폴더 생성
mkdir C:\2025_AI\myfirst && cd C:\2025_AI\myfirst

2. Anaconda 가상환경 생성
conda create -n myfirst python=3.11
주석: 콘다로 가상환경을 만들건데 이름은 myfirst이고 파이썬 버전은 3.11이다.

3. 가상환경 활성화
conda activate myfirst

4. 가상환경 비활성화
conda deactivate

4️⃣ VS Code에서 hello.py 파일 만들기

1. 탐색기에서 myfirst 폴더를 찾아 마우스 우클릭 → "VS Code에서 열기" 선택

2. hello.py 파일을 생성하고 아래 코드 작성
print("Hello, Python!")

3. 실행 확인:
python hello.py

4. VS Code확장 프로그램 설치 (Python & CodeSnap)

✅ Python 확장 프로그램
- VS Code 좌측 Extensions (Ctrl + Shift + X)에서 Python 검색 후 설치

✅ CodeSnap 확장 프로그램
- CodeSnap 검색 후 설치
- 코드를 보기 좋게 캡처할 수 있고, 레포트등 소스 코드를 옮겨서 작성할 때 유용함

### 가상 환경
- 가상 환경은 왜 사용하는가?
  - 가상환경을 사용하면 프로젝트별로 독립적인 환경을 유지하면서 의존성 문제 없이 깔끔한 개발을 할 수 있도록 도와줌.

5️⃣ 
