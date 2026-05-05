# cheetsheet

## セットアップ

```powershell
uv sync
```

## 仮想環境を有効化

```powershell
.\.venv\Scripts\Activate.ps1
```

実行ポリシーで止まる場合:

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned
.\.venv\Scripts\Activate.ps1
```

## 起動

```powershell
uv run python gradio_app.py --server-name 0.0.0.0 --server-port 7860
```
