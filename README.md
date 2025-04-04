# Rockyou.txt wordlist
```bash
scp -P 5000 clara@venus.hackmyvm.eu:~/protected.zip ~/
39YziWp5gSvgQN9

sudo apt install build-essential libncurses-dev bison flex libssl-dev libelf-dev dpkg-dev debhelper bc rsync kmod cpio

git clone https://github.com/openwall/john
cd john/src
nproc
./configure && make -j  

./zip2john protected.zip > pass
./john pass --wordlist=rockyou.txt
