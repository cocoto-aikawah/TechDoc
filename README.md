■初回のみpython3のインストール(すでにインストールされているので不要)。  
$ sudo yum install python3 -y  

■ほかの人とかぶらないように自分のフォルダを作成し、そこで作業を行う  
(例)  
$ mkdir aikawah  
$ cd aikawah  
  
■VI等でPythonコードを記述。作成に当たっては何を使用してもかまわない。  
1.ファイルの拡張子は「.py」としてエディタを起動  
(例)  
$ vim test.py  
  
2.Pythonコードを記述し保存。  
※記述に関しては公式サイト等で確認してください。  
　インデント位置が重要なので、他の言語に慣れていると、スペースを自由につけすぎてエラーになる場合が多々あります。  
(例)  
print("Hello world!")  
  
3.ファイル名を指定して起動  
(例)  
$ python test.py  
Hello world!  
※例だと、文字列を表示する処理が実行される。  
  
■参考サイト  
・Python公式サイト  
https://www.python.org/  
・Pythonコミュニティ紹介サイト  
https://www.python.jp/pages/community.html  
