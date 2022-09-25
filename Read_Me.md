  <link href=".\css\StyleSheet.css" rel="stylesheet"/>
 

# Read Me

チームに新たに参加した方は必ず目を通しておいてください。

## 目的
このプロジェクトは学習を目的としたプロジェクトなので各自で設計、製造し
みんなでレビューして良いものをMergeして開発していくことを目的としています。
みんなに共有できる技術はこのONE_DOCUMENTのリポジトリーで更新していきましょう。
<br>

共有技術共有のドキュメントの追加は`/Doc`にドキュメントを追加して`Index.md`にリンクを張ってください。
お願いします。
`Read_Me`に関するドキュメントは`/Common_Doc`にドキュメントを追加して`Read_Me.md`にリンクを張ってください。



<br><br>

# リポジトリールール

### ブランチについて
基本的に`main`ブランチは`Push`禁止です。
無料枠の中で管理している関係上mainブランチに`Push`できてしまうため注意してください。

万が一`Push`してしまった場合にはチームディスカッションで報告をお願いします。こちらで復元を行います。

### ブランチ命名規則
基本的に以下の通り命名をすること
`yyyymmdd_UserName_BranchName`
BranchNameは変更点がわかりやすい名前にすること

### 開発進行について
開発進捗についてはプロジェクトのタスクスレッドで共有すること。<br>
ソースレビューを依頼したい場合には、対象の`branch`を`Push`したあとPRでDraftを発行しメンションをつけて共有すること。

### 開発環境について
visual studio 2022で進めていいます。
※古いバージョンだとサポートされていない可能性があるので注意してください。

<br><br>

# 環境準備とツールWiki


## Visual_Studio_Code

- [ダウンロードリンク](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)
- [日本語表示化](https://digitor.jp/textbook/vscode-japanese/)
- [プラグイン一覧](./Common_Doc/Recommend_Plugin_Fro_Visual_Studio_Code.md)
- [文字エンコードのデフォルトをUTF-8にする](https://www.javadrive.jp/vscode/setting/index4.html)
  
## Git_Hub
- [Git_Hubアカウントの作成方法](https://jiyuta.com/github-account/)
<br><br>

## Visual_Studio_2022
- [ダウンロードリンク](https://visualstudio.microsoft.com/ja/vs/whatsnew/)
- [インストール](./Common_Doc/HIow_To_Intall_Visual_Studio.md)
- [プラグイン一覧]()←工事中
- [おすすめ設定]()←工事中
- [使い方]() ←工事中
<br><br>

## Git
 Gitは学習と慣れのためにGitBashを使用しましょう
- [Gitとは](https://wa3.i-3-i.info/word12778.html)
- [ダウンロードリンク](https://gitforwindows.org/)
- [インストール手順](https://qiita.com/suke_masa/items/404f06309bb32ca6c9c5)
- [GitBashの使い方](https://www.granfairs.com/blog/staff/gitbash-setting-shortcut)

<br><br>

# チュートリアル
1. [リポジトリークローンの作成](./Common_Doc/Gow_To_Clone_Repojitories.md)
2. [main_branchを最新化(pull)](./Common_Doc/How_To_Pull.md)
3. [branchの作成・削除](./Common_Doc/How_to_make_branch.md) [←そもそもbranchとは？](https://backlog.com/ja/git-tutorial/stepup/01/)
4. [ソースファイルを編集する(Visual_Studio_Code編)](./Common_Doc/How_To_Edit_File_Visual_Studio_Code.md)
5. [ソースファイルを編集する(Visual_Studio_2022編)]()←工事中
6. [`git commit`して変更を確定させる。]()←工事中
7. [`git push`してGitHubにブランチを上げる]()←工事中

