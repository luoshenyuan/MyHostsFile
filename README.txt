修改hosts后生效的方法：（刷新 dns 命令）

一、Windows
开始 -> 运行 -> 输入cmd -> 在CMD窗口输入:
ipconfig /flushdns



二、Linux
终端输入：
sudo rcnscd restart


对于systemd发行版，请使用命令：
sudo systemctl restart NetworkManager



三、Mac OS X终端输入：
sudo killall -HUP mDNSResponder
