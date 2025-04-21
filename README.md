 MTProxy 安装指南
📦 第一步：克隆脚本到服务器
在终端中执行以下命令：
```
git clone https://github.com/xfy52/mtproxy.git
```

⚠️ 若出现以下提示 则为未安装 Git：
```
-bash: git: command not found
```

请根据您的系统类型安装 Git：

✅ CentOS / RHEL 系统：
```
sudo yum install git
```
✅ Ubuntu / Debian 系统：
```
sudo apt install git
```

安装完成后，请再次执行克隆命令：
```
git clone https://github.com/xfy52/mtproxy.git
```

📂 第二步：进入项目目录
```
cd /root/mtproxy
```

🚀 第三步：执行安装脚本
```
bash mtproxy_go.sh
```

✅根据提示完成安装即可
