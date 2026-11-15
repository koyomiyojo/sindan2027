# 2027年 自分と家族の未来を育てる十干診断

## GitHub Pagesで公開する
1. ZIPをパソコンで展開します。
2. https://github.com/koyomiyojo/sindan2027 を開きます。
3. Add file → Upload files から、展開したフォルダーの「中身」をアップロードし、Commit changes を押します。
   リポジトリ直下に index.html、style.css、app.js、data.js、config.js、assets/ を配置してください。ZIPファイル自体や、外側のフォルダーをアップロードしないでください。
4. Settings → Pages → Build and deployment で Source を Deploy from a branch にします。
5. Branch を main、フォルダーを / (root) にして Save。
6. 公開処理完了後、https://koyomiyojo.github.io/sindan2027/ を開きます。

リポジトリは公開用に Public に設定してください。index.html がすでにある場合は本パッケージの内容で更新してください。

## 構成
index.html / style.css / app.js / data.js / config.js / assets/ / .nojekyll
ビルドやパッケージインストール、サーバープログラムは不要です。HTMLを直接開いても診断できます。すべての画像は同梱し、相対パスで参照しています。

## お問い合わせ先
config.js の contactUrl: "" に https:// で始まる連絡先URLを入力してください。現在は未設定で「準備中」と表示します。
guideImage は assets/guide.png です。水色の服のキャラクターを全箇所で共通利用しています。

## プライバシーと計算
ChatGPT・Apple等のログイン機能、アクセス解析、外部API呼び出しはありません。名前・生年月日はブラウザー内だけで計算され、サーバーへ送信・保存しません。再読み込みで入力内容は消えます。結果のコピーと印刷・PDF保存ができます。
日干はグレゴリオ暦からJDNへ変換し、2000-01-07=甲子から60日周期で算出。1900〜2026年の毎月15日、1,524日を別の暦計算と照合済み。うるう年・世紀年に対応。日付境界は0時とし、出生時刻・出生地補正は扱いません。
2027年は立春（2月4日）を年の切り替わりとして解説。月別アドバイスは季節の養生と日干の個性を組み合わせたもので、個人の正確な月運計算ではありません。
