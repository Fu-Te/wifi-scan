# WifiScan
Scapyを利用してWiFiスキャンをします．
近くのワイヤレスネットワークとMacアドレス，dBmシグナル，チャネルと暗号化タイプを検索して表示する

# 使い方
```
$ git clone https://github.com/Fu-Te/wifi-scan.git
$ cd wifi-scan
$ pip install -r requirements.txt
$ python3 wifi_scan.py
$ sudo ifconfig wlan0 down
$ sudo iwconfig wlan0 mode monitor
```

#　参考
https://www.thepythoncode.com/article/building-wifi-scanner-in-python-scapy