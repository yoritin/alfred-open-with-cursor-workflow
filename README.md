# Open With Cursor in Alfred

このWorkflowは、Alfredを使用して特定のファイルをCursorで簡単に開くことを可能にします。ファイル選択やフォルダ選択時にキーワードを使用することで、Cursorなどの指定したアプリケーションでファイルやフォルダを開くことができます。

## 機能

- **キーワードによる開き方**: `cursor` などのキーワードを使って、Finderで選択されているアイテムをCursorで開きます。
- **ファイル/フォルダアクション**: 選択したファイルやフォルダを右クリックして、Cursorで直接開くオプションを選択します。
- **POSIXパスのサポート**: 特定のファイルやフォルダのPOSIXパスを入力して開くことができます。`~/` はユーザーホームディレクトリに展開されます。

## インストール方法

1. [Open with Cursor.alfredworkflow](https://github.com/yoritin/open-with-cursor/blob/main/Open%20with%20Cursor.alfredworkflow)ファイルをダウンロードします。
2. ダウンロードしたファイルを開きます。
3. 「Import」を選択して、ダウンロードした`.alfredworkflow`ファイルをインポートします。

## 使い方

1. **キーワードを使用**: Alfredで`cursor`と入力し、Enterを押します。Finderで選択されているアイテムがCursorで開きます。
2. **ファイル/フォルダアクション**: Finderでファイルやフォルダを選択し、右クリックメニューからCursorで開くオプションを選択します。
3. **POSIXパスを入力**: Alfredで`cursor`と入力し、スペースを開けてから開きたいファイルやフォルダのPOSIXパスを入力します。

## 設定のカスタマイズ

- デフォルトの開き方を変更するには、WorkflowのApplescriptソースを編集してください。
- ユーザーホームディレクトリの代わりにデスクトップフォルダをデフォルトにするには、指定の行をコメントアウトし、別の行のコメントを解除します。

## サポート

何か問題がある場合や改善の提案がある場合は、GitHubリポジトリの[Issues](https://github.com/yoritin/open-with-cursor/issues)ページを通じてフィードバックを送ってください。
