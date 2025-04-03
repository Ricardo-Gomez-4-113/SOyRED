# SO
```bash
scp -P 5000 clara@venus.hackmyvm.eu:~/protected.zip ~/
39YziWp5gSvgQN9

git clone https://github.com/openwall/john
cd john/src
./configure && make

./zip2john protected.zip > pass
john pass --wordlist=rockyou.txt
