*****************************************************
ＹＭ用　輝夜口上　Ａ→ＹＭ移植版　Ver1.00
*****************************************************

※この口上はrev6でテストプレイをしながら製作しました

1.概要
 1,5口上の仕様
2.その他
3.更新履歴

-----------------------------------------------------------------
1.概要
-----------------------------------------------------------------

Ａ用の輝夜口上をＹＭに移植しつつ、仕様に合わせて色々加筆・改変しました。

様々な事がありましたが、ついにVer1.00
つまり、正式版として稼働する事ができる訳ですね。

様々な口上……いや、名前挙げた方がいいかな
YM用依姫口上、RRの咲夜口上、スター口上、やぁふぁフラン口上、早苗口上、A用の雛口上、霊夢口上、RR用の輝夜口上には特にお世話になりました。

IRCの人達や掲示板の人達にはお世話になっていただきありがとうございます。

----------------------------------------
1,5.口上の仕様
----------------------------------------

Ver0.80から豊姫を主人にした時の口上を追加しました。
依姫を助手にしてあると開始時の口上が変化する上に触手調教時に体力的な面で有利になります。
基本的な流れとしては屈服1～3→恋慕と淫乱を付ける→売却or解放となります。


ちなみにproto21ではREVERSALモードでもエンゲージリングを送る事ができるので
豊姫が主人の状態での輝夜の個別エンドを見る事ができます。
（ただし豊姫主人時の独自の奴隷エンドは用意していません）

一部口上がしつこいかも知れませんが、まあEXTRAモード専用なので悪しからず。



-----------------------------------------------------------------
2.その他
-----------------------------------------------------------------

人を選ぶようなイベントを遠慮無く発動させるモードを投入してあります。
最初の問いで99を入力してください。
（ただしこのモードでも選択式のイベントはあります）


Ａ用とＹＭ用の作者：toroiya
平仮名でもカタカナでも英語でもいいです。

今更ですが、夜這い口上は夜這いイベントの内容が汎用化される前に書いた物なので
現在のＹＭでは対応し切れていない可能性がかなり高いです。

-----------------------------------------------------------------
3.更新履歴
-----------------------------------------------------------------

11/07/14　Ver1.10
・指チュパの口上を追加
・フェラチオ時に分岐を追加
・自慰口上を一部追加
・動物性愛経験が一定以上で永琳が助手だと輝夜を猫化させられるイベントを追加（今のところ調教開始時しか変わらない）
それぞれにメイド服のコスプレをしてたり、羞恥プレイ中だと分岐がかかるようにしました。


11/03/01　Ver1.00
今回は既存口上の補強および修正に力を入れるよ！
いや…まあ、今まで追加してきたのが余りにも狭い範囲ばかりだったので
たまには広範囲の補強でより充実できるようにしようかと…
・岩清水の口上を加筆しました。
・テンプレで見てニプルキャップまでの調教口上を改修しました
・絶頂時の口上、従来は部位ごとには分かれていなかったのですが今回からは部位ごとに口上を用意
　（従来の口上の前に表示されます）


11/01/27 Ver0.95
・選択肢で三択以上出た場合、2以降の選択肢を選択できない不具合を修正
・薬物刻印を持った状態だと調教開始時と終了時に口上が変わるようにしました。
　薬物刻印Lv3だと絶頂時の口上が変化するようにしました。
・調教開始時の一部の条件でTALENT:オトコになってたのをTALENT:PLAYER:オトコに修正
・調教対象が居ない状態で輝夜を売却しようとすると起こるエラーを修正しました
　（つまり売却後エピソードをRev6仕様に合わせました）
・特定の条件を満たして薬物刻印がLv3だと放尿時の口上が変わったりします
・永琳が助手の時の調教開始時の口上を実装しました
・首筋耳裏舐めの口上を追加しました


10/11/28 Ver0.91
・幼児退行時の口上とアナルセックス時の口上辺りの構文にＬｖ2相応のバグがあったので修正

10/11/27　Ver0.90
・アナル正常位、アナル後背位、犬に犯させる、豚に犯させる、馬に犯させるの口上を追加しました
・幼児退行時の取得後の初調教時、調教開始時、調教終了時の口上とエンディングを追加しました



10/08/19　Ver0.85
・助手無しで初回調教を開始すると落ちる不具合を改善
　（陥落してない妹紅助手時に初調教をすると起きる条件分岐がASSIのNOを参照するのに
　　ASSI > 0を入れて短絡評価させなかったのが原因）
・proto30辺りで一文字変数が撤廃された事によって正常に動作しなかった
　酒恥肉倫の口上の処理を変更
・動作には関係ないらしいのですが、Lv2の警告が気分よくなかったので
　二択は別関数を作って、そこでループを一括化して解決しました。
・解決方法を教えてくださったみなさん。ありがとうございます！

10/08/18　Ver0.80
・調教中に狂気、精神崩壊時には別の反応をするようにしました
・調理時の口上を追加しました
・解放時の口上を追加しました
・売却時の口上を追加しました（一部特殊なので注意）
・売却後エピソードも追加しました
・乳首ローター、髪扱き、フィストファック、アナルフィスト、両穴フィスト、触手催眠、剃毛、お酒を飲ませる、
　触手Ｇスポ責め、杭、ナイフの口上を追加しました
・恋慕かつ主人のセックスによる処女喪失時の口上でTFLAG:20を指定していたのをTFLAG:2に修正しました
・豊姫を主人にした時の口上を追加しました

10/02/03　Ver0.70
・触手強制飲酒中にコマンドを選択した時の口上を追加
・助手が妹紅の時、あるいは主人が妹紅の時の口上を少しだけ追加（マゾッ気がLv3以上の時に表示）
・人を選ぶようなイベントを解放している時に特定の条件を満たしてスターを助手にした場合の口上を追加
・胸揉み、乳首責め、放尿時の口上を追加（移植）しました
・焦らしプレイ中に絶頂に達した時のフラグの加算が間違ってるのを修正しました
・睡眠中関連の口上を補強しました
・人を選ぶようなイベント時の特殊イベントが進行してる時に開始時の口上が変わるようにしました
・体力0時の口上を移植しつつ更に追加、移植してきた物に蓬莱人じゃなくなった時の口上を追加しました
・パイズリで射精時、セックスで膣内射精時、アナルセックス時に射精した時の口上を追加しました

10/01/20　Ver0.60
・一部の口上で男性だけにしか対応していなかった点を修正
・奴隷エンディングが表示されなかった点を修正
・誤字修正
・恋慕+反発刻印Lv3の状態だと売却口上が表示されなかったのを修正
・ボールギャグ・触手口辱・強制開口器装着時にコマンドを実行すると専用口上が表示されるようにしました
・助手が居ない状態で野外プレイを行うと止まるバグと
　助手が居ない状態で野外プレイ時に何もしないを選ぶと止まるバグを修正しました

10/01/15　Ver0.50
・とりあえずVer0.50として完成


































・時期が来たらやるべき事
触手催眠失敗時（判定処理どうやって入れるかを後で考察）




素質変動させる要素がＡと違ってＹＭには結構多いので薬で素質変動させる要素は削りました
…が、薬物刻印Lv3時に売却をした時の口上を新たに用意しました
…妹輝夜？何の事です

なにかバッドエンド的な要素を用意したいけど蓬莱人なせいで死亡口上が書けないという
一応書いてあるけどこれリザレクションするの前提だし
何らかの原因で蓬莱人が外れた時用の口上を用意してないとシュールな状況が生まれてしまうかも知れない