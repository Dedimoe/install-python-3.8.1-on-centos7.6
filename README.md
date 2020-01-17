# install-python-3.8.1-on-centos7.6
install-python-3.8.1-on-centos7.6

```
sudo yum install gcc openssl-devel bzip2-devel libffi-devel wget
cd /opt
sudo wget https://www.python.org/ftp/python/3.8.1/Python-3.8.1.tgz
sudo tar xzf Python-3.8.1.tgz
cd Python-3.8.1
sudo ./configure --enable-optimizations
sudo make altinstall
#--note: altinstall is used to prevent replacing the default python binary file /usr/bin/python
sudo rm Python-3.8.1.tgz
python3.8 -V
```
