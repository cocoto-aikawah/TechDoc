■インスタンスの起動までの手順  
1.島村さんに作成してもらった情報から「Console login link」にアクセスする。  
2.同じくもらった情報から、ユーザ名(User name)とパスワード(Password)を入力して「サインイン」。  
　※初回のみ、パスワードの変更を求められる。  
3.デフォルト？だとリージョンが「オハイオ」になっているので、バー右上のプルダウンから「東京」を選択。  
　※うまくいかない場合は、  
　https://ap-northeast-1.console.aws.amazon.com/console/home?region=ap-northeast-1#  
　にアクセスしてみる。  
4.左側のメニューから「インスタンス」を選択  
　aws-cloud9-... のものが対象  
5.画面右下の「インスタンスの表示」をクリック。  
6.インスタンスを選択し、「接続」をクリック。  
7.インスタンスに接続の画面で「接続」をクリック。  
  
■SSHクライアントの起動(TeraTermの例)  
1.ホスト名にグローバルIPを指定(要確認)。  
2.「このホストをknown hostsリストに追加する」のチェックは外しておく。  
3.「RSA/DSA/ECDSA/ED25519鍵を使う」にチェックを入れ、配布されたpemファイルを鍵ファイルとして指定。  
  
■初回のみpython3のインストール(すでにインストールされているので不要)。  
$ sudo yum install python3 -y  
  
■VI等でPythonコードを記述。作成に当たっては何を使用してもかまわない。  
※記述に関しては公式サイト等で確認してください。  
　インデント位置が重要なので、他の言語に慣れていると、スペースを自由につけすぎてエラーになる場合が多々あります。
(例)  
$ vim test.py  
・test.py  
print("Hello world!")  
  
■実行したいときはファイル名を指定して起動  
(例：ファイル名が「test.py」の場合)
$ python test.py  
Hello world!  
  
■参考サイト  
・Python公式サイト  
https://www.python.org/  
・Pythonコミュニティ紹介サイト  
https://www.python.jp/pages/community.html  
