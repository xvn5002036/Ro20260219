# Ro20260219

2026-02-19 RO 客戶端主程式專案。

## 重要提醒

本儲存庫是公開的。請勿上傳遊戲帳號、密碼、資料庫密碼、GitHub Token、後台密碼或其他私人資料。

大型檔案（例如 GRF、EXE、DLL、ZIP、7Z）已設定由 **Git LFS** 管理。第一次上傳前，電腦必須先安裝並啟用 Git LFS。

## 第一次下載

```bat
git lfs install
git clone https://github.com/xvn5002036/Ro20260219.git
cd Ro20260219
```

## 放入主程式後上傳

先把 RO 主程式複製到 `Ro20260219` 資料夾內，再執行：

```bat
git add .
git commit -m "加入 2026-02-19 RO 主程式"
git push origin main
```

## 之後下載完整大型檔案

```bat
git clone https://github.com/xvn5002036/Ro20260219.git
cd Ro20260219
git lfs pull
```

如果檔案總量超過 GitHub 帳號的 Git LFS 儲存或流量額度，推送仍可能失敗；屆時應將完整客戶端壓縮包改放 GitHub Releases 或其他大型檔案儲存空間。
