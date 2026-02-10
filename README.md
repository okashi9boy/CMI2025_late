# kaggle_bass_repo
- kaggleの複製用リポジトリ。各コンペに対してこのリポジトリを複製し、実験管理を行う。
- 複製は手作業でこのリポジトリをzipでDLしてnewリポジトリでreadme作るとファイルUPできるからドラック＆ドロップで複製
- 上記を https://took.jp/github-import-repository/ のようにしようとしたができなかった
- コピペ後はコンペ概要を記載。
- コンペ概要をAIでまとめて貼り付ける際はマークダウン記法で指定して、AIの出力を編集状態にしたうえでコピーする。

## kaggleコンペ取り組み時の流れ
1. chrome分割タブ機能、拡張機能のサイドバーを使用してai studio、github、参考サイトなどを表示させながら進行
2. githubでkaggle_bass_repoリポジトリを複製して名前だけ変更する
3. githubで「. + any key」でweb版vs codeが開けるのでファイルやフォルダを作成、削除する
4. kaggle notebook でinputファイルセット

## githubでの編集方法chips
- マークダウンの書き方
  - 見出し「#」
  - テキスト装飾「斜体（*）*A*、太字（**）**A**」
  - コードブロック（```）
  - その他　https://note.com/minami206/n/n7fff993ce14f

## 基本tree

```
├experiments
│    ├exp_1
│    │   ├a.md（ディレクトリ内の説明用、yamlの中身についてや実験のメモなど）
│    │   ├config.yaml（パラメーター設定）
│    │   ├exp_1.ipynb or exp_1.py（実験ファイル）
│    │
│    ├exp_2（exp_1をコピーして改変して使用）
│
│
├results
│    ├exp_1
│    │    ├model.pkl(実験ファイルで生成したモデルのoutputファイル)
│    │    ├results.csv（提出用ファイル）
│    │
│    ├exp_2（exp_1をコピーして改変して使用）
│
├reference
  ├note
  │  ├ipynb.md
  │
  ├discuss
      ├discuss_pdf_or_.md  

```
