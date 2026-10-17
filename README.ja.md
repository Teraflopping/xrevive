# xrevive

### [**English**](README.md) · [**Deutsch**](README.de.md) · [**Français**](README.fr.md) · [**Español**](README.es.md) · [**Italiano**](README.it.md) · [**Português (Brasil)**](README.pt-BR.md) · [**Русский**](README.ru.md) · [**العربية**](README.ar.md) · **日本語** · [**简体中文**](README.zh-CN.md)

[Xrecomp](https://github.com/Teraflopping/Xrecomp) で再コンパイルした初代 Xbox ゲーム用のデスクトップランチャーです。オンラインサービスは Xbox Live 復活プロジェクト [xb.live](https://xb.live) が提供します。

## v0.1.14 をダウンロード

[Windows x64 版をダウンロード](https://github.com/Teraflopping/xrevive/releases/download/v0.1.14/xrevive_0.1.14_x64-setup.exe) · [Linux 版（AppImage）をダウンロード](https://github.com/Teraflopping/xrevive/releases/download/v0.1.14/xrevive_0.1.14_amd64.AppImage) · [すべてのインストーラーとリリースノート](https://github.com/Teraflopping/xrevive/releases/latest)

配信中のゲーム実行ファイルは現在 **Windows x64** に対応しています。Linux では Wine または Proton で実行できます（実験的）。macOS 版はまだゲームをプレイできません。

## 機能

- 手持ちの ISO または展開済みのゲームフォルダーを追加し、対応する実行ファイルをダウンロードします。Release ビルドがあればそれを使い、Beta や Alpha ビルドをインストールする前には確認します。対応ゲームのリージョンフリー版、メディアパッチ適用版、名前を変えたものや再署名したダンプも認識します。
- Release・Beta・Alpha のどのゲームもインストール前に閲覧できます：アクティビティ、アップデート、リーダーボード、実績、アドオン、リアルタイムのプレイヤー数とロビー数を表示し、ページ上から **INSTALL** できます。
- ゲームとランチャーのアップデートを自動確認。ゲームのアップデートは置き換えた古い実行ファイルを削除し、ゲームは近くのサーバーからダウンロードされ、接続が切れても続きから再開します。
- xb.live でサインイン（まずは Midnight Club 3 のオンラインから）し、フレンド、ライブ中のロビー、コミュニティイベント、リーダーボードを表示できます。xb.live がダウンしていても、ゲームはオフラインで起動します。
- インストール済みゲームの管理：プレイ、ローカルファイルの参照、アンインストール、そして DLC/Addons タブ。各 MOD に On/Off スイッチと作者のクレジットがあります。**▶ PLAY** は有効な MOD を入れてゲームを起動し、アドオンはゲームのアップデート後も動作します。
- セーブタブでバックアップ、復元、インポート、PS2 セーブの変換、Midnight Club 3 と NINJA GAIDEN Black のセーブエディターが使えます。
- シェーダーキャッシュはゲームと一緒に保存されるので、シェーダーのコンパイルは初回起動時だけです。
- 何が起きたか、どう直せばよいかを説明するわかりやすいエラーメッセージ。「コントロールされたフォルダー アクセス」がインストールをブロックした場合は **Allow xrevive in Windows Security** ボタンが表示されます。
- 設定 > 言語 でスペイン語、イタリア語、アラビア語を選べます。アラビア語ではウィンドウ全体が右から左に表示されます。
- インストール済みゲームを Steam に追加（設定またはライブラリから）。カバーアートと Deck での Steam Input に対応します。
- Windows 8.1 以降と Direct3D 11 のシステムチェック。それでもプレイすることもできます。
- Play を押すと、古い `XBL-Hosted` フォルダーにある XB Online のセーブが各ゲームの通常のセーブフォルダーにコピーされます。既存のセーブが置き換えられることはなく、何も削除されません。セーブを確認したら、`SaveData\XBL-Hosted` はご自身で削除できます。

## ゲームはご自身で

xrevive にはゲームの ISO やデータは含まれていません。ご自身のゲームファイルを使ってください。このバージョンはゲームをローカルでコンパイルする代わりに公開済みの実行ファイルをダウンロードします。実行ファイルがまだないゲームは、後で使えるよう展開しておけます。

Windows 版ランチャーとインストーラーは Authenticode 署名済みです。ランチャーのアップデートは xrevive のアップデート鍵で署名されています。macOS 版は公証（notarize）されていないため、macOS での初回インストール時にセキュリティの警告が表示されることがあります。

---

xrevive はファンプロジェクトです。Microsoft とは提携しておらず、Microsoft による承認も受けていません。
