# Near Hot Auto Claim Daily On Via VPS
```
sudo apt update && sudo apt install -y git && sudo apt install -y screen
```
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash \
&& source ~/.bashrc \
&& nvm install 20.10.0 \
&& nvm use 20.10.0 \
&& sudo apt install npm -y
```
```
git clone https://github.com/0xlucyg/hot-wallet-auto-claim
cd hot-wallet-auto-claim
```

Open File Private.txt Ganti Private Key Dengan Private Key Kalian | username.tg Ganti dengan Username Wallet Near Hot Kalian
```
screen -S hot

node index.js
```
CTRL A D (Save Screen)

back to Screen 
```
screen -r hot
```
