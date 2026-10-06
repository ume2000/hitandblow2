# ヒット&ブロー オンライン対戦

静的HTMLだけで動作するヒット&ブローです。
オンライン通信にはPeerJS/WebRTCを使用します。

## 公開方法（GitHub Pages）

1. GitHubで新しいリポジトリを作成する。
2. このフォルダの中身をリポジトリの `main` ブランチ直下へアップロードする。
3. `Settings` → `Pages` → `Build and deployment` → `Source` で `GitHub Actions` を選ぶ。
4. `Actions` の `Deploy to GitHub Pages` が成功すると公開URLが表示される。
5. そのURLを友達に送る。

GitHub PagesはHTML/CSS/JavaScriptの静的サイトを公開できます。
オンライン対戦のシグナリングはPeerJS Cloudを利用します。

## 遊び方

- 2人対戦または4人トーナメントを選ぶ
- ルームコードを作る
- 同じルームコードを友達に共有する
- カラー4色または数字4桁を選択
- 相手の答えをHit & Blowで推理する

※ホストのブラウザを閉じると、そのルームは終了します。
※通信環境によってはWebRTCの接続が成立しない場合があります。
