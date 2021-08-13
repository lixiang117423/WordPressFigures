```shell
sudo apt-get install openssh-server
sudo service ssh start
sudo apt-get install git

ls -a ~/.ssh
ssh-keygen -t rsa -C "lixiang117423@gmail.com"
cat ~/.ssh/id_rsa.pub # 将公钥复制粘贴到GitHub的Setting里面即可。
```

