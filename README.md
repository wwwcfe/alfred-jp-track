#配送状況確認 Alfred Workflow

日本の運輸業者の配送状況を確認する Alfred Workflow です。


## 対応サービス

- ヤマト運輸
- 佐川急便
- 日本郵便
- 西濃運輸


## 使い方


```
track yamato <送り状番号>
track sagawa <送り状番号>
track japanpost <送り状番号>
track seino <送り状番号>
```

## スクリーンショット

![](https://raw.github.com/wwwcfe/alfred-jp-track/master/screenshot.png)


## カスタムサーチ

Alfred Workflow が利用できないユーザーは以下のブラウザの URL 欄にコピペしてカスタム検索に登録できます。

ヤマト運輸
```
alfred://customsearch/%E3%82%AF%E3%83%AD%E3%83%8D%E3%82%B3%E3%83%A4%E3%83%9E%E3%83%88/track%20yamato/utf8/noplus/http://jizen.kuronekoyamato.co.jp/jizen/servlet/crjz.b.NQ0010?id={query}
```

佐川急便
```
alfred://customsearch/%E4%BD%90%E5%B7%9D%E6%80%A5%E4%BE%BF/track%20sagawa/utf8/noplus/http://k2k.sagawa-exp.co.jp/p/web/okurijosearch.do?okurijoNo={query}
```

日本郵便
```
alfred://customsearch/%E6%97%A5%E6%9C%AC%E9%83%B5%E4%BE%BF/track%20japanpost/utf8/noplus/https://trackings.post.japanpost.jp/services/srv/search/?search.x=1&search.y=1&requestNo1={query}
```

西濃運輸
```
alfred://customsearch/%E8%A5%BF%E6%BF%83%E9%81%8B%E8%BC%B8%20%28%E3%82%AB%E3%83%B3%E3%82%AC%E3%83%AB%E3%83%BC%E4%BE%BF%29/track%20seino/utf8/noplus/https://track.seino.co.jp/cgi-bin/gnpquery.pgm?GNPNO1={query}
```
