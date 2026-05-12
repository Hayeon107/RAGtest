## 1. 설치
1-1. 파이썬 설치 (https://www.python.org/) *설치 후 powershell에서 확인

1-2. VSCode 설치 (https://code.visualstudio.com/Download)

1-2-1. 파이썬, 주피터 extention 설치

1-2-2. gitbash 설치 (https://git-scm.com/install/windows)

## 2. 깃허브 VSCODE 연동

2-1. git에서 사용할 폴더 선택 : cd c:\RAGtest

2-2. git 초기화 : git init

2-3. git 연동 

: git config --global user.email "khappy616@gmail.com"

git config --global user.name "Hayeon107"

2-4. VSCODE에서 F1 > git clone > 레포선택

## 3. 가상환경 세팅
3-1. 주피터 세팅 :
python -m venv venv #venv 폴더에 가상환경 생성
.\venv\Scripts\Activate.ps1 #powershell 활성화
python -m pip install --upgrade pip

3-2. 주피터 설치 : python -m pip install notebook ipykernel

3-3. 인터프리터 연결 : Ctrl + shift + P -> Python: Select Interpreter -> RAGTEST/venv 안의 python 선택

## 4. 필요라이브러리 설치

4-1. 랭체인 : python -m pip install langchain openai langchain-community faiss-cpu python-dotenv PyPDF2 tiktoken
