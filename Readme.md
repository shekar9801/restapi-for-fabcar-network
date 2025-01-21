#### Prerequisities installation (Hyperledger fabric 2.2.0)
##### 1. Install the docker and docker-compose
```
sudo apt-get update -y
sudo apt-get install -y docker-ce docker-ce-cli containerd.io
```

```
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```
##### 2. Install the python

```
sudo apt-get install python3.8 python3-pip -y
```
##### 3. Install Node.js 14.x and npm:

```
curl -fsSL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install -y nodejs
```
##### 4. Download Go 1.14 (required for Hyperledger Fabric 2.2):

```
wget https://dl.google.com/go/go1.14.15.linux-amd64.tar.gz
sudo tar -C /usr/local -xzf go1.14.15.linux-amd64.tar.gz

```
##### 5.Add Go to PATH

```
echo "export PATH=$PATH:/usr/local/go/bin" >> ~/.bashrc
source ~/.bashrc
```


