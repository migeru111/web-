xml
    <?xml version="1.0"encoding="utf8"?>
        <htmlxmlns="http://www.w3.org/1999/xhtml">
        <head>
            <title>初めてのHTML</title>
        </head>
        <body>
            <h1>初めてのHTML</h1>
            <p>HTMLの仕様書は<ahref="http://www.w3.org">W3C</a>にあります。</p>
        </body>
        </html>

    開始タグ　
        <tagname>
    終了タグ 
        </tagname>
    内容(content)　
        開始タグと終了タグに挟まれたもの
    要素 
        開始タグ、内容、終了タグで構成される。
        要素は属性を複数持てる。 
    属性
        属性名と属性値の組
        開始タグの中に 属性名="属性値" という形式で記述する。

DOM
    概要
        ドキュメントオブジェクトモデル
        web文書のためのプログラミングインターフェース。
        html,xml,cssを、javascriptなどのプログラミング言語からアクセスできるようにするためのAPIのこと。
        DOMはhtml,xmlの各要素をオブジェクトとして表現するため、プログラミング言語を使用してそれらを操作できる。
        
        ツリー構造で表現する。
        ドキュメントの各要素やテキストはノードとして表現される。
            ノードにはいくつかの種類がある。
                htmlの要素を表すものを要素ノードという。
                要素の中に記述されているテキストをテキストノードという。

        chatGPT曰く
            xmlで表現された文書に対して、domというAPIを用いることで、プログラミング言語によって文書を操作する。**とのこと

    DOMについて
        udemy
            一番わかりやすい
            https://udemy.benesse.co.jp/development/dom.html
        DOM
            https://developer.mozilla.org/ja/docs/Web/API/Document_Object_Model
        DOMとは
            https://developer.mozilla.org/ja/docs/Web/API/Document_Object_Model/Introduction

jquery
    javascriptのライブラリ
    html文書内の要素を操作する方法を提供する。
        jQuery()は$()と書ける

    DOMのドキュメントからDOM要素を選択するためにselectorが使用される
        childSelector
            $("parent > child")
            上の記法で、parentの小要素のchildをクエリしてjQueryオブジェクトとして取得する。
            https://api.jquery.com/child-selector/

    参考
        https://api.jquery.com/category/selectors/
