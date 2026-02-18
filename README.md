# 🔮 Lucky Compass — 全占術統合 開運ナビ

**APIキー不要 • 完全無料 • GitHub Pagesで動作**

![Lucky Compass](https://img.shields.io/badge/Lucky%20Compass-v2.0-gold)
![License](https://img.shields.io/badge/license-MIT-blue)
![No API Key](https://img.shields.io/badge/API%20Key-不要-green)

## ✨ 特徴

- **完全オフライン動作** — Anthropic APIキー不要
- **全15種占術統合** — 西洋占星術・タロット・数秘術・ルーン・東洋占星術・風水・四柱推命・紫微斗数・0学・姓名判断・九星気学・おみくじ・六曜・算命学・血液型
- **毎日変わる結果** — 日付＋生年月日のシード値で日替わり算出
- **5タブ構成** — 今日の運勢・ガチャ占い・今日の開運・月間カレンダー・設定

## 📱 機能一覧

| タブ | 機能 |
|------|------|
| 🔮 今日の運勢 | 総合スコア・ラッキータイム・スポット・フード・全占術詳細 |
| 🎰 ガチャ占い | 33ゲーム対応ランキング・引くべき時間・ルーティン |
| ✨ 今日の開運 | アニソン・フード・おすすめ本・ラッキーカラー |
| 📅 月間カレンダー | 日別運気・ガチャ最適日表示 |
| ⚙️ 設定 | 星座・干支・九星・姓名など個人設定 |

## 🚀 GitHub Pages へのデプロイ手順

### 方法①：GitHub.com からアップロード（推奨・一番簡単）

1. [github.com](https://github.com) にログイン（アカウントがなければ無料登録）
2. 右上の「＋」→「New repository」をクリック
3. Repository name に `lucky-compass` と入力
4. 「Public」を選択して「Create repository」
5. 「uploading an existing file」をクリック
6. `index.html` をドラッグ＆ドロップ
7. 「Commit changes」ボタンをクリック
8. リポジトリの「Settings」→「Pages」→「Branch: main」→「Save」
9. 数分後に `https://あなたのGitHubユーザー名.github.io/lucky-compass/` で公開！

### 方法②：Git コマンド（開発者向け）

```bash
git clone https://github.com/あなたのユーザー名/lucky-compass.git
cp index.html lucky-compass/
cd lucky-compass
git add .
git commit -m "🔮 Lucky Compass v2.0"
git push origin main
```

GitHub の Settings → Pages → Branch: main → Save

## 📖 使い方

1. ページを開く
2. 「⚙️ 設定」タブで星座・干支・九星気学・姓名を入力（初回のみ）
3. 「📍 現在地を取得」ボタンで位置情報を取得（任意・精度UP）
4. 「✨ 今この瞬間の運勢を占う」ボタンをタップ！

## 🔧 カスタマイズ

`index.html` 内の以下の部分を編集してください：

```html
<!-- デフォルト値の変更 -->
<input id="bdate" value="1993-04-14">  ← 生年月日
<input id="situation" value="宮崎市 イオンモール">  ← デフォルト場所
<option value="酉" selected>酉</option>  ← 干支
<option selected>六白金星</option>  ← 九星
```

## 📜 占術一覧

1. **西洋占星術** — 12星座×日付の周期で算出
2. **タロットカード** — 日替わりカードドロー（大アルカナ12枚）
3. **数秘術** — 生年月日から命数を計算
4. **ルーン占い** — 10種のルーン文字から日替わりドロー
5. **東洋占星術** — 干支×月の周期
6. **風水** — 吉方位・ラッキーカラー算出
7. **四柱推命** — 天干地支の組み合わせ
8. **紫微斗数** — 14の主星から命宮を算出
9. **0学占い** — シード値ベース算命
10. **姓名判断** — 姓名の画数から総格算出
11. **九星気学** — 九星×月の飛泊位置
12. **おみくじ** — 7段階（大吉〜大凶）重み付き抽選
13. **六曜** — 大安・友引・先勝など日別算出
14. **算命学** — 生年月日ベース算出
15. **血液型占い** — A・B・O・AB型別日替わり

## ⚖️ License

MIT License — 自由に使用・改変・配布可能

## 🙏 クレジット

Lucky Compass — Powered by 全占術統合アルゴリズム
