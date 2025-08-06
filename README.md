自分自身に対するメモ

index.html を作る

GitHubリポジトリのトップに index.html を作成します。

▼ 方法A：Web上で作る

リポジトリにアクセス

「Add file」→「Create new file」

ファイル名に index.html と入力

以下のような簡単なHTMLを貼り付ける：

 <pre>
&lt;!DOCTYPE html&gt;
&lt;html lang="ja"&gt;
&lt;head&gt;
  &lt;meta charset="UTF-8" /&gt;
  &lt;title&gt;高瀬浩之のホームページ&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
  &lt;h1&gt;こんにちは！&lt;/h1&gt;
  &lt;p&gt;これは私のはじめてのGitHub Pagesホームページです。&lt;/p&gt;
&lt;/body&gt;
&lt;/html&gt;
  </pre>

閲覧するには、GitHub Pages の公開設定が必要です。以下の手順で進めてください。

リポジトリ上部メニューの「Settings」をクリック（右端にあります）

左メニューの「Pages」をクリック

「Branch」で main を選び、「/（root）」を選択

「Save」ボタンをクリック

数秒後、「Your site is live at...」というURLが表示されます

例）
https://takase-hiroyuki.github.io/my_first_homepage/

そのURLをクリックすれば、誰でも閲覧できます。

