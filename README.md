#  PalWorld Docker Server Management System Script
This script was created by AlanBacker and currently only works on Debian distributions. 这个脚本由AlanBacker创建，目前仅适用于Debian发行版本。このスクリプトはAlanBackerによって作成され、現在はDebianディストリビューションにのみ対応しています。

# PalWorld Docker Server Management System

This Docker server management script for PalWorld is created by AlanBacker and is specifically designed for Debian server platforms.

## Features

This script offers a variety of functions including:

- Docker installation
- Deployment of a new PalWorld server
- Deployment of an auto-maintenance system that includes automatic backups and scheduled restarts
- Creation of manual backups
- Data recovery from backup files
- Real-time logs viewing
- Game rules file editing
- Management of the game Docker image (start, stop, restart)
- Broadcasting server messages via RCON

## Precautions

- Ensure you have adequate knowledge of Docker and Linux before using this script.
- Always backup your data before performing any operations.
- Make sure Docker and all dependencies are properly installed and configured on your Debian server.
- The Docker image used by this script is sourced from: [kagurazakanyaa/palworld](https://hub.docker.com/r/kagurazakanyaa/palworld).
- Set up the `AdminPassword` and `RCONenabled` parameters for the game before deploying the auto-maintenance system.

## Contributor

- AlanBacker


## License

This script is released under the MIT License. By using this script, you agree to its terms.

## Disclaimer

The author of this script is not responsible for any direct or indirect damage caused by the use of this script. Users assume all risks.

---

**Note: This is the English version of the README.**


# PalWorld Docker 服务器管理系统

这是一个由 AlanBacker 创建的 PalWorld 服务器管理脚本，专门用于 Debian 服务器平台。

## 功能

该脚本提供以下功能：

- 安装 Docker
- 部署新的 PalWorld 服务器
- 部署自动维护系统，包括自动备份和定时重启
- 创建手动备份
- 从备份文件中恢复数据
- 查看实时日志
- 修改游戏规则文件
- 管理（启动、停止、重启）游戏 Docker 镜像
- 通过 RCON 广播服务器消息

## 注意事项

- 使用本脚本前请确保你有足够的 Docker 和 Linux 知识。
- 如果你在中国大陆，并且没有良好的网络环境（如高速访问外网，请修改脚本中第55行为`docker pull docker.mirrors.sjtug.sjtu.edu.cn/kagurazakanyaa/palworld`  注意隔行！
  
  如图：![image](https://github.com/AlanBacker/AlanBacker-PalWorld-Docker-Server-Management-System-Script/assets/53960149/80c6b83b-e95b-4885-8f71-7f3612bad125)
- 以及第97行为`if docker pull docker.mirrors.sjtug.sjtu.edu.cn/kagurazakanyaa/palworld | grep -q 'Downloaded newer image'; then`
  
  如图：![image](https://github.com/AlanBacker/AlanBacker-PalWorld-Docker-Server-Management-System-Script/assets/53960149/8403e9b1-229f-46ae-821d-49e5ff3e0a97)
）
- 在执行任何操作前，务必备份你的数据。
- 确保 Docker 和所有依赖项在 Debian 服务器上已正确安装和配置。
- 本脚本使用的 Docker 镜像来自：[kagurazakanyaa/palworld](https://hub.docker.com/r/kagurazakanyaa/palworld)。
- 在部署自动维护系统前，请先设置游戏的 `AdminPassword` 和 `RCONenabled` 参数。

## 贡献者

- AlanBacker

## 欢迎关注

- Bilibili: [AlanBacker的Bilibili空间](https://space.bilibili.com/702922307)

## 使用许可

本脚本遵循 MIT 许可。使用本脚本即表明您同意其条款。

## 免责声明

本脚本作者不对因使用本脚本而造成的任何直接或间接损失负责。用户应自行承担风险。

---

**注意：这是中文版本的 README。**

# PalWorld Dockerサーバー管理システム

このPalWorldサーバー管理スクリプトはAlanBackerによって作成され、Debianサーバープラットフォーム専用に設計されています。

## 機能

このスクリプトは以下の機能を提供します：

- Dockerのインストール
- 新しいPalWorldサーバーのデプロイ
- 自動バックアップとスケジュールされたリスタートを含む自動メンテナンスシステムのデプロイ
- マニュアルバックアップの作成
- バックアップファイルからのデータ復旧
- リアルタイムログの表示
- ゲームルールファイルの編集
- ゲームDockerイメージの管理（開始、停止、リスタート）
- RCONを通じたサーバーメッセージのブロードキャスト

## 注意事項

- このスクリプトを使用する前に、DockerとLinuxに関する十分な知識を持っていることを確認してください。
- いかなる操作を行う前に、必ずデータをバックアップしてください。
- Debianサーバー上でDockerおよびすべての依存関係が正しくインストールされ、設定されていることを確認してください。
- このスクリプトで使用されるDockerイメージはこちらから取得しています：[kagurazakanyaa/palworld](https://hub.docker.com/r/kagurazakanyaa/palworld)。
- 自動メンテナンスシステムをデプロイする前に、ゲームの`AdminPassword`と`RCONenabled`パラメータを設定してください。

## 貢献者

- AlanBacker

## 連絡先

- Bilibili: [AlanBackerのBilibiliスペース](https://space.bilibili.com/702922307)

## ライセンス

このスクリプトはMITライセンスの下でリリースされています。このスクリプトを使用することで、その条件に同意したことになります。

## 免責事項

このスクリプトの作者は、このスクリプトの使用によって生じる直接的または間接的な損害について一切責任を負いません。ユーザーはすべてのリスクを負担します。

---

**注意：これはREADMEの日本語版です。**
