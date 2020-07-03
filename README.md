# 卒業制作-2019年度生
- [シラバス](https://1drv.ms/x/s!Anf4PowESFUjg_to0KzjF6rMyHSnRQ?e=87OYJz) > 学校開始の遅れによりコンテスト応募がなくなったので、無理のないようにリスケします(6/10)

# 参考URL
- MayaからUnityに読み込む
  - [インポートの時の制限](https://docs.unity3d.com/ja/2018.4/Manual/HOWTO-ImportObjectsFrom3DApps.html)
  - [他のアプリケーションからのエクスポート](https://docs.unity3d.com/ja/2018.4/Manual/HOWTO-exportFBX.html)
- [Unityの命名規則](http://am1tanaka.hatenablog.com/entry/2019/12/06/101055)
  - [シートひな形](https://docs.google.com/spreadsheets/d/1MV--pg9RYgMXMCftDIoX7AJAxXn95eMiCc0f8-SL5U8/)
- [GitHubの開発フロー](https://sketchboard.me/LBSAHzZ8ynEE)
- [Visual Effect Graphサンプル](https://blogs.unity3d.com/jp/?s=visual+effect+graph+sample)
- [テラシュールブログ. Unity 2017の新しいスプライトをパッキングする仕組み、”SpriteAtlas”について](http://tsubakit1.hateblo.jp/entry/2017/05/04/233000)
- [Unity Japan. Unity道場2D編 ライティングで差をつけろ！（6月9日号）](https://youtu.be/Km_4NQPk59s)
- [UnityのプロジェクトをGitで管理するように設定して、GitHubにPublishする手順](https://github.com/dat19/gp1/blob/master/github-unity.md)
- [GitHubの自分のプロジェクトが壊れた場合](https://docs.google.com/document/d/1HlV70sEMS8G3eLAD6YMuIObY7hei7YdaXKObGV9EpYg/)
- [ArtStation. Art&Designのショーケース](https://www.artstation.com/)
- [Pinterest](https://www.pinterest.jp/)
- [Disney Research Studios.](https://studios.disneyresearch.com/)
- [XR-HU3. パーティクル徹底解説！基本的なモジュールの使用方法から応用例まで](https://xr-hub.com/archives/3522)
- [STYLY. パーティクルを覚える](https://styly.cc/ja/tips/unity-introduction-particle/)

# 素材例
- [ぐらびぃ](Resources/Graviy.unitypackage) > View rawをクリック

# 年間の予定
- 6月～7月 試遊作品の完成とポートフォリオの充実(フェーズ1)
- 11月 正式版の開発。展示版の作成 / Webで公開(フェーズ2)
- 2月 DVDに焼いて、パッケージの作成 / Webで公開(フェーズ3)

# MAYAのシェーダー(マテリアル)について
- Stinger PBS, Lambert, Phongを使う
  - Arnoldはレイトレ用の設定なので、UnityやUEでは読み込めない。他エンジンで利用する場合はStinger PBSなどを使う
  - セルシェーダーなど、特殊な塗りを使いたい場合も同様にゲームエンジン側で動く必要があるので、設定はゲームエンジンで

# 6週目
## 予定
- 試遊のための作業
- ポートフォリオを進める
- 新設を検討しているノベルのためのキャラ確認


# 5週目
## 現状共有
- [Google Meet](https://meet.google.com/yav-uzhd-wjq)

## 話題
- [Naughty Dog The Last of Us Part II Art Blast](https://magazine.artstation.com/2020/06/naughty-dog-the-last-of-us-part-ii-art-blast/?fbclid=IwAR1EidrUgiwOeoqpC5lq4__F5IascmqYeQVd_Hun5WSXzmA1Vm2qducK0vA)
  - [感想ツイート](https://twitter.com/Kouji_Tajima/status/1278481964513628160)
- [paiza開発日誌. 新卒向け・企業に聞いた！「応募者を面接で落とした理由」ランキング【エンジニア編】](https://paiza.hatenablog.com/entry/2018/03/30/%E6%96%B0%E5%8D%92%E5%90%91%E3%81%91%E3%83%BB%E4%BC%81%E6%A5%AD%E3%81%AB%E8%81%9E%E3%81%84%E3%81%9F%EF%BC%81%E3%80%8C%E5%BF%9C%E5%8B%9F%E8%80%85%E3%82%92%E9%9D%A2%E6%8E%A5%E3%81%A7%E8%90%BD%E3%81%A8)
  - これらのことを念頭において、面接で今の制作物について紹介する時のことを想定しながら作業を進めよう
- [CGWORLD学生CGトライアル「WHO'S NEXT?」2020年第2弾作品募集スタート！作品締切：7/31（金）](https://cgworld.jp/news/event/whosnext07.html)
  
## 予定
- 企画や仕様についてヒアリングをして、不明点を列挙する
- MayaからUnityへのデータの渡し方
  - [インポートの時の制限](https://docs.unity3d.com/ja/2018.4/Manual/HOWTO-ImportObjectsFrom3DApps.html)
  - [他のアプリケーションからのエクスポート](https://docs.unity3d.com/ja/2018.4/Manual/HOWTO-exportFBX.html)
  - [Maya. Stingray 物理学に基づいたシェーダを作成する](https://knowledge.autodesk.com/ja/support/maya/learn-explore/caas/CloudHelp/cloudhelp/2016/JPN/Maya/files/GUID-13B0F0A6-39D5-4668-A722-DD743877D2E3-htm.html)
  - [UnityのPBR(Physically based rendering)](https://docs.unity3d.com/ja/2018.4/Manual/shader-StandardShader.html)
    - 最終出力先がUnityならUnityで動く必要がある。UnityのPBRを知っていることは有利。ツールであれば[Substance Designer](https://www.borndigital.co.jp/software/1000.html)
    - Unreal Engineでも事情は同じ [映像制作におけるUE4の活用～マテリアル設計～](https://www.unrealengine.com/ja/blog/ue4-material)
- グラフィックデータのやりとりの方法を確認(命名規則とネットドライブ)
- 仮グラフィックを組み込んで、軽く操作できるものを目指す
- 各自作業を進める

## メモ
### 飛行機の不具合
- 原因
  - 速度が出る前に回転が発生すると、回転が止まらなくなる
  - また、RigidbodyのUse Gravityがないと動作が安定しない
  - 以上が重なって動作が不安定になったものと思われる。
- 解決策
  - RigidbodyのUse Gravityを有効にする
  - タイヤの位置などにSphereColliderやBoxColliderを配置して、飛行機が沈んだり、飛び立つ前に転がらないようにする
  - 地面にも当たり判定を入れて、飛行機が沈まないようにする


# 4週目
## 内容
- 企画や仕様についてヒアリングをして、不明点を列挙する
- グラフィックデータのやりとりの方法を確認(命名規則とネットドライブ
- 仮グラフィックを組み込んで、軽く操作できるものを目指す
- 各自作業を進める



# 3週目
## 話題
- [paiza開発日誌. 6/1時点の内定率は56.9%！就活再開で巻き返す方法とは](https://paiza.hatenablog.com/entry/2020/06/15/%E3%80%9021%E5%8D%92%E3%80%916/1%E6%99%82%E7%82%B9%E3%81%AE%E5%86%85%E5%AE%9A%E7%8E%87%E3%81%AF56_9%25%EF%BC%81%E5%B0%B1%E6%B4%BB%E5%86%8D%E9%96%8B%E3%81%A7%E5%B7%BB%E3%81%8D%E8%BF%94%E3%81%99%E6%96%B9)
- [バンダイナムコスタジオ. インターンシップ](https://bandainamcostudios.snar.jp/index.aspx?id=Q30FqP_l6BU)
- [CGWORLD](https://cgworld.jp/magazine/cgw259.html)
- [ArtStation. Art&Designのショーケース](https://www.artstation.com/)
- [Disney Research Studios.](https://studios.disneyresearch.com/)

## 参考：ラフ絵の利用
- [森田/イクシール. パンチ、キックのコンビネーション](https://note.com/ixill_morita/n/n88ed086f0bcd)
- [Toon Boom. ビデオコンテとは](https://blog.toonboom.com/ja/%E5%8B%95%E7%94%BB%E3%82%B3%E3%83%B3%E3%83%86%E3%83%93%E3%83%87%E3%82%AA%E3%82%B3%E3%83%B3%E3%83%86%E3%81%A8%E3%81%AF%E7%9B%B4%E6%84%9F%E7%9A%84%E3%81%AB%E7%90%86%E8%A7%A3%E3%81%A7%E3%81%8D%E3%82%8B%E7%B5%B5%E3%82%B3%E3%83%B3%E3%83%86)

## 今週、完了させたいこと
- Unityのプロジェクトを作成して、想定した解像度でビルド
- 仮のグラフィックを組み込んでビルドして、フルスクリーンで雰囲気を確認する
  - Recorderを組み込んでスクリーンショットを作成。Trelloで共有する
- 画面レイアウト、キャラクターの大きさ、UIのレイアウトについて、暫定値を決める

## 進捗に応じて、以下を実施
- グラフィックの命名方法と、Unityフォルダー内での配置を決める
- ポートフォリオに記載する想定で、キャラクターの設定を考える
- 2Dイメージのフォーマット、作り方について個別に講義
- 3DオブジェクトをUnityへインポートする方法
- GitHubでの作業練習

## 命名規則
- [Google Drive](https://drive.google.com/drive/)
  - グラフィック素材のファイル名や制作担当者、進捗などを共有する
  - [シートひな形](https://docs.google.com/spreadsheets/d/1MV--pg9RYgMXMCftDIoX7AJAxXn95eMiCc0f8-SL5U8/)


# 2週目

## 2日目
### Bグループ
- 作業割り振りの確認
- 3Dモデルの読み込み方法の調査

### Cグループ
- 初回説明
- プログラマーのうちの一人
  - Trelloで卒業制作用のチームを作成
  - チームに、メンバーを追加
  - チーム用の新しいボードを作成して、作品名にする
  - これまでに決まっている仕様や、必要そうな作業をカードで作成

### Aグループ


### 共通
- Unityプロジェクトの作成とGitHubリポジトリー作成
- GitHubにチームメンバーを加える
- 共有ドライブ
  - キャラクターCGコースの皆さんは、プロジェクトに組み込むためのデータができたら、決められたフォルダーに、決められたファイル名でコピーする
  - 更新したら、Trelloなどで報告
  - 原則として、プログラマーは報告されたデータをその日のうち、遅くとも、次の講義までに組み込み、制作者に見せる
- 作業の割り振りについて相談

### 参考
- [AUTOMATON. 一方方向ローグライクRPG『片道勇者プラス』](https://automaton-media.com/articles/newsjp/20200607-126557/)
- [4Gamer.net. 作品の価値を摩耗させないために](https://www.4gamer.net/games/223/G022384/20160826078/)



### フェーズ1
画面の魅力とゲーム性を確認するために、最小規模でゲームを仮実装する。

|ステップ|キャラクターCG|プログラム|
|-:|:-|:-|
|1|・仮グラフィック作成(粗いものでよい。色、大きさ、アニメの枚数を揃える)<br>・作業待ちや完了したらポートフォリオ作成|・Unityのプロジェクトを作成して、チーム開発できるようにGitHub上で共有<br>・重要なシーンから仮グラフィックを表示|
|2|・ポートフォリオに使えるようにゲーム素材を仕上げる<br>・挙がった修正点を反映させる|・仮グラフィックを組み込み全員で確認。修正点をリストアップ|
|3|・グラフィックを仕上げる|・ゲームの操作、ルールを実装|


### 企画の作り方 / チーム開発
- Unity1週間ゲームジャムLT
  - [マミーさん. チーム「密会取り締まり委員会」の発表](https://youtu.be/-qWwYVWgczA?t=6093)・・・チーム開発について
  - [EIKIさん. ゴリラが人類を強制的にSTAY HOMEさせるゲーム](https://youtu.be/-qWwYVWgczA?t=6719)・・・アイディアの転がし方、発注、ペース、進め方
  - [tnkさん. 「斬新さ」から考えるゲーム開発](https://youtu.be/-qWwYVWgczA?t=3002)・・・プランナー的視点、斬新なアイディア
- 2018年度生の作品の紹介
  - [Greening](https://youtu.be/YIH_g-8d4dU)
  - [はんぐらびぃStage1](https://www.youtube.com/watch?v=m1n--Ws1IyA) / [Stage2](https://youtu.be/MbufuWRoShQ) / [Stage3](https://youtu.be/dDulxJgI45o)
- 開発環境の準備と利用の練習
  - キャラクターCGの人たちは、GitHubアカウントとTrelloアカウントの作成
    - [作業メモ](https://docs.google.com/document/d/1bRQoVxfwsWoijGeEbPVwCFM9jctwKr6NfTxcPaXZflw/)
  - プログラマーの人たちは、決まった作品について以下のことを決める
    - 画面の解像度
    - 開発する項目をリストアップして、順番を検討する
    - Unityプロジェクトを作成して、PrivateでGitHubにPublish
- [Trello](https://trello.com)
  - チームの作成
  - ボードの作成(仕様 / Backlog / TODO / Check / Done)
    - 仕様
      - 企画の参考資料やゲーム画面サイズ、ストーリー、参考URL、使用アセット、メンバー情報などのカードを作成
    - Backlog
      - まだ手を付けていない作業
      - 思いついた作業のカードをこのリストに作成する
    - TODO
      - 作業を開始した項目を、BacklogからTODOに移す
      - 期限と担当者を決める
    - Check
      - 実装を完了したらTODOからCheckに移す
      - チーム内で動作確認をする
      - 問題点や修正が必要になったら、Backlogに戻すか、期限を更新してTODOに戻す
    - Done
      - 問題なく動作したら、CheckからDoneに移して作業完了



# 1週目
- 卒業制作の方針
- 自己紹介と希望の作品
- チーム分け
  - TPS / ローグライク / 箱庭謎解き / カードバトル
- 企画のブレインストーミング

## 1回目
### 卒業制作の方針
- ガイダンス [シラバス](https://1drv.ms/x/s!Anf4PowESFUjg_to0KzjF6rMyHSnRQ?e=8VnPAU)
- [ポートフォリオ基本のき　メモ](https://docs.google.com/document/d/10oJlWgdlyhmemeEHsd87exYVEapaZo3ePxTKDKSICBc/)
  - [ポートフォリオ基本のき](https://cgworld.jp/special/entrylive-online/vol1/channel/104/)


### 自己紹介と希望の作品
配布した紙に記入ののち、自己紹介と希望の作品の発表。サーバーを使う場面を検討。

#### キャラクターCG ジャンル
- 2D手書き / 2D人物 / 2D背景 / Live2D / 2Dドット
- 3Dモデリング / 3Dリギング / 3Dアニメ / 3Dキャラクター / 3Dオブジェクト
- ユーザーインターフェース
- 魔法や爆発、打撃などのエフェクト
- 動画


#### プログラマー
- 2D or 3D
- ノベル / カード・ボードゲーム / アクション / シューティング / RPG
- PC / Web / ネットワークPC / スマホ

ガチャ、ログボ、ランキングなどで構わないので、サーバーを利用する機能を検討して欲しい。

### 企画のブレインストーミング
- チームの仮決め
- ゲームデザインの復習
  - 参考：1週間ゲームジャムの振り返り会
  - ゲームの案のまとめかた
  - 世界観、プレイヤーの設定、目指すもの、ルールについて案を出す
    - 誰かの紙の裏に、ブレインストーミングして出た言葉を書きまくる
  - サムネイル
    - ゲームのイメージを小さくラフに描いたものを、別の人の紙の裏に描きまくる

### 発表
チームごとにブレストの結果発表。

まとまってなくてよい。出たアイディアや方向性を代表者に発表してもらって、他のチームから意見をもらう。
