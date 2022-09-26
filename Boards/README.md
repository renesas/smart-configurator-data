# source

BDF(Board Description File)置き場。RSK系はボードチーム管理だが、RSK系以外(RX72N Envision Kit等)はボードチーム管理外のものがあり、暫定でここを置き場として規定して原本管理を行う。

# 将来の想定
* もしかすると、最終的にはこのリポジトリはGitHubから参照されるためGitHub上で公開となるかもしれない
* よってここではBDF原本のみを管理することとし、設計資料は以下別リポジトリで管理することとする
  * http://global-infra-jp-main.dgn.renesas.com/products/common/tools/sc/bdf/design
* 2022/08/09追記
  * e2 studio 2022-07以降はGitHub上の以下からBDFをダウンロードできる機構が搭載された
    * https://github.com/renesas/smart-configurator-data
  * スマートコンフィグレータチームのナムさん(シンガポール)に聞いたところによると、今しばらくの間はGitHubに加えて、ルネサスウェブからダウンロードする方式も残しておいた方が良いだろうことをマーケティングチームと合意を取っているとのこと
    * よって、ZIPファイル化してルネサスウェブ上のデータを更新する作業も今しばらく続く

# RSK系のBDFは？
* ボード設計チームで一元管理できていれば理想だが、今はそうなってない
* ボード設計チームでの対応があぶれてしまったものを一時的にSP2で開発を請けている格好になっている
* RSK系のBDFの開発責任者含め、BDF全体の責任者リストは以下
  * https://renesasgroup.sharepoint.com/:x:/s/k2reldoc_Project/301_SCPCPJ/EZELE1p5xKJAiWw0_zgZsxUBlHJ8lM-SeV7WfLbPjteq-g?CID=4D8377A1-C8F2-4E5C-9258-05402A537B7C&wdLOR=c092F3056-7750-47BC-8BCA-9FC074ABC2C0
* 2022/08/09追記
  * RSKチームの五十嵐さんと相談し、本GitLabに原本を登録いただくことにした
    * これでRXマイコン周りのBDFは一元管理ができた
      * 管理表によるとRZのBDFがいくつかあるようだが、これもそのうち一元管理できるようになると良いと考える

# 関係者と議論を行う場
* http://global-infra-jp-main.dgn.renesas.com/common/portal/-/issues/102
