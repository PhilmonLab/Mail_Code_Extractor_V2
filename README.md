# Mail_Code_Extractor_V2
This is version 2 of the script. It creates a temporary GuerrillaMail address, watches the inbox, and when an email arrives it extracts the verification code and the verification link so you can copy them or open the link right away.


## Linux (Debian/Ubuntu)

cd cloned-project-folder

#### 1) System deps (Python + venv + Tkinter)
sudo apt update
sudo apt install -y python3 python3-venv python3-tk

#### 2) Create + activate venv 
python3 -m venv venv
> or//  python3 -m venv .venv    // if you want it to be hidden)
source  venv/bin/activate

#### 3) Install Python deps
python -m pip install -U pip
python -m pip install requests pyperclip

#### 4) Run
python3 run.py

#### To exit the venv

deactivate


## macOS

git clone ....

#### Install Python :https://www.python.org/downloads/

#### Install Tkinter
brew install tcl-tk

#### Create + activate venv
python3 -m venv venv
#### or: python3 -m venv .venv   # if you want it hidden
source venv/bin/activate
#### or: source .venv/bin/activate


#### Install Python deps
python -m pip install -U pip
python -m pip install requests pyperclip

#### Run
python3 run.py

#### To exit the venv
deactivate


## Windows

git clone 
cd cloned project folder

#### Install Python
https://www.python.org/downloads/windows/
#### During install: check “Add Python to PATH”

#### Create + activate venv (PowerShell)
py -m venv venv
#### or: py -m venv .venv   # if you want it hidden
.\venv\Scripts\Activate.ps1
#### or: .\.venv\Scripts\Activate.ps1

#### If activation is blocked:
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
.\venv\Scripts\Activate.ps1

#### Install Python deps
python -m pip install -U pip
python -m pip install requests pyperclip

#### Run
py run.py

#### To exit the venv
deactivate

<img width="704" height="607" alt="Screen" src="https://github.com/PhilmonLab/Mail_Code_Extractor_V2/blob/main/assets%20/pictures/code.png" />
<img width="704" height="607" alt="Screen" src="https://github.com/PhilmonLab/Mail_Code_Extractor_V2/blob/main/assets%20/pictures/code_2.png" />




