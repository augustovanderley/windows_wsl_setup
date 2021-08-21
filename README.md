# windows_wsl_setup
How to start the setup the wsl in linux with vscode and python


# Install Ubuntu distro in microsoft Store

sudo apt update
sudo apt upgrade

# Install Docker 
https://docs.docker.com/desktop/windows/wsl/

# Fix Permission Denied in docker
https://stackoverflow.com/questions/48957195/how-to-fix-docker-got-permission-denied-issue



# [Optional] Install WSL 2 with oh my zsh
https://nickymeuleman.netlify.app/blog/linux-on-windows-wsl2-zsh-docker



# Install pyenv


sudo apt-get update; sudo apt-get install make build-essential libssl-dev zlib1g-dev \
libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm \
libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev

git clone https://github.com/pyenv/pyenv.git ~/.pyenv

Add to .bashrc: 
export PYENV_ROOT="$HOME/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init --path)"

https://github.com/pyenv/pyenv
https://www.liquidweb.com/kb/how-to-install-pyenv-on-ubuntu-18-04/


# install python and libs

pyenv install 3.8.10
pyenv global 3.8.10

pip install --upgrade pip
pip install ipython

