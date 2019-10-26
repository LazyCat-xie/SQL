sudo service mysql start # 打开MySQL服务
sudo apt-get install mysql-server # 安装MySQL服务端、核心程序
sudo apt-get install mysql-client # 安装MySQL客户端
sudo netstat -tap | grep mysql # 验证MySQL是否安装并启动成功
mysql -u root # 使用root用户登录
show database; # 查看有哪些数据库（注意不要漏掉分号；）
use <数据库名> # 连接其中一个数据库
show table; # 查看该数据库中有哪些表（注意不要漏掉分号；）
quit 或者 exit # 退出MySQL
