# Math

```bash

sudo apt update
sudo apt upgrade

sudo apt install texlive-lang-cjk xdvik-ja evince

sudo apt install texlive-fonts-recommended texlive-fonts-extra
#hoge.texファイルのある場所まで移動する。

# dviファイル生成
platex hoge.tex

# pdfファイル生成
dvipdfmx hoge.dvi

#pdf開く(tex編集中は以下で開くと変更反映がリアルタイムになる。)
evince hoge.pdf &