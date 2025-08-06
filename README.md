自分自身に対するメモ

index.html を作る<br />
GitHubリポジトリのトップに index.html を作成します。

▼ 方法A：Web上で作る<br />
リポジトリにアクセス<br />
「Add file」→「Create new file」<br />
ファイル名に index.html と入力<br />
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

閲覧するには、GitHub Pages の公開設定が必要です。以下の手順で進めてください。<br />
リポジトリ上部メニューの「Settings」をクリック（右端にあります）<br />
左メニューの「Pages」をクリック<br />
「Branch」で main を選び、「/（root）」を選択<br />
「Save」ボタンをクリック

数秒後、「Your site is live at...」というURLが表示されます<br />
例）<br />
https://takase-hiroyuki.github.io/my_first_homepage/

そのURLをクリックすれば、誰でも閲覧できます。

