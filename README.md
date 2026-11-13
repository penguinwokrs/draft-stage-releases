# Draft Stage（配布用）

League of Legends のカスタムゲームの BAN/PICK を、大会配信風の画面で表示する Windows アプリの配布場所です。カスタムゲームに観戦者として入った PC で使います。ソースコードはここにはありません。

> **アルファ版**です。機能や見た目は今後変わります。各版の内容は [Releases](https://github.com/penguinwokrs/draft-stage-releases/releases) のノートを見てください。

## インストール

1. [Releases](https://github.com/penguinwokrs/draft-stage-releases/releases/latest) から `Draft-Stage_*_x64-setup.exe` をダウンロードして実行する
   - コード署名がないため「Windows によって PC が保護されました」と出ることがあります。「詳細情報」→「実行」で進めてください
   - ユーザーごとのインストールです（管理者権限は不要）
2. 起動すると設定ウィンドウが開き、タスクトレイにアイコンが出ます

## 更新

起動時に新しい版を確認し、チャンピオン選択中・試合中でなければ自動で入れます（入れるときにアプリは一度終了します）。タスクトレイの「更新を確認」からも確かめられます。

## 使い方

1. 設定ウィンドウでチームを登録し、Blue 側と Red 側のチーム、BO と勝ち数、ルール、スキン、大きさを選ぶ
2. カスタムゲームのロビーに観戦者として入る。チャンピオン選択が始まると自動で進む
3. 表示先は設定ウィンドウの右上で選ぶ
   - **オーバーレイ**: 画面の上に重ねる（チャンピオン選択の間だけ出る）
   - **OBS**: ブラウザソースで `http://127.0.0.1:7781/` を開く（幅 1920、高さ 1080）

## 不具合・要望・質問 / Bug reports, requests, questions

[Issues](https://github.com/penguinwokrs/draft-stage-releases/issues/new/choose) から、テンプレートを選んで送ってください。何語で書いても大丈夫です。

Please open an [issue](https://github.com/penguinwokrs/draft-stage-releases/issues/new/choose) and pick a template. Any language is fine.

## 利用条件 / Terms of use

[利用条件](TERMS.md)（[English](TERMS.md#english)）の範囲で、個人・団体を問わず無料で使えます。配信・大会（参加費・賞金のある大会を含む）での利用に個別の許諾は要りません。再配布・改変・販売はできません。収益のある大会・配信で使うときは、概要欄・大会のページ・エンドクレジットのどれかに次のクレジットを入れてください（配信・動画・大会のページのどれも無い大会では、省略していただいてかまいません）。

    Draft: Draft Stage — https://github.com/penguinwokrs/draft-stage-releases

---

Draft Stage was created under Riot Games' "Legal Jibber Jabber" policy using assets owned by Riot Games. Riot Games does not endorse or sponsor this project.
