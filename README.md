# installation_Python

## Python 개발 환경 구축 가이드

1️⃣ Anaconda 설치하기

Anaconda 공식 사이트에서 최신 버전 다운로드

설치 진행 후, "Add Anaconda to PATH" 체크!

터미널에서 설치 확인:

conda --version

2️⃣ VS Code 설치하기

VS Code 공식 사이트에서 다운로드 후 설치

설치 후 터미널에서 실행 확인:

code --version

3️⃣ 가상환경 설정할 파일 만들기

원하는 프로젝트 폴더 생성

mkdir my_project && cd my_project

Anaconda 가상환경 생성

conda create -n myenv python=3.11

가상환경 활성화

conda activate myenv

4️⃣ VS Code에서 hello.py 파일 만들기

탐색기에서 my_project 폴더를 찾아 마우스 우클릭 → "VS Code에서 열기" 선택

hello.py 파일을 생성하고 아래 코드 작성

print("Hello, Python!")

실행 확인:

python hello.py

5️⃣ 확장 프로그램 설치 (Python & CodeSnap)

✅ Python 확장 프로그램

VS Code 좌측 Extensions (Ctrl + Shift + X)에서 Python 검색 후 설치

✅ CodeSnap 확장 프로그램

CodeSnap 검색 후 설치

코드 스니펫을 예쁘게 캡처할 수 있어, 레포트 작성 시 유용

