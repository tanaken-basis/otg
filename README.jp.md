# OTG (Optimal Transport Grouping)

[English](README.en.md) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [日本語](README.jp.md)

## 概要
なるべく均一なグループ分けを自動生成するためのPythonのプログラムです。最適輸送の手法を用いています。

## 使い方
- "otg_gradio.py"をPythonで実行すると、Gradioを用いて作成したWebアプリが起動します。グループ分けの自動生成のためのパラメータの調整、自動生成の計算の実行、計算結果のファイルへの出力などができます。このWebアプリケーションは、ローカルで動作させることができます。
- "otg_flet.py"をPythonで実行すると、Fletを用いて作成したGUIアプリが起動します。グループ分けの自動生成のためのパラメータの調整、自動生成の計算の実行、計算結果のファイルへの出力などができます。
- ノートブックのファイル"otg.ipynb"にも、同様のプログラムを記述しています。

## Pythonプログラムを使用する場合の注意点
- このコードでは、データの可視化のために、Pythonライブラリ UMAP を使用しています。UMAP のインストールについては、https://github.com/lmcinnes/umap を参照してください。
- Webアプリの作成で使用している Gradio のインストールについては、https://github.com/gradio-app/gradio を参照してください。
- アプリの作成で使用している Flet のインストールについては、https://github.com/flet-dev/flet を参照してください。

## サンプルの実行結果

#### Gradio
![alt text](otg_gradio-1.jpg)

#### Flet
![alt text](otg_flet-1.jpg)