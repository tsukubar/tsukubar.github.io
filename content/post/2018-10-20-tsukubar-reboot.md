---
title: Tsukuba.Rへようこそ
author: Shinya Uryu (@u_ribo)
date: '2018-10-20'
slug: ''
categories: []
tags: []
---

去る10月7日、およそ7年ぶりとなるTsukuba.Rが[つくばイノベーションプラザ](http://www.city.tsukuba.lg.jp/shisetsu/shiminseikatsu/1002800.html)にて[開催されました](https://www.meetup.com/ja-JP/TsukubaR/events/254321674/)[^1]。運営メンバーも刷新ということもあり、新生Tsukuba.Rとして再起動となります。イベントのナンバリングも#1と改めました。

[^1]: 前進となるTsukuba.Rの#9が2011年11月に開催されてから

![つくばへようこそ！](../image/tsukubar_kick_off_meeting1.jpg)

立ち上げの回となった今回は、Tsukuba.Rのコミュニティとしてのあり方や今後の運営について議論する回でした。
ゲストスピーカーとして[\@kilometer00](http://twitter.com/kilometer00) さんにトークしていただり、LTや飛び込みでの発表があったりと賑わいました。

この記事では当日発表のあった資料と回の様子（主にTwitterからの実況）について報告します。話し合った内容についての詳細は[GitHub Issues](https://github.com/tsukubar/hq/issues)にまとめています。

<blockquote class="twitter-tweet" data-lang="en"><p lang="ja" dir="ltr">はじまったぞ！ <a href="https://twitter.com/hashtag/tsukubar?src=hash&amp;ref_src=twsrc%5Etfw">#tsukubar</a></p>&mdash; kilometer (@kilometer00) <a href="https://twitter.com/kilometer00/status/1048788392106807302?ref_src=twsrc%5Etfw">October 7, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/TsukubaR?src=hash&amp;ref_src=twsrc%5Etfw">#TsukubaR</a><br>つくばR、はじまりました～！パチパチ</p>&mdash; niszet📚技術書典5 い04でした (@niszet0) <a href="https://twitter.com/niszet0/status/1048788304051621888?ref_src=twsrc%5Etfw">October 7, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


記念すべき？最初のつぶやき。

## Guest Talk Sessoion \@kilometer00

国内のRコミュニティとして、もっとも規模が大きく歴史も長いTokyo.Rの運営メンバーを務めている[\@kilometer00](http://twitter.com/kilometer00)さん。話していただいたテーマは「初心者セッションを行う際のコンセプト」です。

<script async class="speakerdeck-embed" data-id="f6d07c06ab73475db39096901a2a15b6" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>

[\@kilometer00](http://twitter.com/kilometer00)さんはここ数回のTokyo.Rの初心者セッションで毎回発表されています。行動神経科学を専門に研究されていることもあり、とてもわかりやすく、私自身もなるほど、と何度も納得してしまいました。

初めてRを触る、プログラミングをする人たちに対して、どのように考え方から伝えていく際の知見について学べました。

<blockquote class="twitter-tweet" data-lang="en"><p lang="ja" dir="ltr">昨日のハイライトです。 <a href="https://twitter.com/hashtag/tsukubar?src=hash&amp;ref_src=twsrc%5Etfw">#tsukubar</a> <a href="https://t.co/w4tDkzhtTn">pic.twitter.com/w4tDkzhtTn</a></p>&mdash; kilometer (@kilometer00) <a href="https://twitter.com/kilometer00/status/1049186446077120513?ref_src=twsrc%5Etfw">October 8, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="ja" dir="ltr"><a href="https://twitter.com/kilometer00?ref_src=twsrc%5Etfw">@kilometer00</a> さんの話からは、誰かに何かを教える際に気をつけていることやコツを学べました。実例を取り上げ、比較すること。そうすれば確かにわかりやすいかもしれないと感じました。<br>Tokyo.R運営の話も、コミュニティ活動の参考になる点が豊富でした。<br>（無茶をお願いしてしまってすみません）</p>&mdash; Uryu Shinya (@u_ribo) <a href="https://twitter.com/u_ribo/status/1048872731054227457?ref_src=twsrc%5Etfw">October 7, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


## Meeting session

一部抜粋です。

- Rコミュニティではあるけど、Rだけにこだわらず、「つくば」周辺の学生、研究者、データ分析に携わる人の交流の場、活動の支援を目指したい
    - 回のテーマは言語を問わずに。Python, Julia、なんでもこい。
- 一回の時間は数時間（平日）から半日（休日）。発表者は2,3人。時間が余ればもくもく会として自由時間に充てるのが良い。
- イベントページとして[meetup](https://www.meetup.com/ja-JP/TsukubaR/)を用意したが、日本人ユーザにはconnpassの方が馴染みがある。Tokyo.Rでの導入事例もあるので移行を検討する。
- meetup, Slack, [GitHub Organization](https://github.com/tsukubar)を通じてイベントの用意を行う
    - これらのサービスを利用しないメンバーには職場、メールを通して連絡

![テーマ回に関する議論の様子](../image/tsukubar_kick_off_meeting2.jpg)

## Lighting Talk Session

話題提供として、[\niszet0](https://twitter.com/niszet0) さんのR Markdownでパワーポイントを作る、[\@u_ribo](https://twitter.com/u_ribo) による[textlint](http://textlint.github.io)の機能をRコード、R Markdownに導入する話がありました。また、予定にはなかったのですが、[\@hankagosa](https://twitter.com/hankagosa) さんが、統計モデリングの簡単な導入を行ってくださいました。（豪華な資料を超短時間で圧縮して説明するというもの！！）

### 超速ベイズ入門 \@hankagosa

<blockquote class="twitter-tweet" data-lang="en"><p lang="ja" dir="ltr">唐突に超豪華ベイズ入門！ <a href="https://twitter.com/hashtag/tsukubar?src=hash&amp;ref_src=twsrc%5Etfw">#tsukubar</a></p>&mdash; kilometer (@kilometer00) <a href="https://twitter.com/kilometer00/status/1048814910442893317?ref_src=twsrc%5Etfw">October 7, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="ja" dir="ltr">サプライズでしたが、気になったポイントをその場で質問できるし、じっくり解説してもらえるし、お得感たっぷりでした😁1000×ありがとうございます！！ <a href="https://t.co/xI0R8mfnNi">https://t.co/xI0R8mfnNi</a></p>&mdash; Uryu Shinya (@u_ribo) <a href="https://twitter.com/u_ribo/status/1048874643291951104?ref_src=twsrc%5Etfw">October 7, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### R Markdownでパワーポイント作成 \@niszet0

<blockquote class="twitter-tweet" data-lang="en"><p lang="ja" dir="ltr">突貫LTで技術書典のお話 <a href="https://twitter.com/hashtag/tsukubar?src=hash&amp;ref_src=twsrc%5Etfw">#tsukubar</a></p>&mdash; kilometer (@kilometer00) <a href="https://twitter.com/kilometer00/status/1048824384008282113?ref_src=twsrc%5Etfw">October 7, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="ja" dir="ltr"><a href="https://twitter.com/niszet0?ref_src=twsrc%5Etfw">@niszet0</a> さんは、明日 <a href="https://twitter.com/hashtag/%E6%8A%80%E8%A1%93%E6%9B%B8%E5%BA%97?src=hash&amp;ref_src=twsrc%5Etfw">#技術書店</a> で販売される「R MarkdownでWord文書を作ろう」の制作秘話とR Markdownでパワポ（⁉️）を作るという話を聞けました。とても実用的な話でした。表紙は要チェックです👀</p>&mdash; Uryu Shinya (@u_ribo) <a href="https://twitter.com/u_ribo/status/1048874159898423296?ref_src=twsrc%5Etfw">October 7, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="ja" dir="ltr">RMarkdown（pandoc）でパワポ作るの便利そう。昔紹介したのはこちら。 <a href="https://twitter.com/hashtag/tsukubaR?src=hash&amp;ref_src=twsrc%5Etfw">#tsukubaR</a> <a href="https://t.co/wsFFbn62nI">https://t.co/wsFFbn62nI</a></p>&mdash; Kentaro Matsuura (@hankagosa) <a href="https://twitter.com/hankagosa/status/1048827784766709760?ref_src=twsrc%5Etfw">October 7, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

### textlintrパッケージ開発話 \@u_ribo

Twitter上のふとした一言で始まったtextlintのR移植パッケージtextlintrについて紹介しました。

https://github.com/uribo/textlintr

ぜひお試しください! バグ報告、機能追加のリクエストもお待ちしています。


## 祭りの後に...

不慣れな運営、進行でしたが、無事に開催できてひとまず安心です。参加された方、どうもありがとうございました。今後ともお世話になります。

Tsukuba.Rでは、運営をサポートしてくださるメンバーを募集しています。活動に興味のある方はぜひ、meetupでメンバー登録をおこなってください。TwitterやSlackで[\@tsukubar](https://twitter.com/tsukubar)または[\@u_ribo](https://twitter.com/u_ribo)あてにメンションを飛ばしていただいても構いません 😀

最後に、すべてではありませんが、Twitter上で見かけたイベントの感想をピックアップします。

<blockquote class="twitter-tweet" data-lang="en"><p lang="ja" dir="ltr">tsukubaR楽しかったな。遅刻して入ったらどう見てもボルダリングの説明してて面食らったけど、初心者への教え方論でもっと早めから聞きたかったわい。 <a href="https://twitter.com/hashtag/tsukubaR?src=hash&amp;ref_src=twsrc%5Etfw">#tsukubaR</a></p>&mdash; Kentaro Matsuura (@hankagosa) <a href="https://twitter.com/hankagosa/status/1048858670778343425?ref_src=twsrc%5Etfw">October 7, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="ja" dir="ltr">筑波大学に変態的なRユーザがいるというタレコミも得た</p>&mdash; Uryu Shinya (@u_ribo) <a href="https://twitter.com/u_ribo/status/1048881330627342339?ref_src=twsrc%5Etfw">October 7, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="ja" dir="ltr">Tsukuba.R#1 おしまい！参加された方ありがとうございました。<br><br>今後のコミュニティ運営を考えるための議論や相談ができてよかったです。<br>開始前、参加者数に不安がありましたが、蓋を開けてみれば学生の参加もあり、企業、研究機関、大学という多様な人たちが交流できる場となっていて安堵しました。</p>&mdash; Uryu Shinya (@u_ribo) <a href="https://twitter.com/u_ribo/status/1048871294266105856?ref_src=twsrc%5Etfw">October 7, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="ja" dir="ltr">今後が楽しみな会でした！ありがとうございました！ <a href="https://t.co/GhsoCJ2jPl">https://t.co/GhsoCJ2jPl</a></p>&mdash; nakaizumi (@iOut3) <a href="https://twitter.com/iOut3/status/1048880483164086274?ref_src=twsrc%5Etfw">October 7, 2018</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
