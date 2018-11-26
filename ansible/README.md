# installation
 ## 依赖：python2.7
 ## 安装完验证：ansible --version
 
# 部署机器准备工作
 ## ssh免登陆设置
  在ansible服务器上执行ssh-keygen，~/.ssh/文件夹下生成id_rsa和id_rsa.pub，讲id_rsa.pub的内容拷贝到其他服务器的authorized_keys文件中。
  验证：在ansible服务器上执行ssh *.*.*.*,不用输入密码，就登入。
 ## 设置要部署的服务器
  编辑/etc/ansible/hosts文件。
