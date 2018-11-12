## 目次
 - [必須](#必須)
 - [レイアウト](#レイアウト)
 - [シンボル・スタイル管理](#シンボルスタイル管理)
 - [検索・置換](#検索置換)
 - [ハンドオフ・遷移図](#ハンドオフ遷移図)
 - [操作系](#操作系)
 - [その他](#その他)

## 必須
### Sketch Runner
https://sketchrunner.com/

macOSのSpotlight機能のように、Sketchの機能、シンボル、プラグインなどを呼び出せるショートカットプラグインです。便利なプラグインが増えてくると、キーボードショートカットを割り当てられる空きが少なくなってきます。そんなときSketch Runnerを起動してプラグイン名を入れれば、キーボードを打つだけで素早く起動できます。

### [InVision Craft](https://www.invisionapp.com/craft)
プロトタイピング・コラボレーションプラットフォームであるInVisionが開発・提供しているプラグインです。Sketchプラグインの中でも突出した性能を備えており、1つのプラグインで以下の機能が使えます。

- InVisionにアートボードを同期
- レイヤーや色、テキスト情報の保存・同期
- ファイル内にあるオブジェクトからスタイルガイドを生成
- テキストや写真をオブジェクトに反映
- Webサイト上のコンテンツ（テキスト、写真）をオブジェクトに反映
- JSON APIからコンテンツをオブジェクトに反映
- コンテンツの複製

### Symbol Organizer
https://github.com/sonburn/symbol-organizer

Symbolsページに格納されているシンボルを並び替えできるプラグインです。水平／垂直の並び方向、階層を含んだ並び替えなどが可能です。Symbolsページは気がつくとごちゃごちゃしてしまいがちなので、定期的にSymbol Organizerを適用して整理することで、全体の構成を見渡せたり、命名がおろそかになっているシンボルを発見するのに役立ちます。

### Automate
https://ashung.github.io/Automate-Sketch/

Sketchの基本機能を拡張してくれるプラグインです。Automateを入れるだけで
- 選択した複数レイヤーのマージンを指定した数値に揃える
- レイヤーのX／Y位置に応じてレイヤーリストを並び替え
- 特定の種類のレイヤーだけを選択する
- グリッドやガイドのコピー&ペースト
など、100種類近くの機能が使えるようになります。  

## レイアウト
### Anima Toolkit
https://animaapp.github.io/Auto-Layout/

オブジェクトに対して位置／サイズの指定を設定することで、レスポンシブなオブジェクトが作れるプラグインです。このプラグインを使うことで、1つのオブジェクトでサイズの異なる状態の確認ができるようになります。
他にも指定したマージンを保ってくれる「Stacked Group」の作成や、有料ですがSketch上のレイアウトをそのままWebサイトとして公開できる「Launchpad」、アニメーションGIFを作成できる「Timeline」もあります。


## シンボル・スタイル管理
### Symbol Manager
https://gumroad.com/l/sketch-symbols-manager

シンボルをFinderのように一覧管理できるプラグインです。半角スラッシュの階層がフォルダで表現されており、ドラッグ&ドロップで位置の入れ替えができたり、シンボル名のリネームが可能です。

### Symbol Instance Renamer
https://github.com/sonburn/symbol-instance-renamer

インスタンスのレイヤー名をシンボル名にリネームしてくれるプラグインです。初期フェーズではシンボル名を考えるのを後回しにしがちですが、このプラグインを使うことで後からでもレイヤー名を整えられます。適用範囲は「すべてのページ」「現在見ているページ」「選択したアートボード」「選択したインスタンス」など状況に応じて変えられます。

### Symbol Instance Locator
https://github.com/sonburn/symbol-instance-locator

選択したシンボル／インスタンスを一覧表示してくれるプラグインです。一覧から選択すると該当するレイヤーに移動し、作成したシンボルがどこで使われているかを把握できます。

### Move to Library
https://github.com/ahmedmigo/Move-to-library-sketchplugin

選択したシンボル／インスタンスをLibraryに移動できるプラグインです。移動したシンボルのインスタンスはすべてLibraryのシンボルとして置き換わります。

### Styles Generator
https://github.com/lucaorio/sketch-styles-generator

選択したレイヤーからスタイルを一括で作成できるプラグインです。レイヤー名がそのままスタイル名になるので、例えば12pt/left／12pt/center／12pt/rightといったレイヤー名のテキストを作成してプラグインを使えば、一気にテキストスタイルが3つ作成できます。最初にスタイルを用意するタイミングで使用すると効果的です。

### Layer Style Manager
https://gumroad.com/l/sketch-shared-styles-manager

Symbol Managerのレイヤースタイル版です。Symbol Managerと同様に、階層ごとにフォルダで分けられていたり、階層間の移動やリネームが可能です。

### Text Style Manager
https://gumroad.com/l/sketch-text-styles-manager

Symbol Managerのテキストスタイル版です。Style Managerと同様に、階層ごとにフォルダで分けられていたり、階層間の移動やリネームが可能です。

### Shared Style Finder
https://github.com/sonburn/shared-style-finder

スタイルが適用されているレイヤーを一覧表示できるプラグインです。一覧から選択すると該当レイヤーに移動します。

### Shared Text Styles
https://github.com/nilshoenson/shared-text-styles

テキストスタイルをインポート／エクスポートできるプラグインです。このプラグインを活用することで、例えばさまざまなプロジェクトに応用できるマスターファイルを作成し、プロジェクトの初期からテキストスタイルが用意された状態のファイルを作成できるようになります。

### Unused Style Remover
https://github.com/sonburn/unused-style-remover

どのレイヤーにも適用されていないスタイルを一覧表示し、削除できるプラグインです。  

## 検索・置換
### Rename It
https://github.com/rodi01/RenameIt

選択したArtboard／Layerの名称を変更できるプラグインです。単に打ち込んだテキストに変えるだけでなく、テキストの置換や英数連番の追加、元レイヤー名の入れ込みなど、リネームに欲しい機能がひととおり揃っています。

### Font Finder
https://github.com/ukn530/FontFinder

いま開いているページ内で使われているフォントを一覧で表示してくれるプラグインです。チェック項目を入れると、そのフォントが適用されているレイヤーだけを選択状態にできます。不要なフォントが紛れ込んでいないかチェックするのに役立ちます。

### Font Mixer
https://github.com/littlebusters/Sketch-Font-Mixer

選択したテキストレイヤー内のテキストを、英語やひらがな、数字などの条件をもとに他のフォントに置換できるプラグインです。

### Presto Selecto
https://github.com/sonburn/presto-selecto

条件を指定してレイヤーを一括選択できるプラグインです。レイヤーの種類やレイヤー名に含まれるテキストなどを条件に含むことができます。

### Select Similar Layers
https://github.com/wonderbit/sketch-select-similar-layers

Adobe Illustratorのように、選択したレイヤーと同じ情報を持っているレイヤーをまとめて選択できるプラグインです。  

## ハンドオフ・遷移図
### Sketch Measure
http://utom.design/measure/

Canvas上にオブジェクトの情報やマージンなどを記載できるプラグインです。また、各種情報をHTMLとして出力することもできます。
開発側とコミュニケーションする際には、実装に必要な情報を得られるドキュメントの作成が必須です。後述のZeplinやInspectはネットワーク利用が前提のサービスですが、Sketch Measureはオフラインで全てが完結するので、オンラインサービスを使うのが難しい場合はSketch Measureの利用を検討してみてください。

### User Flows
https://abynim.github.io/UserFlows/

Sketch上で画面遷移図が作れるプラグインです。通常の作業に支障が出ないように、生成される線がロックされていたり、アートボードを動かしても位置を再調整してくれるなど、親切な作りとなっています。

## 操作系
### Nudge, Push, Shove.
http://nudgepushshove.com/

アートボードやレイヤーをカーソルキーで動かす時の距離を変えられるプラグインです。また、⇧＋カーソルキーより1段階大きく移動できるコマンドも備えています。

### Handy Tools
https://github.com/webpatch/Handy-Tools

Adobe Illustratorのように、オブジェクトの整列をする際に基点となるオブジェクトを指定できたり、複数オブジェクトのマージンを指定できるプラグインです。



## その他
### Midnight
https://midnightsketch.com/

Sketchをダークモードに変えられるプラグインです。その他にもツールバーのアイコンを変更できたり、レイヤーリストのインデント表示やカラータグの追加もできます。

### Material Theme Editor
https://material.io/tools/theme-editor/

Material Designのガイドラインに沿ったテンプレートをもとに、オリジナルのテーマを作成・カスタマイズできるGoogle製のプラグインです。初めてAndroidのアプリを作る時などに活用できます。

### SVGO Compressor
https://github.com/bohemiancoding/svgo-compressor

Bohemianが公式で提供しているSVG圧縮プラグインです。インストールすれば、あとは自動的に「Make Exportable」から書き出すSVGを圧縮してくれます。

### PDF Export
https://github.com/DWilliames/PDF-export-sketch-plugin

Sketchが標準で搭載しているPDF出力よりも細かい設定ができるプラグインです。選択したアートボードのみ出力、PNGデータをPDFとしてまとめる、などの機能が使えます。

### Stark
http://www.getstark.co/

色覚障害のシミュレートやコントラストのチェックができるプラグインです。

### Place Linked Bitmap
https://github.com/frankko/Place-Linked-Bitmap

画像に外部リンクの設定を付与できるプラグインです。
