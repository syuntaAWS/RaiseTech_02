# 第4回課題提出

## 内容

1. VPC作成
2. EC2作成
3. RDS作成
4. EC2からRDSへ接続

### VPC作成

- VPC作成<br>
![VPC作成](/lecture4/VPC作成.png)

### EC2作成

- EC2作成<br>
![EC2作成](/lecture4/EC2作成.png)

- **インバウンドルールmyIP設定再提出**<br>
![再提出](/lecture4/myIPに設定.png)

### RDS作成

- **RDS再作成サブネット変更**<br>
![再作成](/lecture4/RDS再作成サブネット変更.png)

- **インバウンドルール設定エビデンス**<br>
![RDSインバウンドルール設定](/lecture4/プライベートサブネットエビデンス.png)

### EC2からRDSへ接続

- **再作成再接続**<br>
![EC2からRDSへ再接続](/lecture4/EC2接続RDS接続.png)

## 感想

- EC2接続がうまくいかず講師の方への質問し解決<br>
  EC2の設定でプライベートサブネットを選択していた。<br>
- 上記以外についてはネットの豊富な情報に助けられた。<br>
- 第５回の内容でわからない部分が発生した場合にも、一度立ち止まり調べることを忘れず行う。

## 参考資料

- [EC2からRDS接続](https://blog.serverworks.co.jp/ec2-to-private-rds)
- [AZについて](https://rikeitsushin.com/region-az/)
- [セキュリティーグループ](https://qiita.com/free-honda/items/fa6533d9eb2204ad7cf8)
- [パブリック及びプライベートサブネットについて](https://qiita.com/ryoya1122/items/70b9aca52c2c18322e5a)
- [AWSのネットワーク基礎知識](https://qiita.com/MayForBlue/items/95562b1af16f74e44110)