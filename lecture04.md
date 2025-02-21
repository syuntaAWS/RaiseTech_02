# 第4回課題提出

## 内容

- VPC作成→EC2作成→RDS作成→EC2からRDSへ接続

### VPC作成

- VPC作成<br>
![VPC作成](/lecture4/VPC作成.png)

### EC2作成

- EC2作成<br>
![EC2作成](/lecture4/EC2作成.png)

- インバウンドルール設定<br>
![EC2インバウンドルール設定](/lecture4/EC2インバウンド.png)

- EC2へ接続確認<br>
![EC2接続](/lecture4/EC2へ接続.png)

### RDS作成

- RDS作成<br>
![RDS作成](/lecture4/RDS作成.png)

- インバウンドルール設定<br>
![RDSインバウンドルール設定](/lecture4/RDSインバウンド.png)

### EC2からRDSへ接続

- RDSへ接続<br>
![EC2からRDSへ接続](/lecture4/RDS接続.png)

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