# AGENTS.md

- 所有回應一律使用繁體中文。
- 專案語言為 Python（`iem_python` 為 Python 3.12），一律用 conda 管理套件，禁止用系統 `pip` 直裝。
- Conda 環境為 `iem_python`（路徑 `C:\Users\user\anaconda3\envs\iem_python`）；`conda` 不在 PATH，呼叫請用完整路徑 `C:\Users\user\anaconda3\Scripts\conda.exe`。
- 執行 Python / 安裝套件時免 `activate`，直接用 `conda run -n iem_python`（PowerShell 下 `activate` 常失效）：
  - 執行：`& "C:\Users\user\anaconda3\Scripts\conda.exe" run -n iem_python python <script.py>`
  - 安裝：`& "C:\Users\user\anaconda3\Scripts\conda.exe" install -n iem_python <pkg>`
- Repo 現況為綠地（僅 `.git/` + 本檔，無 manifests、無 CI）；選定建置 / 測試 / lint 流程後需回來補上確切指令。
