ssh-keygen -t rsa 生成rsa格式秘钥

scp -P 端口号 /path/to/local/file user@remoteip:/path/to/put

在远端机器

cat id_rsa.pub >> ~/.ssh/authorized_keys