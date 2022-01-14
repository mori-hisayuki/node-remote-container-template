# ディレクトリ構造

```
|--.devcontainer // remote containerの設定
|  |--devcontainer.env
|  |--devcontainer.json
|  |--docker-compose.yml
|  |--amd
|     |--Dockerfile
|--.WebApp // アプリケーション本体
|--.gitignore
|--.editorconfig
|--README.md
```

## awsへの接続
ローカル環境の`~/.aws`ディレクトリをマウントしているため、接続先情報はローカルに依存する

## Githubへの接続
AWS同様に`~/.ssh`ディレクトリをマウントしているため、接続先情報はローカルに依存する

接続情報が追加されたknown_hostsをsshディレクトリに追加する

## 環境変数
`.devecontainer`の直下に`devcontainer.env`ファイルを配置すると読み込まれる


## default Extension(上から順)
###
- Vim
- Git Graph
- gitflow
- vscode-icons
- indent-rainbow
- Code Spell Checker
- Tabnine AI Autocomplete
- Live Server
- Live Share
- EditorConfig for VS Code

### node用
- Auto Rename Tag
- ESLint
- Prettier
- Jest Runner
- Path Autocomplete
- Path Intellisense
