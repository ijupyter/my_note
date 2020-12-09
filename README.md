# my_note
用powershell作为conda环境:

以管理员身份运行PowerShell

执行：`set-ExecutionPolicy RemoteSigned`

执行：`conda init powershell`

npm install -g cnpm --registry=https://registry.npm.taobao.org
npm config set registry https://registry.npm.taobao.org
npm config set electron_mirror="https://npm.taobao.org/mirrors/electron/"
npm config set ignore-engines true

custom-electron-titlebar

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple pip -U
pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/ 
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/ 
conda config --set show_channel_urls yes
