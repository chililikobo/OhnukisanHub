# Ohnuki-san Hub

[![Latest Release](https://badgen.net/github/release/chililikobo/OhnukisanHub)](https://github.com/chililikobo/OhnukisanHub/releases/latest)
[![Downloads](https://badgen.net/github/assets-dl/chililikobo/OhnukisanHub)](https://github.com/chililikobo/OhnukisanHub/releases/latest)
[![License](https://badgen.net/badge/license/Free%20%2F%20Commercial/purple)](#editions--licensing)
[![Platform](https://badgen.net/badge/platform/Windows%2011%20%2F%2010%20%2F%20Server/black)](https://chililikobo.github.io/en/ohnuki-san-hub.html)

[English](#english) | [日本語](#日本語)

---

## English

Ohnuki-san Hub is the companion management console for the standalone Windows PC IT asset scanner **Ohnuki-san** (`OhnukiSan.exe`). It allows you to create zero-install portable scanner packages for offline or on-site Windows PCs and aggregate collected HTML reports into fleet KPIs, interactive charts, and Excel-ready CSV ledgers.

### Key Features
- **Zero-Install Portable Scanner Creation**: Export the embedded `OhnukiSan.exe` (and optional Pro key file `ohnuki-pro.dat`) as a ZIP archive, ready-to-run folder/USB package, standalone `.dat` file, or standalone Free executable.
- **Multi-PC Analytics Dashboard**: Load Free and Pro HTML reports via folder selection or drag-and-drop. Inspect 5 clickable KPI cards, 4 cross-filtering donut charts (Manufacturer, OS, OS Version/Build, Chassis), quick filter pills, a 1-click **Compare: All Files** / **Ledger: Latest / PC** mode toggle, and a categorized property inspector.
- **Unlimited Excel-Ready CSV Export**: Export aggregated asset inventory data to UTF-8 (with BOM) CSV files ready for Microsoft Excel with no limits.
- **Standard (Free) & Detailed (Pro) Audit Modes**: Collect core hardware, OS, storage, network, security, users/groups, software, updates, printers, and paths in Free mode; unlock VPN, Proxy, Routing, Event Logs, Active Directory / Entra ID, Roles/Features, Services, Processes, Scheduled Tasks, and PnP Devices in Pro mode.
- **One-Shot Protection & Offline Security**: License data (`license.dat`) is encrypted and bound to the host PC with up to a 30-day offline grace period, while `ohnuki-pro.dat` supports configurable expiration limits along with optional post-scan auto-deletion and executable self-deletion.
- **Native AOT Compiled & Bilingual**: Designed to run standalone with no external dependencies (no .NET runtime required), with automatic English / Japanese localization (`--lang-en` / `--lang-ja`).

### The 3-Step Fleet Inventory Workflow
Stop wasting time running slow scripts or manually compiling PC specs into spreadsheets:
1. **Create Scanner**: Export `OhnukiSan.exe` (and optional `ohnuki-pro.dat`) to a USB drive or ZIP from the **Create Scanner** tab.
2. **Run on Target PCs**: Double-click `OhnukiSan.exe` on each Windows PC (works 100% offline and generates a self-contained HTML report).
3. **Aggregate & Export CSV**: Drag and drop the collected HTML reports into **Analytics** to review fleet health and export an Excel-ready CSV ledger!

### Quick Start
1. Extract the downloaded ZIP archive and run `OhnukiHub.exe`.
2. (Optional) Click **Try with 5 Sample PCs** on the **Analytics** tab to explore the dashboard immediately.
3. Open **Create Scanner** to export `OhnukiSan.exe` (Standard Free, 24-hour Pro Trial, or Licensed Pro) to a ZIP file, folder, or USB drive.
4. Run `OhnukiSan.exe` on target PCs to generate HTML reports, then load or drag-and-drop those HTML reports into **Analytics** and click **Export CSV**.

### Editions & Licensing
- **Ohnuki-san Hub**: Completely free with no limits for Analytics, CSV export, Standard Audit (Free) scanner creation, and 24-hour Pro Trial creation.
- **Standard Audit (Free Edition)**: Unlimited, zero-license scanning with standalone `OhnukiSan.exe`.
- **Detailed Audit (Pro Edition)**: Unlocks enterprise audit modules (AD/domain, VPN, proxy, routing, event logs, services, processes, scheduled tasks, roles/features, PnP devices). Unregistered users can try all Pro features via a **24-hour, 1-run Pro Trial**; activating a Gumroad license key (Monthly, Yearly, or Lifetime) in **Pro License** unlocks continuous multi-PC scanning, up to 30-day expiry, and client-ready licensed report stamps:

| | Pro Trial (Free / Unregistered) | Ohnuki-san Pro (Licensed) |
|---|---|---|
| **Multi-PC Scanning** | 1 run (`ohnuki-pro.dat` auto-deletes) | **Continuous via USB / shared folder** (keeps `.dat`) |
| **Token Expiry** | Fixed 24 hours | **1 / 3 / 7 / 14 / 30 days** (advance prep & remote ZIP sharing) |
| **Report Stamp (HTML / MD / CSV)** | `Trial (Unregistered)` | **Licensed email** (ready for client delivery & audit records) |
| **Post-Scan Auto-Deletion** | Locked ON | **Toggle ON / OFF** per workflow |

### Terms & Disclaimer
- **License**: Hub and Standard scanner are free; Pro features are provided with a paid license. Secondary distribution is prohibited. See the [official page](https://chililikobo.github.io/en/ohnuki-san-hub.html) for details.
- **Data Privacy**: Collected inventory data is never transmitted externally. External communication occurs only with the Gumroad API during Pro license activation/verification (`OhnukiSan.exe` performs zero external communication).
- **Warranty**: Provided "As-Is". The author assumes no responsibility for any damages resulting from the use of this software.

### Credits (External Libraries)
This application incorporates open-source components. For detailed copyright notices and license agreements, refer to [ThirdPartyNotices.md](ThirdPartyNotices.md).

### Links & Contact
- **Developer**: chilili kobo
- **Official Page**: [https://chililikobo.github.io/en/ohnuki-san-hub.html](https://chililikobo.github.io/en/ohnuki-san-hub.html)
- **GitHub**: [https://github.com/chililikobo/OhnukisanHub](https://github.com/chililikobo/OhnukisanHub)
- **X (Twitter)**: [@chililikobo](https://x.com/chililikobo)
- **Email**: chilili.kobo@gmail.com

---

## 日本語

Ohnuki-san Hub（大抜さん Hub）は、スタンドアロン型 Windows PC IT資産情報スキャナー「大抜さん（`OhnukiSan.exe`）」の専用統合管理アプリケーションです。オフラインや現場 PC 向けのインストール不要な調査パッケージの作成と、回収した複数台の HTML レポートの一括集計・分析・Excel 用 CSV 出力をこれ1つで行えます。

### 主な機能
- **調査ツールの作成・書き出し**: 内蔵された `OhnukiSan.exe`（および Pro 設定ファイル `ohnuki-pro.dat`）を、ZIP アーカイブ、フォルダ / USB 直接保存、`.dat` 単体、標準調査（Free）単体として書き出せます。
- **複数台レポートの集計・比較ダッシュボード**: Free 版・Pro 版混在の HTML レポートをフォルダ選択またはドラッグ＆ドロップで一括読み込み。クリックで絞り込める5つの KPI カード、4種のクロスフィルタ対応ドーナツチャート（メーカー / OS / OSバージョン / シャーシ種別）、クイックフィルタ、1クリックの **「比較: 全ファイル / 台帳: 各PC最新のみ」モード切替**、詳細プロパティインスペクタを備えています。
- **無制限の Excel 用 CSV 出力**: 集計した資産台帳を UTF-8（BOM付き）の Excel 対応 CSV ファイルとして制限なく出力できます。
- **標準調査 (Free) ＆ 詳細監査 (Pro)**: Free 版でハードウェア・OS・ストレージ・ネットワーク・セキュリティ・ユーザー/グループ・ソフト一覧・更新・プリンター・システムパスを収集。Pro 版では VPN、プロキシ、ルーティング、イベントログ、Active Directory / Entra ID、Windows機能、サービス、プロセス、スケジュールタスク、PnPデバイスまで詳細監査できます。
- **ワンショット保護とオフラインセキュリティ**: 管理用 PC のライセンス（`license.dat`）は端末ごとに暗号化して保護され、最大30日間のオフライン利用に対応。現場用の Pro 設定ファイル（`ohnuki-pro.dat`）には有効期限の設定に加え、実行後の自動削除や本体自己削除を指定できます。
- **Native AOT コンパイル ＆ 日英対応**: 単体動作するように設計されており、.NET ランタイムなどの追加インストールは不要です。OS 言語に応じて日本語 / 英語を自動切替します（`--lang-ja` / `--lang-en` 対応）。

### 3ステップで完了する PC 資産棚卸しワークフロー
時間のかかる手作業での PC スペック調査や台帳転記を大幅に効率化できます：
1. **調査ツールを作る**: 「調査ツール作成」タブから USB メモリや ZIP として `OhnukiSan.exe`（必要に応じて `ohnuki-pro.dat`）を書き出します。
2. **対象 PC で実行する**: 調査したい Windows PC で `OhnukiSan.exe` をダブルクリックします（完全オフラインで動作し、HTML レポートが生成されます）。
3. **集計・CSV 出力する**: 回収した HTML レポートを「集計・比較」画面にドラッグ＆ドロップするだけで、状態チェックと Excel 用 CSV 台帳の出力が一瞬で完了します！

### 使い方
1. ダウンロードした ZIP ファイルを解凍し、`OhnukiHub.exe` を起動します。
2. （任意）「集計・比較」タブの「サンプル5台で体験する」から、ダミーデータで画面操作をすぐに試せます。
3. 「調査ツール作成」タブで、標準調査（Free）または詳細監査（24時間お試し / Pro 登録済み）を選び、ZIP・フォルダ/USB などに書き出します。
4. 対象 PC で `OhnukiSan.exe` をダブルクリックして実行すると HTML レポートが生成されます。生成された HTML レポートを「集計・比較」タブで読み込む（またはドラッグ＆ドロップする）と自動集計され、「Excel用 CSV出力」で保存できます。

### エディションとライセンス
- **Ohnuki-san Hub 本体**: 集計・比較、CSV 出力、標準調査（Free）の書き出し、詳細監査（24時間お試し）の書き出しを無料・無制限で利用できます。
- **標準調査（Free Edition）**: `OhnukiSan.exe` 単体でライセンス不要・期限なしで何度でも利用できます。
- **詳細監査（Pro Edition）**: AD/ドメイン構成、VPN、プロキシ、ルーティング、イベントログ、サービス、プロセス、スケジュールタスク、Windows機能、PnPデバイスなどの詳細監査項目がアンロックされます。ライセンス未登録でも**24時間・1回限りのお試し版**で全 Pro 機能を体験でき、「Proライセンス」タブで Gumroad ライセンスキー（月額 / 年額 / 永続・買い切り）を登録すると、複数台連続スキャン・最大30日の期限設定・正規ライセンス表記が解放されます。

| | お試し版 (無料・未登録) | Ohnuki-san Pro (登録済み) |
|---|---|---|
| **複数台スキャン** | 1回ごとに `ohnuki-pro.dat` を自動削除 | **USB・共有フォルダから連続スキャン可**（`.dat` を保持） |
| **有効期限** | 24時間固定 | **1・3・7・14・30日**（前日準備・メール/チャット ZIP 配布対応） |
| **レポート表記 (HTML / MD / CSV)** | `Trial (Unregistered)` | **正規ライセンス表記**（客先納品・監査証跡に対応） |
| **実行後の自動削除** | 常に ON（固定） | **ON / OFF を用途に応じて切替可能** |

### 利用規約・免責事項
- **ライセンス**: Hub 本体および標準調査は無料、詳細監査の拡張機能は有料ライセンスにより提供されます。二次配布は原則禁止します。詳細は[公式ページ](https://chililikobo.github.io/ohnuki-san-hub.html)をご参照ください。
- **外部通信**: 収集した資産情報を外部へ送信することはありません。外部通信は Pro ライセンス認証・検証時の Gumroad API 通信のみに限定されます（書き出される `OhnukiSan.exe` は外部通信を行いません）。
- **免責事項**: 本ソフトウェアは「現状有姿（As-Is）」で提供され、使用により生じた一切の損害について作者は責任を負いません。

### 外部ライブラリ（クレジット）
本ソフトウェアはオープンソースコンポーネントを使用しています。各コンポーネントの著作権表示およびライセンス条文の詳細は [ThirdPartyNotices.md](ThirdPartyNotices.md) をご参照ください。

### リンク・連絡先
- **制作者**: chilili kobo
- **公式ページ**: [https://chililikobo.github.io/ohnuki-san-hub.html](https://chililikobo.github.io/ohnuki-san-hub.html)
- **GitHub**: [https://github.com/chililikobo/OhnukisanHub](https://github.com/chililikobo/OhnukisanHub)
- **X (旧Twitter)**: [@chililikobo](https://x.com/chililikobo)
- **メール**: chilili.kobo@gmail.com

