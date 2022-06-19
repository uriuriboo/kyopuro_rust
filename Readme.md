### RustのDocker環境です
機能を追加したり、修正したりの途中です
いつかDockerfileとかで以下の1~10の操作を自動化できるようにしたいです

## やってほしいこと
1. cargo competeをインストール
2. 拡張機能Rustをインストール
3. sudo apt-get する(4のため)
4. fish shellをダウンロード
5. fisherも
6. taskrunnerでいい感じにする(ビルド、テスト、デバッグ、可視化とか)
7. グラフの可視化
8. ライブラリの追加
9. online-judge-toolsの追加
10. シェルスクリプト(tc.bash)でabc以外にもテストができるようにする(権限を与えて実行可能に chmod a+x tc.bash)
11. cargo-equipを使えるように設定

# 使い方
input.txtにデバッグの入力を入れてください。

# 注意
launch.jsonはコンテストごとに書き換えてください

rust-analyzerをインストールするとコンテナを立ち上げるごとに使えなくなりました