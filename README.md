# AI-Market-Research

AI ツール・サービス市場の最新動向を調査し、Markdown レポートとして蓄積するリポジトリ。

## ディレクトリ構成

```
AI-Market-Research/
├── SKILL.md              # Claude スキル定義
├── README.md
└── YYYY-MM/              # 年月フォルダ（例: 2026-03/）
    ├── YYYY-MM-DD.md     # 日次レポート
    └── ...
```

## セットアップ

### 1. SSH キーの発行と設定

`gorilla-muscle` アカウント専用の SSH キーを作成する。

```bash
ssh-keygen -t ed25519 -f ~/.ssh/id_ed25519_gorilla -C "gorilla-muscle"
```

パスフレーズは任意。生成後、公開鍵を GitHub に登録する。

```bash
cat ~/.ssh/id_ed25519_gorilla.pub
```

出力内容を GitHub → Settings → SSH and GPG keys → New SSH key に貼り付ける。

次に `~/.ssh/config` へ以下を追記する。

```
Host github-gorilla
  HostName github.com
  User git
  IdentityFile ~/.ssh/id_ed25519_gorilla
```

接続確認:

```bash
ssh -T git@github-gorilla
```

`Hi gorilla-muscle!` と表示されれば成功。

### 2. リポジトリのクローン

```bash
git clone git@github-gorilla:gorilla-muscle/AI-Market-Research.git /workspace/AI-Market-Research
```

### 3. git config の設定

GitHub コントリビューション（草）を正しく記録するため、リポジトリごとに設定する。

```bash
cd /workspace/AI-Market-Research
git config user.name "gorilla-muscle"
git config user.email "nozomi.muscle.10.02@gmail.com"
```

## 使い方

Claude で以下のように実行する。

```
/ai-market-research
```

レポートは `YYYY-MM/YYYY-MM-DD.md` に直接作成・コミットされる。リモートへのプッシュは手動で行う。
