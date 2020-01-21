# 利用方法(Windows)

## 事前準備
1. `addr_research_portfolio`フォルダをC直下に置く
1. Pythonをインストールしておく
[Python](https://www.python.org/downloads/)
1. Chromeをインストールしておく
[Chrome](https://www.google.com/intl/ja_jp/chrome/) 
1. Chrome driverを最新のものにする
[Chrome driver](https://chromedriver.chromium.org/downloads)
1. 最新にした場合は`common`フォルダ内の`chromedriver.exe`と入れ替える
1. `first.bat`を実行する


## IPアドレスの危険度を調査したい場合

1. `test_researchIP.txt`と同じ形式で検索したいIPアドレスの一覧をテキストデータで作成
1. コマンドプロンプトなどで`main_Web_IP.py`を実行し、作成したテキストデータをドラック&ドロップ
1. `Enter`を押下すると、結果が`result`フォルダに出力される



## URLの危険度を調査したい場合

1. `test_researchURL.txt`と同じ形式で検索したいURLの一覧をテキストデータで作成
1. コマンドプロンプトなどで`main_Web_URL.py`を実行し、作成したテキストデータをドラック&ドロップ
1. `Enter`を押下すると、結果が`result`フォルダに出力される
