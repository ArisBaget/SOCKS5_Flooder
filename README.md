# SOCKS5 Flooder - HTTP Flood script using SOCKS5 proxies

## 🤔 How to use?

### Install Python 3.
```
sudo apt install python3.
```
### Install PIP.
```
sudo apt install python3-pip
```

### Install modules.
```
pip3 install requests pysocks
```

### Usage.
```
python3 SOCKS5_Flooder.py <URL> <THREADS> <TIME> <SOCKS5.TXT> <TIMEOUT> <RATE>
```

| Argument| Description|
|-------------| -------------|
|URL|The target website's URL|
|THREADS|Number of threads attack (Should be from 1000 to 5000)|
|TIME|Number of seconds attack|
|SOCKS5.TXT|The file that contain SOCKS5 proxies (Must be in same folder with the script)|
|TIMEOUT|Timeout of the SOCKS5 proxy (Should be from 3-10)|
|RATE|Rate limit A.K.A requests per connections (Should be from 32 to 100, use 64 is best)|
