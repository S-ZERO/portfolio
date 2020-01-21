# 利用方法(Windows)

## 事前準備
1. `addr_research_portfolio`フォルダをC直下に置く
2. Pythonをインストールしておく
[Python](https://www.python.org/downloads/)
3. Chromeをインストールしておく
[Chrome](https://www.google.com/intl/ja_jp/chrome/) 
5. Chrome driverを最新のものにする
[Chrome driver](https://chromedriver.chromium.org/downloads)
 ※. 最新にした場合は`common`フォルダ無いの`chromedriver.exe`と入れ替える
4. `first.bat`を実行する


## IPアドレスの危険度を調査したい場合

1. `test_researchIP.txt`と同じ形式で検索したいIPアドレスの一覧をテキストデータで作成
2. コマンドプロンプトなどで`main_Web_IP.py`を実行し、作成したテキストデータをドラック&ドロップ
3. `Enter`を押下すると、結果が`result`フォルダに出力される



## URLの危険度を調査したい場合

1. `test_researchURL.txt`と同じ形式で検索したいURLの一覧をテキストデータで作成
2. コマンドプロンプトなどで`main_Web_URL.py`を実行し、作成したテキストデータをドラック&ドロップ
3. `Enter`を押下すると、結果が`result`フォルダに出力される
