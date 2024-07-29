# 方法一把pm2.sh文件放在根目录用./pm2.sh命令运行或使用
（mkdir -p ~/.npm-global && npm config set prefix '~/.npm-global' && echo 'export PATH=~/.npm-global/bin:$PATH' >> ~/.bashrc && source ~/.bashrc && npm install -g pm2）  运行
# 方法二 下载Files.zip上传到根目录并解压再次使用
mkdir -p ~/.npm-global && npm config set prefix '~/.npm-global' && echo 'export PATH=~/.npm-global/bin:$PATH' >> ~/.bashrc && source ~/.bashrc && npm install -g pm2 即可
# 注意方法二保证目录里没有.pm2和.npm-global文件如果有请删除
