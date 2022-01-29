1. Go to https://github.com/pyenv/pyenv -> wiki
2. Install suggested build environment for ubuntu
3. Go to main page -> README.md -> Installation -> Automatic Installer -> https://github.com/pyenv/pyenv-installer
4. Follow instruction
5. Add to .bashrc:
export PATH="$HOME/.pyenv/bin:$PATH"
eval "$(pyenv init --path)"
eval "$(pyenv virtualenv-init -)"
6. exec $SHELL

