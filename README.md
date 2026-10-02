# FDE Desktop for Windows

**[下载 Windows 安装包 · Download · ダウンロード](https://github.com/pmodev988/fde-releases/releases/download/v0.6.0/FDE-Desktop-Setup-0.6.0.exe)** · [版本说明 · Release notes · リリース説明](https://github.com/pmodev988/fde-releases/releases/tag/v0.6.0) · [全部版本 · All releases · すべてのリリース](https://github.com/pmodev988/fde-releases/releases)

[公开签名证书 · Public certificate · 公開署名証明書](https://github.com/pmodev988/fde-releases/releases/download/v0.6.0/codesign.cer) · [SHA-256 校验文件 · Checksums · チェックサム](https://github.com/pmodev988/fde-releases/releases/download/v0.6.0/SHA256SUMS)

## 中文

本仓库提供 FDE Desktop 的 Windows 安装包、SHA-256 校验文件和公开签名证书。

当前公开版本为 **0.6.0**，支持 Windows 10／11（64 位）。安装需要管理员权限；未安装 WebView2 运行时时，安装器会联网下载安装。

安装包使用 injapan 的**自签名证书**签名并带时间戳。Windows 可能提示未知发布者或 SmartScreen 警告；请先核对文件摘要与签名证书指纹，详细步骤见版本说明。

升级前，安装器会备份本机 FDE 数据。卸载会保留本机数据和备份。请先阅读版本说明再安装或升级。

## 日本語

FDE Desktop の Windows インストーラー、SHA-256 チェックサム、公開署名証明書を配布しています。

現在の公開バージョンは **0.6.0** です。Windows 10／11（64 ビット）に対応し、インストールには管理者権限が必要です。WebView2 ランタイムがない場合は、インターネット経由でダウンロードしてインストールします。

インストーラーは injapan の**自己署名証明書**で署名され、タイムスタンプが付いています。Windows に不明な発行元や SmartScreen の警告が表示される場合があります。ファイルのハッシュと署名証明書の拇印を確認してください。詳しい手順はリリース説明をご覧ください。

アップデート前にローカルの FDE データをバックアップします。アンインストールしてもデータとバックアップは保持されます。インストールや更新の前にリリース説明をお読みください。

## English

This repository distributes FDE Desktop Windows installers, SHA-256 checksums, and the public signing certificate.

The current public version is **0.6.0**, for Windows 10/11 (64-bit). Installation requires administrator rights. If the WebView2 Runtime is missing, the installer downloads and installs it using an internet connection.

The installer uses an injapan **self-signed certificate** with a timestamp. Windows may display an unknown-publisher or SmartScreen warning. Verify the file hash and signer thumbprint; see the release notes for detailed instructions.

The installer backs up local FDE data before an update. Uninstalling preserves local data and backups. Read the release notes before installing or upgrading.
