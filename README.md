# 2024_PBL(lanitech)
2024年度学部共通PBL 言語処理班

## 観光雑誌PDF 校正Webアプリケーション概要
![Image](https://github.com/user-attachments/assets/972142bf-508b-4f6d-959d-bd0719b50128)

###1. 前準備

Google Colab用のファイルを開き、画面上部のバナーで"ランタイム"をクリックし、続いて"ランタイムのタイプを変更"をクリックすることにより使用するハードウェアを変更できます。
T4 GPU にチェックを入れ、GPUの部分にチェックが入っていることを確認して保存してください。

本アプリでは、3つの home.png, check.png, show.png（写真）と、Few-shot用の Proofreading_data_train.csv"（csvファイル）があります。これらをダウンロードしてください。
次に、画面左側のバナーにあるフォルダアイコンをクリックし、これらをアップロードしてください。

また、本アプリケーションはStreamlit が使用されています。
アプリの利用には、ngrokのアカウント登録が必要となります。
[こちら](https://ngrok.com/)でngrokのアカウントを作成していただき、Your AuthoToken に表示されるトークンを次のコードに入力してください。

```python
# ngrokを設定
NGROK_AUTH_TOKEN = "Your AuthoToken"
```

###2.アプリケーションの使い方

ファイルがアップロードされ、トークンが入力されている状態でGoogle Colabを実行していただくとリンクが生成されます。リンクの先でアプリケーションを操作することができます。

