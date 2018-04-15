# How to setup virtual Env

Install Pip

```
sudo apt-get install python-pip
```

Install virtualenv

```
sudo pip install virtualenv
```

Create a dir to store your virtualenvs (I use ~/.virtualenvs)

```
mkdir ~/.virtualenvs
```

Install virtualenvwrapper

```
sudo pip install virtualenvwrapper
```

Add below command to .basrc or .zsh file
To open bashrc file use ``` vim ~/.bashrc``` this command

```
export WORKON_HOME=~/.virtualenvs
```
```
. /usr/local/bin/virtualenvwrapper.sh
```
Create a new virtualenv using
```
mkproject PROJECT NAME
```
To start virtualenv or switch between environment use
```
workon PROJECT NAME
```

