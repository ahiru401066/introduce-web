# introduce-web  
<img width="400" alt="Image" src="https://github.com/user-attachments/assets/693749aa-29c6-4170-9ae9-380c47f2fa73" />
<img width="400" alt="Image" src="https://github.com/user-attachments/assets/8eb87b24-977d-481b-a4a4-4a3c9e549c21" />
  
#### 概要　
　このプロジェクトはポートフォリオ+自己紹介用のサイトです。自分の紹介や、過去の作品や技術的な取り組みを掲載することと、  
 インフラやネットワークを学習するために作成しました。

ホームページURL：https://ichikawa-work.com


## 技術
- **HTML5** & **CSS3** & **JavaScript** (Bootstrap使用)
- **EC2**
- **nginx**

## 行ったこと
- **フロントエンド開発**  
  サイトのUIを作成し、レスポンシブデザインを意識して実装
    
- **ドメイン取得とIPに紐付け**
  1. お名前.comでドメインを取得
  2. DNS設定を操作してEC2のパブリックIPをレコードに設定
- **NGINXを導入**  
  リバースプロキシや静的ファイルの設定  
- **Certbotを利用しHTTPからHTTPSへ変更**    
  Let's EncryptでSSL証明書を適応


## 今後の改善点
- **デプロイの自動化**  
  現在は手動で行っているが、GitHub Actionsを利用して自動でサーバーにデプロイできるようにする

