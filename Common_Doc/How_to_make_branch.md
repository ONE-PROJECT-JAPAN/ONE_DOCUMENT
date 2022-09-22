# branchの作成・削除の方法

1. git Bash を起動しましょう
   
   ![hoge](/Image/execute_git_bash.png) <br><br>

2. branchを作るリポジトリーへ移動しましょう
userのディレクトリーからであれば以下のコマンドで移動できます。<br>
※今回はONE_DOCUMENTのbranchを作ってみす。<br>

   ```sh
   cd git/ONE_DOCUMENT
   ```
   以下のように`ONE_DOCUMENT`のディレクトリーにいればOK<br>
   ※執筆者の環境では`work/`配下にいるので下記のようになっている。<br>
   併せて`ONE_DOCUMENT`の後ろの`main`にも注目。<br>
   ここには現在いる自分のいる`branch`が表示される。
   ![hoge](/image/cd_repository.png)

3. `main branch`をベースに新たに`branch`を作ろう。<br>
   以下コマンドで**今いる自分のいるbranch**をベースにbranchを作ることができる。 <br>
   `[branch_name]`の箇所は任意の名前に置き換えよう。
   ### ブランチ命名規則 <br>
   基本的に以下の通り命名をすること<br>
   `yyyymmdd_UserName_BranchName`<br>
   BranchNameは変更点がわかりやすい名前にすること<br>


   ```sh
   git checkout -b [branch_name]
   ```
   以下のように`branch`が作成できると作成した`branch`に切り替わる<br>

   ![hoge](/image/checkout_mk_branch.png)

   
4. `branch`の一覧を確認する。<br>
   `git branch`コマンドで確認できる。
   ```sh
   git branch
   ```
   ![hoge](Image/../../Image/show_branch.png)

5. `main branch`へ移動
   `git checkout`コマンドで移動しよう。<br>
   ディレクトリー名の右側が`(main)`になればOK
   ```sh
   git checkout [branch_name]
   ```
   ![hoge](/Image/switch_branch.png)

6. 作成したbranchを削除<br>
   ときは `branch -D`コマンドで行える<br>
   `-D`の部分は大文字、小文字で意味が変わるので注意しましょう。
   ```
   git branch -D [branch_name]
   ```
   削除した後に`git branch`を実行して削除されたことも確認
   ![hoge](/image/delete_branch.png)

　　
7. チュートリアル終了
   