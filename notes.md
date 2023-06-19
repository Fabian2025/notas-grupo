# <font color = #00FFFF size=6 face="STCAIYUN">SETEAR ENVIROMENT CON VERSION DE PYTHON EN WINDOWS </font>
* python -m pip install --upgrade pip
* Install virtualenv "pip install virtualenv"
* virtualenv -p 3.8.8 "nombredelentornovirtual" -> si no funciona este intentar con el siguiente
* python -m virtualenv -p "python version" "virtual environment name"

# <font color = #00FFFF size=6 face="STCAIYUN">SETEAR ENVIROMENT CON VERSION DE PYTHON EN UBUNTU </font>
* Install virtualenv "pip install virtualenv"
* sudo apt install python3.8-venv
* virtualenv -p 3.8.8 "nombredelentornovirtual" -> si no funciona este intentar con el siguiente
* python -m virtualenv -p "python version" "virtual environment name"

# <font color = #00FFFF size=6 face="STCAIYUN">CAMBIAR DE TERMINAL EN VSCODE </font>
* CTRL + SHIFT + P
* Terminal: Select Default Profile
* Select the terminal you want

# <font color = #00FFFF size=6 face="STCAIYUN">CAMBIAR DE AMBIENTE </font>
* CTRL + SHIFT + P
* Python: Select Interpreter
* Select the environment you want

# <font color = #00FFFF size=6 face="STCAIYUN">INSTALAR PYTHON EN UBUNTU </font>
## actualizar repositorios
* sudo apt-get install software-properties-common
* sudo add-apt-repository ppa:deadsnakes/ppa
* sudo apt update
## instalar python 3.8
* sudo apt install python3.8
## instalar pip
* sudo apt install python3-pip

# <font color = #00FFFF size=6 face="STCAIYUN">GENERAR LLAVE SSH PUBLIVA Y PRIVADA </font>
* ssh-keygen -t ed25519 -C "<comment>"
* https://docs.gitlab.com/ee/user/ssh.html
