# Open Source Guide

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | **日本語** | [Русский](README.ru.md)

初めてのオープンソース貢献、ステップバイステップ

## 翻訳 初めてのオープンソースへの貢献、ステップバイステップ

##1. 初心者に優しいプロジェクトを見つける

- https://goodfirstissue.dev — プロジェクト全体で`good first issue`をキュレーション
- GitHubのトピック検索: [`good-first-issue`](https://github.com/topics/good-first-issue)
- ドキュメントと翻訳は最も簡単なエントリポイントです。すべてのプロジェクトはそれらを望んでいます

##2. ワークフローを理解する

```
fork → clone → branch → edit → commit → push → pull request → review → merge
```

-**Fork** = 自分のサーバー側のコピーをプッシュできます
-**Branch** = `main`では動作しません。
-**PR** = あなたの提案+それについての議論

##3.受け入れられるPR

- `CONTRIBUTING.md`を最初に読む — 常に
- PRごとに1つの変更 — 小さなビートが大きい
- 説明する**なぜ**、単なるものではなく、メンテナーはコンテキストをマージし、コードではなく
- レビューで反応する - あなた放棄された死ぬPR

##4. 安全に最初に練習する

目的作り付けのサンドボックス(判断なし、ボットは即座にマージします):

- [first-pull-request](https://github.com/aixisstudio/first-pull-request) - あなたの最初のPR
- [add-your-name](https://github.com/aixisstudio/add-your-name) — コントリビューターの壁に参加

##5. レベルアップ

- 課題→再生→修正:信頼の梯子
- 回答ディスカッション — メンテナーはヘルパーを覚えています
- 一貫性はバーストを打ちます: 1つの小さなPR /週は実際のプロファイルを構築します

## 🔬 不慣れなコードベースを読む方法

1. `README.md` + `CONTRIBUTING.md` — 意図
2. `git log --oneline -50` — 何が積極的に変化するのか
3. テスト — ドキュメントよりも優れた動作を文書化
4. 記入項目を見つけて下さい、1つの要求に終りに続いて下さい
5. `rg "TODO|FIXME|HACK"` — メンテナーが痛むことを知っているところ

## 📬 最初のPR — etiquette

-**Smallは尊重されます**:typoの修正>半壊れ目の特徴
-**最終10マージPRを読む**:プロジェクトのレビュースタイルを教える
- **「この上で働くことができる」と尋ねないでください**:一度PRまたはコメントを開くだけで、簡単に
- **条件付きコミット**: `feat:`, `fix:`, `docs:` — ログを最初に確認する
-**CI red = unmergeable**: ローカルでチェックを実行する

## 本当に知る価値のあるプログラム

| プログラム | 受賞 |
|---|---|---|
| ハクトバーフェスト | みんな | デジタルリワード |
| Google Summer of Code | 学生 | 素早い + メンターシップ |
| MLHフェローシップ | 学生 | リモートインターンシップ |
| アウトリーシー | 代表 | $7k インターンシップ |
| Sovereign Tech Fund | メンテナー | 資金調達 |

## ライセンス クイック決定

| ご希望の | おすすめ |
|---|---|
| 「ジャストユース」 | MIT |
| クレジット + 特許保護 | Apache 2.0 |
| シェアライク | GPL-3.0 |
| ドキュメント・コンテンツ | CC-BY-4.0 |
| パブリックドメイン | ライセンス |

---
## 貢献

プルリクエストを歓迎します。レビューしてマージします。[aixisstudio](https://github.com/aixisstudio) による管理 — オープンソースのアプリケーションファイアウォール [Snitch](https://github.com/aixisstudio/Snitch) の作者です。

## ライセンス: MIT
