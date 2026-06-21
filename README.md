# こころの特性スクリーニング

自分の特性や傾向を手軽にセルフチェックできる、無料のWebツールです。  
医療的診断ではなく、専門家への相談のきっかけや自己理解の参考としてご利用ください。

**→ [ツールを使ってみる](https://mitubuchi.github.io/mental-screening/)**

---

## 収録スクリーニング（11種）

| スクリーニング | 問数 | 参考基準 |
|---|---|---|
| ADHD（注意欠如） | 9問 | DSM-5 / ASRSベース |
| ADHD（多動・衝動） | 9問 | DSM-5 / ASRSベース |
| ASD傾向 | 10問 | 独自構成 |
| うつ病 | 9問 | PHQ-9ベース |
| 不安障害 | 7問 | GAD-7ベース |
| 社交不安 | 7問 | 独自構成 |
| コミュニケーション障害 | 7問 | 独自構成 |
| 感覚処理過敏 | 8問 | 独自構成 |
| 双極性障害 | 8問 | MDQベース |
| PTSD | 9問 | PCL-5ベース |
| HSP（高感受性） | 10問 | エレイン・アーロン尺度ベース |

---

## 主な機能

- **テストの選択** — 受けたいスクリーニングをチェックボックスで選択（複数選択可）
- **合計問数の確認** — 開始前に「X種・合計Y問」を表示
- **連続受検** — 選択したテストを順番に連続して受検
- **カテゴリ別スコア** — 各テストの結果をカテゴリごとに可視化
- **結果ダッシュボード** — 受検したすべてのテスト結果を一覧比較
- **PDF保存** — 結果レポートをPDFでダウンロード（jsPDF使用）
- **Claudeへの相談** — 結果をもとにAIにアドバイスを求める連携機能

---

## 使い方

1. 受けたいスクリーニングにチェックを入れる
2. 「選択したテストを開始」をクリック
3. 各質問に回答（「次へ」で進む）
4. 個別結果 → ダッシュボードで全体を確認
5. 必要に応じてPDFで保存

---

## 技術仕様

- **構成**: HTML / CSS / JavaScript（単一ファイル）
- **サーバー不要**: すべてブラウザ内で完結
- **外部ライブラリ**: [jsPDF](https://github.com/parallax/jsPDF)（PDF生成のみ、CDN経由）
- **データ保存なし**: 回答・結果はブラウザ外に送信・保存されません

---

## ローカルで使う

```bash
# リポジトリをクローン
git clone https://github.com/mitubuchi/mental-screening.git

# index.html をブラウザで開くだけで動作します
```

---

## 免責事項

- このツールは**医療的診断ではありません**
- 結果はあくまで傾向の参考であり、確定診断には専門家の診察が必要です
- スコアが高い場合でも、必ずしも該当する疾患・障害があるわけではありません
- 正確な診断・治療については、精神科・心療内科・発達障害専門クリニックにご相談ください

### 緊急の場合

気持ちがつらいとき、誰かに話を聞いてほしいときは以下へご連絡ください。

| 相談窓口 | 電話番号 | 受付時間 |
|---|---|---|
| よりそいホットライン | 0120-279-338 | 24時間・無料 |
| こころの健康相談統一ダイヤル | 0570-064-556 | 都道府県により異なる |
| いのちの電話 | 0120-783-556 | 毎日16時〜21時、毎月10日は8時〜翌8時 |

---

## 参考文献・出典

- **PHQ-9**: Kroenke K, Spitzer RL, Williams JB. (2001). The PHQ-9. *J Gen Intern Med*, 16(9), 606-613.
- **GAD-7**: Spitzer RL, et al. (2006). A brief measure for assessing generalized anxiety disorder. *Arch Intern Med*, 166(10), 1092-1097.
- **ASRS**: Kessler RC, et al. (2005). The World Health Organization Adult ADHD Self-Report Scale (ASRS). *Psychol Med*, 35(2), 245-256.
- **PCL-5**: Weathers, F.W., et al. (2013). PTSD Checklist for DSM-5. National Center for PTSD.
- **MDQ**: Hirschfeld RM, et al. (2000). Development and validation of a screening instrument for bipolar spectrum disorder. *Am J Psychiatry*, 157(11), 1873-1875.
- **HSP尺度**: Aron, E.N. & Aron, A. (1997). Sensory-processing sensitivity and its relation to introversion and emotionality. *J Pers Soc Psychol*, 73(2), 345-368.

---

## ライセンス

MIT License — 非商用・商用を問わず自由にご利用いただけます。  
ただし、各質問票の原著作権は各著者・団体に帰属します。

---

*このツールはセルフケアと自己理解のために作られました。あなたの一歩を応援しています。*
