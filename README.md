# campingcloud

## DOWNLOAD images(1.2GByte):
- 展開すると16G SD カードのサイズになります。
- https://s3-ap-northeast-1.amazonaws.com/camping-cloud/campingcloud.20180118.img.zip

## INITIALISE 
1. download image .
2. イメージをSD カードに書き込んでください。（Mac の場合は以下のツールが簡単です）
   dd or (apple-pi-baekr tool)[https://www.tweaking4all.com/software/macosx-software/macosx-apple-pi-baker/]
3. ラズパイに　差し込んで起動する。

## HOW TO USE
1. PowerOn
2. Connect Wify from iPhone. (WAP : camping-cloud-ap/Zaq12wsx)
3. Connect via SSH (User : pi / p@ssW0rd)

## tool
* USB ドングルを本体に接続し、以下のツールを使うと　outbound をネットワーク側に接続するようになります。
　たとえば、ドングルを指した状態で家のwify に接続すると raspiが　ルータとして外部接続のパケットを流すようになります。
  
``` 
sudo /opt/tools/chwify.sh {your.home.wify or phone tethering} {wify.password}
```
