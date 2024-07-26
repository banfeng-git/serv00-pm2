# serv00-pm2 复制以下命令就可以在serv00安装pm2
mkdir -p ~/.npm-global && npm config set prefix '~/.npm-global' && echo 'export PATH=~/.npm-global/bin:$PATH' >> ~/.bashrc && source ~/.bashrc && npm install -g pm2
echo "请使用 ~/.npm-global/bin/pm2 来调用pm2"
