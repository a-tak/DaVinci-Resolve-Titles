# DaVinci-Resolve-Titles

DaVinci ResolveのFusionで作成したEditページ用テンプレートです

## インストール

### Windows

`(インストールドライブ):\Users\(ユーザー名)\AppData\Roaming\Blackmagic Design\DaVinci Resolve\Support\Fusion\Templates\Edit\Titles` へsettingファイルをコピーしてDaVinci Resolveを再起動すると、カットやエディットページに各タイトルが表示されます。
(トランジションは `Titles` ではなく `Transitions`)

## お手軽に確認する方法

Fusionコンポジションつくって、settingのテキストの内容をノードでctrl + Vで貼り付けすることもできます。

## タイトル
### リストタイトル

テキスト欄ありますが、エディットページで段階的に文字表示することが出来なかったので、実際はここ使わずEditページで別のテキスト貼り付けたりしています。

(最初から入ってるテキストはサンプルです😀)

## ジェネレーター

### チャプタータイトル

Titlesの同名のものとは違って画面全体でチャプター表示する物。

Loderノードでロゴを読み込みしているので、環境に合わせてパスの変更が必要(パスを変更できるようにし忘れているので、今はマクロ内の文字列を直接書き換えないといけない)
