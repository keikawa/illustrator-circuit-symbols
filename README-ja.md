# Illustrator 回路記号シンボル

回路図やブロック図をAdobe Illustratorで描くためのシンボルライブラリです。

## 使い方と推奨設定

1. **Schematic-Symbols.ai** をダウンロードします。
2. Illustratorで **Window > Symbols** を開き、パネル左下の **Symbol Libraries Menu > Other Library…** からダウンロードしたファイルを選びます。
3. ライブラリパネルから記号をアートボードへドラッグします。
4. **View > Show Grid** と **View > Snap to Grid** を有効にします。
5. **Edit > Preferences > Guides & Grid**（Windows）で **Gridline every: 5 px**、**Subdivisions: 5** に設定します。macOSではIllustratorの環境設定から **Guides & Grid** を開きます。

配線には **Pen Tool (P)** を使い、**Fill: None**、黒の **Stroke: 1 pt** に設定してください。

配置した記号だけを編集するには、選択してSymbolsパネルの **Break Link to Symbol** を使います。シンボル定義を編集すると、同じドキュメント内のリンクされた記号も変更されます。

## 作図用ファイルとカテゴリ別ライブラリ

新しく図を描く場合は **Schematic-Starter.ai** を **File > Open…** で開き、**File > Save As…** で別名保存して使えます。シンボルが登録済みで、Symbols / Wires / Labels のレイヤーを用意しています。

カテゴリごとにパネルを分ける場合は、**Other Library…** から **Categories** 内の `.ai` ファイルを開いてください。

[Example-RC-Filter.ai](Example-RC-Filter.ai) は、RCローパスフィルタとバッファの作図例です。

## ライセンス

[MIT Licence](LICENSE)

元データ：[affinity-circuit-symbols-asset](https://github.com/keikawa/affinity-circuit-symbols-asset)
