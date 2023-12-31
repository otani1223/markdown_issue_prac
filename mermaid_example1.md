# mermaidとは

Mermaid とは、コードベースでガントチャートやフロー図などの作図が可能となるJavaScriptのライブラリです。
2022年にGitHubやQiitaでもサポートされるようになり、Markdownの中に専用のコードを書くことで図の挿入が出来るようになりました。

GitHubでもMermaidに対応した為、 README.md などに図を挿入するハードルが非常に下がったものかと思います。
従来は別のツールで作成した画像を別サーバに置いたり、GitHub内のwikiやissueなどに画像をアップロードし、URLをコピーしてMarkdownに記述……などなど、非常に多くの手間がかかっていました。

そういったこともあり、最近は自分自身もMermaidを書く機会が増えましたが、普段コーディングやMarkdownの記述に使っているVSCodeでMermaidも書けると便利だな、ということで、VSCodeでMermaidを書く環境を整えました。
今回は環境作りの際にインストールした拡張機能や設定について紹介していきます。

## mermaid記法をプレビューに表示する

VSCodeはデフォルトでもMarkdownのプレビューは出来ますが、Mermaid記法は認識してくれず、以下のようにただのコードとして表示されてしまいます。
※プレビューを並べて表示する場合はコマンドパレットで Markdown: Open Preview to the side を選択

そこで、プレビュー時にMermaid記法で記述したコードを図として表示する為に必要な拡張機能をインストールします。


### Markdown Preview Mermaid Support

## 使い方

拡張機能をインストールするだけで、特に設定を変更することなくプレビュー時に図が表示されるようになります。
先ほどのコードも、拡張機能インストールした後は以下のようにガントチャートが表示されるようになりました。

## mermaid記法をハイライト表示に

IDEを使っているのであれば、白と黒だけでは味気ないし見づらい時に丁度いい、Mermaid記法をハイライト表示してくれる拡張機能。

### Mermaid Markdown Syntax Highlighting

## 使い方

この拡張機能もインストールをするだけで設定する必要もなく使用できる。
導入するだけでMermaid記法で記入した部分の色を変える