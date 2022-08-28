Cd $HOME &&
Pkg upgrade -y &&
Pkg update -y &&
Pkg install git &&
Git clone https://github.com/MRRI04/MRRI04/
cd termux-config &&
sh ./install.sh
