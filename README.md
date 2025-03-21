# installation_Python

## Python 개발 환경 구축 가이드

1️⃣ Anaconda 설치하기

Anaconda 공식 사이트(https://www.anaconda.com/download)에서 최신 버전 다운로드

설치 진행 후, "Add Anaconda to PATH" 체크!
![image](https://github.com/user-attachments/assets/5e621e1c-ed01-4ee6-b9dc-61d78d32e2d0)

터미널에서 설치 확인:
conda --version

----------------------------------------------------------------------------------------------------------------------------------------------------------

2️⃣ VS Code 설치하기

VS Code 공식 사이트(https://code.visualstudio.com/download)에서 다운로드 후 설치
![image](https://github.com/user-attachments/assets/3834e51e-912d-4b22-894d-00258ab41ee8)

설치 후 터미널에서 실행 확인:
code --version

----------------------------------------------------------------------------------------------------------------------------------------------------------

3️⃣ 가상환경 설정할 파일 만들기

1. 원하는 프로젝트 폴더 생성
mkdir C:\2025_AI\myfirst && cd C:\2025_AI\myfirst

2. Anaconda 가상환경 생성
conda create -n myfirst python=3.11
주석: 콘다로 가상환경을 만들건데 이름은 myfirst이고 파이썬 버전은 3.11이다.

아래 코드로 콘다 가상환경 확인
  - python --version
  - conda --version
  - conda env list
  - pip list 
![image](https://github.com/user-attachments/assets/0bdf01f3-4695-48a3-b744-19e5c61245fd)

3. 가상환경 활성화
conda activate myfirst

4. 가상환경 비활성화
conda deactivate

✅ VS Code에서 가상환경 인터프리터 설정

  1. VS Code에서 Ctrl + Shift + P를 눌러 Command Palette 실행
  2. "Python: Select Interpreter" 검색 후 선택
  3. 리스트에서 conda 가상환경 중 myfirst 선택
  4. 터미널에서 python --version 입력 후, 가상환경의 Python이 정상적으로 설정되었는지 확인
  5. ctrl+shift+'~'를 눌러 새 터미널 창을 열고 (myfirst)라는 가상 환경이 표기 되면 정상
     ![image](https://github.com/user-attachments/assets/e9e122ac-ff2b-41a8-aa5f-449bf2f95dc1)

----------------------------------------------------------------------------------------------------------------------------------------------------------

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

----------------------------------------------------------------------------------------------------------------------------------------------------------

5️⃣ 주소록 만들기 프로젝트
[진행 과정]

1. GPT에게 의뢰
  - GPT에게 만들고자 하는 프로그램에 대해 간단히 설명하고, 사용할 라이브러리(PyQt 등)를 정함.

2. GPT가 제공한 코드 실행
  - VS Code에서 C:\2025_AI\myfirst\addressBook.py 파일을 생성하고 GPT가 제공한 코드를 복사하여 붙여넣기.
  - 실행 (python addressBook.py) 후 오류 발생 예상.

3. 오류 해결 과정
  - 발생한 오류 메시지를 복사하여 다시 GPT에게 질문.
  - GPT가 수정된 코드를 제공하면 기존 코드 수정 후 재실행.

4. 최종 실행 및 검토
  - 코드가 정상적으로 실행되면, 기능 테스트 진행.
  - 필요 시 GPT를 활용하여 추가 기능 개선.

[목적]
생성형 AI(GPT)를 활용한 프로그램 개발이 얼마나 용이한지 검토
PyQt 사용 이유: 필요한 패키지를 선택하고 설치하는 과정을 경험하기 위함

