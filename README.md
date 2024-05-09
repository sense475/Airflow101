# install python
## install pyenv (python version controll)

for MacOS using brew

```
brew update
```
```
brew install ncurses
```
```
brew install pyenv
```

```
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc
echo '[[ -d $PYENV_ROOT/bin ]] && export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(pyenv init -)"' >> ~/.zshrc

```

or add this to .zshrc
```
export PYENV_ROOT="$HOME/.pyenv"
[[ -d $PYENV_ROOT/bin ]] && export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init -)"
```

and install python 3.12.3
```
pyenv install 3.12
```

cd to this directory and use this 
```
pyenv local 3.12
```
