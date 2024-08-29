# ささっと手軽にアプリを作成！PythonとStreamlitでデータ分析ダッシュボード開発ハンズオン

## ハンズオン準備
`monomono_streamlit_testdata.csv`をローカルにダウンロード

## ハンズオン手順

1. モジュールのインストール
```
pip install streamlit janome
```

2. コードを開く

`streamlit_app.py`を開く

3. Streamlitの実行
```
streamlit run streamlit_app.py
```
4. シンプルブラウザを開く
![image](https://github.com/user-attachments/assets/32e2be48-741f-41b4-b90e-2f294f0ebef7)

5.シンプルブラウザを更新（変更の確認）
![image](https://github.com/user-attachments/assets/ac149a6e-3fa3-474b-a28a-142a37fcc5d5)

## 演習
1. タイトルで「YouTubeチャンネル分析」と表示されるようにコードを修正する
![image](https://github.com/user-attachments/assets/75c69404-5878-4b64-b071-79af065d5ad1)

2. 変数like_minに対しても、st.sidebar.number_inputによる入力ボックスとし、表示を"高評価数下限"、stepを"1000"とする
![image](https://github.com/user-attachments/assets/33d5fbb5-b2a0-4eb3-8cc7-55fc16aa9523)

3. 棒グラフのx軸を"month"から"video_title"に変更する
![image](https://github.com/user-attachments/assets/481a1419-268a-4709-ad9e-a5454e73525b)

## Streamlitについて

[ドキュメント](https://docs.streamlit.io/develop/api-reference)

[Streamlit Community Cloudの認証について](https://docs.streamlit.io/deploy/streamlit-community-cloud/status#why-does-streamlit-require-additional-oauth-scope)

## 本イベントについて

[イベント詳細](https://jellyware.connpass.com/event/327150/)

[JellyWareホームページ](https://jellyware.jp/)
