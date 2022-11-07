# config for Umbrel Core-lightning
Umbrel Core-lightning用のconfigファイル

/home/umbrel/umbrel/app-data/core-lightning/data/lightningd<br>
この場所にconfigという名前のファイルを置くとCLNはこのコンフィグを見てくれる。

configを編集したらアプリ再起動が必要。<br>
cd ~/umbrel/script; ./app restart core-lightning 

configに何を書くのか知りたいなら
https://lightning.readthedocs.io/lightningd-config.5.html

CLNのログを見るには<br>
docker logs core-lightning_lightningd_1

ファイルに出力したいなら、configファイルと同じ場所にlog.txtというファイルを作り、configにあるlog-fileをコメントアウトを外して再起動<br>

