# This repository is for the BASH/ZSH terminal alias config. 
### This has predefined alias for terminal configs. You'll find the list of command aliasses below


bash = sudo nano ~/.bashrc
zshconfig = mate ~/.zshrc
reso = source ~/.bashrc
zsh = nano ~/.zshrc
soz = source ~/.zshrc

mk = makepkg -si
ls = ls --color=auto
grep = grep --color=auto
l = ls -l
cod = codium
h = history
c = clear
move = mv -i
mkcd = function _mkcd() { mkdir -p "$1" && cd "$1"; }; _mkcd

ohmyzsh = mate ~/.oh-my-zsh

nrun = npm run dev
ydev = yarn dev
nin = npm install
ydev = yarn dev

pain = sudo pacman -Sy
parm = sudo pacman -Rs
paup = sudo pacman -Syu

coac = conda activate
coin = conda install
nv = nvidia-smi
coadd = conda config --add channels
corm = conda remove -n
coincf = conda install -c condaforge::

cogy = conda activate GymGPU
coto = conda activate PytorchGPU

cod = codium
dbs = pg_ctl -D /var/lib/postgres/data -l logfile start
dops = docker ps -l
dos = docker start
mvin = mvn clean install -DskipTests
sshos = ssh -oHostKeyAlgorithms=+ssh-rsa -i $1 root@$2
newapp = bunx --bun create-next-app@latest $1 --typescript --tailwind --eslint

documents = cd /Users/ar/Documents
downloads = /Users/ar/Downloads
desktop = /Users/ar/Desktop
