# 非接触型体温計の開発
2020 年 8 月 3 日

***

## メンバー
 - n19006 佐竹嵐斗

 - n19015 藤野竜徳

***

## 概要

現在日本において、コロナが驚異的な感染を広げています。そのためコロナの感染を防ぐために入店に際して体温を測るなど事前の予防が必要になってきました。けれど接触型体温計の場合、不特定多数の人間に対して使い回しをするなど感染のリスクが出てきます。ですので非接触型体温計の開発を私達は致します。

***

## 目標

  1. できるだけ安価にそして誰でも作れるように。
  1. 精度がよく、感染リスクがないように。

***

## 仕様
  - 非接触温度センサーを使用し、パソコンに温度の表示をします。

    - "Processing"という言語を使いパソコンに温度を表示する。

  - 体温が37.5℃以上と判断されたらメールを飛ばし、PCの画面上に「誰か来るからまっててね〜」みたいなのを出す。

    - メールの内容として、
    　「体温が○○℃と検知されました。」

  - AWSを使いログを取る

    - ログを取って置くことによって不測の事態に備えることができる。

  - 手での検温

    - 手で検温をすることにより、匿名性と効率性を確保できる。

***

## 希望

- Arduinoというマイコンを使用したい。

- 手で検温することにり精度がどのようになるか。

***

## マイルストーン

- ８月

  - ８月１７日に企画書を通す。　８月３１日までに検温器の作成。

- ９月

  - ９月の半ばぐらいまでに、仕様書で出来ることの実装。

- １０月

  - １０月３１日までに検温器を用いての実践。
    - 実践とは不特定多数の人で本当に検温できるか。

- １１月

   - 実践があまり得られないなら、１１月の半ばまで押す。
   １１月はまとめ

- １２月

    - 細かい所の調整。
