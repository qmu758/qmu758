## Hi there 👋

<!--
**qmu758/qmu758** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# きゅーむ / qmu758

Pythonを中心に、日常やシステム運用で発生した課題を
自動化・可視化・ツール化することに関心があります。

デジタル放送・録画サーバー・ネットワーク・監視などの趣味環境から、
ブラウザで使える小規模なWebツールまで、
「実際に欲しいもの・困ったこと」を起点に開発しています。

## Skills

- Python
- JavaScript / HTML / CSS
- VBA
- Git / GitHub
- Windows / Linux
- Tailscale / VPN
- SMB
- SQLite
- Discord Webhook
- Windows Task Scheduler
- ネットワーク・サーバー運用
- 業務改善・自動化

## Featured Projects

### [Recording Mover](https://github.com/qmu758/recording_mover)

VPN経由のリモート録画サーバーから、自宅サーバーへ録画ファイルを
安全に自動転送するPythonツールです。

- 転送量・帯域制限
- 空き容量チェック
- リトライ
- 不完全ファイル対策
- SQLiteによる履歴管理
- 多重起動防止

### [Virtual Broadcast System](https://github.com/qmu758/VirtualBroadcastSystem)

OBS Studioの映像・音声からMPEG-2 TSを生成し、
仮想BonDriver経由でTVTestから受信できる
PC上の仮想デジタル放送システムです。

物理的なRF出力やOFDM変調器を使用せず、
PC内で自主放送環境を構築できます。

> C++実装にはCodexを活用し、
> システム構成・要件設計・動作検証を行っています。

### [Tailscale Monitor](https://github.com/qmu758/Tailscale-Monitor)

Tailscale上の端末のオンライン・オフライン状態を監視し、
Discordへ通知するPythonツールです。

- 誤検知を抑える安定時間判定
- 重要ノードの即時通知
- Windows / Linux対応

### [CSV ↔ JSON Converter](https://qmu758.github.io/csv-json-converter/)

CSVとJSONをブラウザ上で相互変換できるWebツールです。

- CSV → JSON / JSON → CSV
- カンマ・セミコロン・タブ区切り対応
- 引用符・改行を含むCSVに対応
- UTF-8ファイルの読み込み・ダウンロード
- 外部サーバーへのデータ送信なし
- GitHub Pagesで利用可能

## Other Projects

- **Windows Error Discord Notifier**  
  Windowsのイベントログを監視し、異常終了などをDiscordへ通知

- **Discord Disk Space Monitor**  
  Windowsマシンのディスク空き容量を監視してDiscordへ通知

- **Realtime Subtitle**  
  PC上の外国語音声を文字起こし・翻訳し、日本語字幕として表示

- **Japan DTV Channel Converter**  
  地上デジタル放送の物理チャンネルと中心周波数を相互変換

- **JP Phone Number Formatter**  
  日本の電話番号を種類・地域に応じてハイフン区切りへ変換

## Interests

- Automation
- Infrastructure / Networking
- SRE / Operations
- Digital Broadcasting
- Recording Systems
- Web Tools

## Currently Learning

- Python Testing
- CI/CD
- Linux
- Cloud Infrastructure
- Infrastructure as Code
