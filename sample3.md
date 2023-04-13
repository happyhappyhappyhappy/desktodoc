# ChatGPTで作成するプレゼン資料

## 目次

- [ChatGPTで作成するプレゼン資料](#chatgptで作成するプレゼン資料)
  - [目次](#目次)
  - [ ChatGPTとは？](#-chatgptとは)
  - [ Marp for VS Codeとは？](#-marp-for-vs-codeとは)
  - [ スライド作成手順](#-スライド作成手順)
  - [ おわりに](#-おわりに)

## <a name="chatgpt"></a> ChatGPTとは？

- GPTとはGenerative Pre-training Transformerの略です。
- 自然言語処理タスクにおいて強力な性能を発揮するAIモデルです。
- 学習済みのChatGPTを利用することで、簡単に文章生成ができます。

## <a name="marp"></a> Marp for VS Codeとは？

- Markdownを用いてスライドの作成ができるソフトです。
- VS Codeと統合して使うことができます。
- デザインテーマやカスタムスタイルも多数用意されています。

## <a name="procedure"></a> スライド作成手順

1. Marp for VS Codeをインストールしてください。
2. 新しいMarkdownファイルを作成し、次のように設定してください。

   ```yaml
   ---
   theme: default
   paginate: true
   ---
   ```

3. スライドを記述してください。`---`の行で新しいページを作成します。キーボードショートカット`alt+enter`で挿入可能です。

   ```markdown
   # スライド1

   これはスライド1です。

   ---

   # スライド2

   これはスライド2です。
   ```

4. 画像など必要な要素を追加してください。画像はファイルパスを指定するだけで利用できます。

   ```markdown
   # 画像の挿入

   ![サンプル画像](./sample.png)
   ```

5. スライドをプレビューして、修正してください。

## <a name="conclusion"></a> おわりに

- ChatGPTとMarp for VS Codeを利用することで、簡単にプレゼン資料を作成できます。
- Markdownを利用することで文章の編集も直感的に行えます。
- ぜひチャレンジしてみてください！
