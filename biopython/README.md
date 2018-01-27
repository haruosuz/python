Haruo Suzuki (haruo[at]g-language[dot]org)  
Last Update: 2017-08-28

----------

# Biopython Tutorial Project
Project started 2017-08-28.

I have created shell scripts for automating analyses in Biopython Tutorial and Cookbook
http://biopython.org/DIST/docs/tutorial/Tutorial.html

----------

## Project directory structures

    biopython/
     README.md: project documentation
     scripts/: contains scripts for Biopython Tutorial and Cookbook

----------

# Chapter 1  Introduction
## [1.3  Installing Biopython](http://biopython.org/DIST/docs/tutorial/Tutorial.html#htoc4)

http://biopython.org/wiki/Download

    wget http://biopython.org/DIST/biopython-1.70.tar.gz
    tar xvzf biopython-1.70.tar.gz 
    cd biopython-1.70/
    pip install .

## 1.4  Frequently Asked Questions (FAQ)

7. version of Biopython

    python
    \>>> import Bio
    \>>> print(Bio.__version__)
    1.70

----------

## References

### Official Site

### Unofficial sites

https://www.biostars.org/p/59648/
Parsing Swissprot With Biopython

----------
### Japanese

http://biopython.org/DIST/docs/tutorial/Tutorial.html
Biopython Tutorial and Cookbook

http://biopython.org/wiki/SeqIO
Introduction to SeqIO · Biopython

http://biopython-tutorial-ja.readthedocs.io/en/latest/index.html
Biopythonドキュメント翻訳 — biopython-tutorial-ja 1.52 documentation

2017年12月28日に更新
https://qiita.com/sato32ha6/items/b9d85fad2d9de53374bf
BiopythonでGenbankファイル操作：CDSをすべてFASTAに書き出す - Qiita

2017-05-27
https://qiita.com/sato32ha6/items/6b762b0d0314a5db7dc3
BiopythonでFASTAファイル操作　その１：準備と初めの一歩 - Qiita

2017.03.15
https://bi.biopapyrus.jp/python/biopython/seqio.html
SeqIO | データベースからダウンロードしたファイルを処理する BioPython モジュール

2017.03.14
https://bi.biopapyrus.jp/python/biopython/seq.html
Seq | BioPython で塩基配列またはアミノ酸配列を扱うクラス

http://kmooog.hatenablog.com/entry/2016/07/01/165723
BioPythonで系統樹を書いてNewick出力 - ピエール瀧になりたい

2016/03/24
http://www.bi.cs.titech.ac.jp/~ohue/index.php?BioPython
BioPython - PukiWiki - 秋山研究室 - 東京工業大学

http://biosciencedbc.jp/gadget/human/20150728_hattori.pdf
Python入門
Amelieff

http://yagays.github.io/blog/2013/04/20/install-biopython/
Mac OS Xで手っ取り早くBiopythonをインストールして使えるようにする - Wolfeyes Bioinformatics beta 

http://nakano.no-ip.org/attic/category.php?k=Python%2Cbio
TOLLE ET LEGE 屋根裏の備忘録 : カテゴリー : Python,bio
Feb 23, 2010

http://d.hatena.ne.jp/kozo-ni/touch/20100129/1264757221
biopythonでswissprotのレコードをパースする - kozo-niのはてなダイアリー

2009, Kozo Nishida. 
http://biopython-tutorial-ja.readthedocs.io/en/latest/chapter2.html
2章 クイックスタート — biopython-tutorial-ja 1.52 documentation

2008 岩嵜航 Watal M. Iwasaki
https://heavywatal.github.io/python/biopython.html
BioPython: Tools for biological computation - Heavy Watal

2006-10-27
http://ebiomiya.exblog.jp/5938093/
BioPythonのインストール : えどがわだい BioImaging: 大宮分室2

https://sites.google.com/site/shidoinfo/Home/programing-lang/関数型プログラミング言語/python/masuda-yasushi-san-no-peji-akaivu/biopython
去る 2004 年 12 月 8 日に，ゲノム情報学国際会議 (GIW2004) のサテライト BOF として開催された「オープンバイオ BOF 2004」で Biopython の紹介 をプレゼンテーションしてきました．

http://open-bio.jp/archive/20041213_BOF/Biopython-Masuda.pdf

----------


