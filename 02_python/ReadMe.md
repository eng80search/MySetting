開発環境がproxyがある際に、pythonのpipがそのままでは使えないの
ユーザーフォルダ%USERPROFILE%にpipフォルダを作成し、以下のようにpip.iniを設定する

pipパッケージをファイルから一括インストールする方法
1.現在のパッケージ一覧をファイルへ書き出す
pip freeze > requirements.txt
2.新しい環境で以下のコマンドでパッケージを一括インストールする
pip install -r requirements.txt
