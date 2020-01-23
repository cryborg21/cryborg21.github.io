# windows_setup
- 想定OS：Windows10

# 設定

## 完全シャットダウン
- Shiftキーを押しながらスタート→シャットダウン
- 高速起動設定がされている場合、通常のシャットダウンだと完全には電源が落ちない。
- 再起動には影響しない。


## 検索の高速化
- Start→「インデックスのオプション」で検索
- 「変更」→不要なディレクトリからチェックを外す
- 「詳細設定」→「再構築」でインデックスを再構築する

# 一般・必須ツール

## Google Chrome
- Webブラウザ。メイン。
- https://www.google.com/intl/ja/chrome/
- 閲覧履歴の検索はマイアクティビティから
  - https://myactivity.google.com/myactivity

## Firefox
- Webブラウザ。サブ。
- Chromeでログイン中のサービスに別アカウントでログインしたい場合等に使用。
- https://www.mozilla.org/ja/firefox/

## Google日本語入力
- IME
- https://www.google.co.jp/ime/
- CapsLockキー無効化
  - http://forgetmenots.doorblog.jp/archives/53446561.html
- Ctrl-tもしくはF10で日本語入力のまま英字に一発変換
  - https://blogs.windows.com/japan/2016/09/27/jpimetips3/

## atom
- テキストエディタ
- https://atom.io/
- プラグイン
  - language-markdown
  - markdown-pdf もしくは markdown-themeable-pdf
  - markdown-scroll-sync
  - language-cmake

## visual studio code
- コードエディタ
- https://azure.microsoft.com/ja-jp/products/visual-studio-code/

## git for windows
- gitとbash。bash内でvimも使用可能。
- https://gitforwindows.org/

## TeraTerm
- ターミナルエミュレータ
- https://forest.watch.impress.co.jp/library/software/utf8teraterm/

## PDF X-change Editor
- タブ型PDF Viewer/Editor
- https://forest.watch.impress.co.jp/library/software/pdfxchedit/

## FavBinEdit
- バイナリエディタ
- https://www.wabiapp.com/FavBinEdit/

## Microsoft Office一式
- こればかりは買うしか無い。
- 会社でOfficeを使っている場合、HUP(HomeUsageProgram)を利用して安く買える場合がある。
  - https://www.microsoft.com/ja-jp/home-use-program/
- OneDrive上で、新規作成からWord,Excel,Powerpointファイルを作成し、ブラウザ上で編集できる。
  - 通常のデスクトップ版ほどの機能は揃っていないが、あまり凝ったことをしないのであれば十分。
  - プレゼンテーションスライドの作成が目的であれば、Google Slidesの利用も検討すべし。

# 画像

## ペイント
- 説明不要。Windows標準アプリ。3Dじゃない方。
- クロップは基本これで事足りる。

## Snipping Tool
- スクリーンショット撮影ツール。Windows10標準アプリ。
- ウインドウのスクショならAlt+PrintScreen、画面全体のスクショならPrintScreenしてからペイントにペーストでもよい。

## Irfan View
- 高速画像Viewer
- https://forest.watch.impress.co.jp/library/software/irfanview/

## Ralpha Image Resizer
- 複数画像を一括リサイズ。デジカメ撮影の高画質画像をWeb用に縮小する場合など。
- https://forest.watch.impress.co.jp/library/software/ralpha/

## Gaim
- 複数の静止画からGifアニメを作成
- https://forest.watch.impress.co.jp/library/software/giam/

## GifCam
- デスクトップ動画をキャプチャしてGifアニメを作成
- https://gifcam.jp.uptodown.com/windows

# 音声

## Audacity
- 音声ファイル編集
- https://forest.watch.impress.co.jp/library/software/audacity/

## Mp3tag
- 音楽ファイルのタグ情報を一括書き換え
- https://www.gigafree.net/media/mu/mp3tag.html

# 動画

## VLC Media Player
- 再生用。
- キーバインド
  - Spaceキーで再生/一時停止、「キーで再生速度UP、」キーで再生速度Down
  - Shift+Left/Rightでほんの少し戻る/進む
  - Alt+Left/Rightで少し戻る/進む
- お気に入り設定
  - 字幕/OSD：ビデオ開始時にメディアタイトルを表示：チェックを外す
  - インタフェース：ビデオのサイズ荷インタフェースをリサイズ：チェックを外す
  - インタフェース：ビデオの最終フレームで一時停止：チェック
  
## フォト(Windows10標準アプリ）
- 動画の再生だけでなく、時間方向トリミング・複数画像の連結ならこれで可能。
- 動画ファイル右クリック→プログラムから開く→フォト
  - 動画だけど「フォト」アプリで開く
- 左上の「作品に追加」→「新しいアルバム」もしくは既存のビデオプロジェクトに追加
- 「1項目を追加されました。"ビデオの表示"」と出るので"ビデオの表示"をクリック、もしくは「すべての写真を見る」→「ビデオプロジェクト」
- ビデオプロジェクトファイルの場所は隠蔽されており、「フォト」アプリ以外からはアクセスできません。
- 編集過程を残さなくて良いのなら、編集・変換用のプロジェクトを一つ用意しておき、毎回そこに元動画を追加・削除していくと便利。

## shotcut
- https://shotcut.org/download/
- 動画編集用。社用PCのWindows10だと「フォト」アプリが削除されているため。
- 時間方向トリミング・複数画像の連結ならこれで可能。
- 書き出し形式は一番下の「デフォルト」で大概問題ない。gifでの書き出しも可能。
- オープンソース：https://github.com/mltframework/shotcut

## OBS Studio
- https://obsproject.com/
- デスクトップ録画用。
- 主にライブ配信やYoutuber向けに作られているソフトだが、画面録画用途としても大変使いやすい。
- そのため「録画開始」の隣に「配信開始」ボタンがあり、押してしまいそうだが、押したとしても配信先サービスのアカウントが登録されていなければWeb上に垂れ流されることはないので心配無用。
- 使い方：https://vip-jikkyo.net/how-to-use-obs-studio
- オープンソース：https://github.com/obsproject/obs-studio
