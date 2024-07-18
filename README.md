# This repository is for the BASH/ZSH terminal alias config. 
### This has predefined alias for terminal configs. You'll find the list of command aliasses below

### DEFAULT LOAD PRINT
echo Current working dir
pwd

### TERMINAL CONFIG
bash = sudo nano ~/.bashrc
zshconfig = mate ~/.zshrc
reso = source ~/.bashrc
zsh = nano ~/.zshrc
soz = source ~/.zshrc

### BASE LINUX 
mk = makepkg -si
ls = ls --color=auto
grep = grep --color=auto
l = ls -l
cod = codium
h = history
c = clear
move = mv -i
mkcd = function _mkcd() { mkdir -p "$1" && cd "$1"; }; _mkcd

### OH MY ZSH 
ohmyzsh = mate ~/.oh-my-zsh

### NPM-YERN-BUN
nrun = npm run dev
ydev = yarn dev
nin = npm install
ydev = yarn dev

### ARCH LINUX 
pain = sudo pacman -Sy
parm = sudo pacman -Rs
paup = sudo pacman -Syu

### CONDA - ML
coac = conda activate
coin = conda install
nv = nvidia-smi
coadd = conda config --add channels
corm = conda remove -n
coincf = conda install -c condaforge::

### CONDA - KERNEL SPECIFIC
cogy = conda activate GymGPU
coto = conda activate PytorchGPU

### APPLICATIONS 
cod = codium
dbs = pg_ctl -D /var/lib/postgres/data -l logfile start
dops = docker ps -l
dos = docker start
mvin = mvn clean install -DskipTests
sshos = ssh -oHostKeyAlgorithms=+ssh-rsa -i $1 root@$2
newapp = bunx --bun create-next-app@latest $1 --typescript --tailwind --eslint

### Folder 
documents = cd /Users/ar/Documents
downloads = /Users/ar/Downloads
desktop = /Users/ar/Desktop
