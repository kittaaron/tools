### 生成sshkey

ssh-keygen -t rsa -C 'liuhuiyu5201413@163.com' -f id_rsa_github

编辑~/.ssh/config（没有的话是新建）
Host github ##可以随意命名，链接时使用这个名字  
HostName github.com  
User git  
Port 22  
IdentityFile ~/.ssh/id_rsa_second
