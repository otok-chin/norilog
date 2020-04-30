==============
乗りログアプリ
==============

目的
=====

Webブラウザーでコメントを投稿するWebアプリケーションの練習。

ツールのバージョン
====================

:Python:     3.8.2
:pip:        20.1


インストールと起動方法
=======================

リポジトリーからコードを取得し、その下にvenv環境を用意します::

   $ git clone https://github.com/otok-chin/norilog
   $ cd norilog
   $ python3 -m venv venv
   $ source venv/bin/activate
   (venv) $ pip install .
   (venv) $ norilog
    * Running on http://0.0.0.0:8000/


開発手順
=========

開発用インストール
------------------

1. チェックアウトする
2. 以下の手順でインストールする::

     (venv) $ pip install -e .
