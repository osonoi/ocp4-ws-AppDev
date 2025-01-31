
# ハンズオン環境および前提
minishift, 及びIBM Cloud上のOpenShiftで動作を確認中です。
minishiftの環境構築はこちらを参照ください。
https://docs.okd.io/latest/minishift/getting-started/installing.html  
Macでメモリー８GBの機種の場合はVirtualBoxではなくXhyveをお勧めします。  
WindowsでHyper-Vを使う場合はこちらを参照ください。  
https://qiita.com/osonoi/items/8e818e9d3018cb14ee4a


# ハンズオン概要

以下を学びます。
- OCP4クラスターの構築手順
- アプリケーションのデプロイ
  - ソースコードからコンテナイメージをビルドしてデプロイ
  - 既存のコンテナイメージをOCP上に展開してデプロイ
- Jenkinsベースのビルドパイプラインの使用
- 複数コンテナの連携
- 様々なデプロイメント手法(Blue/Green、カナリアリリースなど)

なお，インフラエンジニア向け，アプリ開発エンジニア向けを想定した発展的なハンズオンもご用意しております。

### 前半 
- [Lab1: OCP4クラスター構築，コンテナイメージのビルド&デプロイ](Lab1)
- [Lab2: Jenkinsベースのビルドパイプラインの使用](Lab2)

### 後半
- [Lab3: 複数コンテナの連携](Lab3)
- [Lab4: 様々なデプロイメント手法](Lab4)
