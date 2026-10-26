## こんにちは!

Linuxサーバーの構築・運用を中心に、インフラエンジニアを目指して学習しています。
前職では太陽光発電設備の施工・販売会社で、お客様からの故障トラブルの問い合わせ対応を担当していました。
症状のヒアリング、原因の推測、対応の調整、報告書の作成までを行っており、
その経験を活かし、障害の切り分け・原因特定・記録までを一連の対応として行うことを意識しています。

### 資格
- LPIC-1
- CCNA

### 主な成果物
- [linux-server-portfolio](https://github.com/yasuzaki-ibuki/linux-server-portfolio)
  VirtualBox上のRocky Linux 9に、Nginx・Webアプリ・監視(LINE通知)・作業記録アプリ・勤怠アプリ(PostgreSQL)を構築。
  SELinuxはEnforcingのまま運用し、DBの自動バックアップと復元テスト、2台構成でのネットワーク・ファイアウォール設計、構築中に発生した障害の調査・対処も記録しています。
- [Windows-admin-report](https://github.com/yasuzaki-ibuki/Windows-admin-report)
  VirtualBox上のWindows Server 2025(評価版)に、PowerShellでAD DSを導入しドメイン(lab.local)を構築。
  PC情報・パッチ・ローカルユーザー・管理者グループをCSV出力する点検スクリプトを作成し、エラーの原因と対処も記録しています。

### 使用している技術
- OS:Rocky Linux 9、Windows Server
- Web:Nginx、Flask、gunicorn
- 運用:systemd(service / timer)、firewalld、SELinux、chrony、journald
- ネットワーク:NetworkManager(nmcli)、tcpdump
- Windows:Active Directory、PowerShell
- DB:PostgreSQL、SQLite
- その他:Git / GitHub、Python、LINE Messaging API

### 今後の予定
- 運用手順書(Runbook)の整備と、運用の基本(ログローテーション・ディスク容量・権限管理)の実践
- DNS・DHCP・プロキシなどの基盤サーバー構築と、Zabbixによる監視
- Ansibleによる構築の自動化
- 脆弱性診断ツールを使った、自分のサーバーのセキュリティ確認
- AWS上への構築
