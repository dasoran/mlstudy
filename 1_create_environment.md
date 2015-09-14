# 環境構築

まずは、環境を構築します。

今回はUbuntuで開発します。

また、テキストエディタとしてAtomをいれます。


## 目次

* VirtualBoxを入れる
* Ubuntuをダウンロードする
* Ubuntuをインストールする
* Guest Additionをいれる
* Pythonの動作確認をする
* Atomを入れる
* 今後の作業のために

## VirtualBoxを入れる

まずVirtualBoxをインストールします。

[https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads)

## Ubnutuをダウンロードする

このページから64bitなUbuntuをダウンロードします。14.04で大丈夫です。

寄付してくれとのお願いが出てきますが、特に興味がなければ無視してかまいません。

[http://www.ubuntu.com/download/desktop](http://www.ubuntu.com/download/desktop)


## Ubuntuをインストールする

VirtualBoxでVMを作ってUbuntuをインストールします。

まずはVMを作成します。

1. VirtualBoxを起動する
2. 新規ボタンから「仮想マシンの作成」ウィザードを起動
3. 好きな名前(仮にchocolat)をいれて、タイプを「Linux」バージョンを「Ubuntu (64-bit) 」にする
4. 適当にはいを押し続ける(RAMは2048MBに増やすべき。デフォルトの768MBで動作確認してて遅すぎて原稿書いてる今泣いてる)

これでVMが作成されたのでUbuntuをインストールします。

1. リスト上に表示されている作られたVM(ここではchocolat)を右クリックし設定を開く
2. ストレージの項目にCDっぽいマークがあるのでクリック
3. がんばってUbuntuのiso(さっきダウンロードした奴)を選択(マウント)する
4. 設定画面を閉じる

起動し、インストールしましょう。

1. リスト上でVMを右クリックし、通常起動で起動します
2. ちょっとまって、Try UbuntuとInstall Ubuntuを選ぶ画面でInstall Ubuntuしましょう。ただし、日本語を選ぶのを忘れずに
3. インストール中にアップデートをダウンロードするにチェックをいれて進めます
4. 何も考えず次へ、続けるなどを連打します！
5. ユーザー登録だけちゃんとやります
6. やっためう！Ubuntuがはいっためう！


## Guest Additions

こちらを参照

[VirtualBox にインストールした Ubuntu の画面サイズ（解像度）を640×480以外に変更する方法](http://mogi2fruits.net/blog/os-software/windows/2389/)


## Python3の動作確認をする

Ubuntu起動後、1番上の渦巻きみたいなアイコンをクリックするとアプリ検索ができます。そこで「terminal」と打つと端末というのが表示されるのでそれを起動します。

そこで

```
python3 --version
```

と入力してください。

Python3が正しくインストールされているなら Python 3.4.0 などと表示されるはずです。

## Atomを入れる

Firefoxを立ち上げて、Atomを入れましょう。

Atomというのはテキストエディタの一つで、これからコードを書いていくのに使用するプログラムです。

[Atom](https://atom.io) の「Download .deb」からダウンロードしてください。

終わったらダブルクリックで起動します。


## 今後の作業のために
今後の作業のために作業フォルダを作りましょう。

端末(terminal)から、

```
mkdir mlstudy
```

というコマンドを入力し、homeディレクトリにmlstudyディレクトリを作成します。

今後はこのmlstudyというディレクトリを作業場所とします。



これで、環境構築完了！おつかれさまでした！！



