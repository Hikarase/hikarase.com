# hikarase.com

アプリの紹介とプライバシーポリシーを置くサイト。GitHub Pages で公開している。

## 構成

```
index.html               /mobile-app/ へ転送するだけ
mobile-app/index.html    アプリの紹介と問い合わせ先
privacy/index.html       乾杯ウォッチのプライバシーポリシー
privacy/kyukan/          休肝ウォッチのプライバシーポリシー
privacy/taiju/           体重ウォッチのプライバシーポリシー
app-ads.txt              AdMob のアプリ確認用
style.css                共通スタイル
CNAME                    独自ドメインの設定
```

## 社名を載せない

社名で検索すると登記住所が出るため、サイトには社名を載せない。
TOP を消さずに転送で残しているのは、Apple の法人登録に「組織のドメインで公開されているサイト」が要るため。

## 公開

`main` ブランチへの push で自動的に反映される。
