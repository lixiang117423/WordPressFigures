```shell
wget https://ak-delivery04-mul.dhe.ibm.com/sar/CMA/OSA/09cne/0/ibm-aspera-connect-3.11.0.5-linux-g2.12-64.tar.gz

tar -zxvf ibm-aspera-connect-3.11.0.5-linux-g2.12-64.tar.gz

./ibm-aspera-connect-3.11.0.5-linux-g2.12-64.sh

echo """export PATH=\"/home/xiang/.aspera/connect/bin:\$PATH\" """ >> ~/.bashrc

source ~/.bashrc

ascp -h
```

