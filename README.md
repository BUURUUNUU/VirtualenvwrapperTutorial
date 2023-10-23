**How to install and use virtualenvwrapper on Ubuntu**

1 - Go to home directory

2 - Open terminal on home directory

3 - Run on terminal

```
mkdir .virtualenv
```

4 - Run on terminal

```
sudo apt install python3-pip
```

5 - Run on terminal

```
pip3 install virtualenv
```

6 - Run on terminal

```
which virtualenv
```

7 - Run on terminal

```
pip3 install virtualenvwrapper
```

8 - Run on terminal

```
sudo apt install vim
```

9 - Run on terminal

```
vim ~/.bashrc
```

10 - Press `i` to edit the file

11 - Scroll to the botton on the file

12 - Paste on ~/.bashrc `DONT FORGET TO CHANGE "YOUR USERNAME HERE"`

```
#Virtualenvwrapper settings:
export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3
export WORKON_HOME=$HOME/.virtualenvs
export VIRTUALENVWRAPPER_VIRTUALENV=/home/"YOUR USERNAME HERE"/.local/bin/virtualenv
source ~/.local/bin/virtualenvwrapper.sh
```

13 - Press `ESC`

14 - Type `:wq`

15 - Press `Enter`

16 - Run on terminal

```
source ~/.bashrc
```

17 - To create an Venv Run on terminal

```
mkvirtualenv 'VENV NAME HERE'
```

18 - Deactivate the Venv

```
deactivate
```

19 - List all Venvs

```
lsvirtualenv
```

20 - Activate Venv

```
workon 'VENV NAME HERE'
```
