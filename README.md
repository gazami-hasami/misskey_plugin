[Misskey](https://misskey-hub.net/)で使えるプラグイン。[AiScript](https://github.com/syuilo/aiscript)で書かれている。

## opencw
指定したチャンネルのCWを自動的に開いて表示する。
CWが解除されたノートはCWの「もっと見る」ボタンがなくなり、代わりに"[CW]"が表示される。

対象チャンネルはプラグインの設定の「チャンネルID」にチャンネルIDを入力することで行う。対象チャンネルは半角スペースで区切って複数指定できる。対象チャンネルを指定しないとこのプラグインは何もしない。

設定「CWを開かない文字数」でテキストの長さによってCWを開くかを制御できる。指定した文字数を超えたCWは開かない。

## post_to_channel
投稿フォームに指定したチャンネルへ投稿先を変更するボタンを追加する。
投稿フォーム下の🔌マークからノートしたいチャンネルを選んでからノートすると対象のチャンネルに投稿される。
投稿対象のチャンネルはフォロー中のチャンネルを取得して表示する。

チャンネル内の投稿フォームでは投稿先の変更は行われない。投稿先を変更するボタンを押すとダイアログで「変更したよ」と表示されるが、投稿時にその投稿フォームを開いたチャンネルへ投稿される。

![使用例](https://user-images.githubusercontent.com/22396164/232288192-e1463141-45c1-4920-8d53-634a8954fe0e.png)
