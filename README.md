Install manually

Update your package index

1) sudo apt update

2) sudo apt install curl -y

3) curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -

4) sudo apt install -y nodejs 

install PM2 globally
*) sudo npm install -g pm2

install the panel
1) git clone https://github.com/jihannetwork2204/dev.center

2) cd dev.center

3) npm install 

4) pm2 start ecosystem.config.cjs 

restart the panel
cmd :   pm2 restart all


direct install cmd :
