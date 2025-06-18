# Change Log

本Change Logのフォーマットは [Keep a Changelog](http://keepachangelog.com/) に基づいています。

## [v7.2] - 2025-06-17
### Fixed
- kakip_ai_appsが実行できない問題を修正
- デフォルト壁紙の問題を修正

## [v7.1] - 2025-06-11
### Added
- IMX462カメラのサポートを追加
- CANFDのサポートを追加
- SCI5ToGPIO、PWM0、PWM1、SPI、I2C10 用のDTBOを追加

### Fixed
- v4l2src 要素使用時の GStreamer における RGGB エラーを修正

## [v7] - 2025-05-07
### Added
- Geekworm X1301のサポート
- デバイスツリーオーバーレイ機能のサポート

## [v6-EEE-disabled] - 2025-02-03
### Fixed
- PHYドライバでEEE(Energy Efficient Ethernet)を無効化するように修正

## [v6] - 2025-01-14
### Added
- TigerVNCによるリモートデスクトップ機能の追加
- IMX219カメラのサポート
- Cortex-M33 及び Cortex-R8 を使用したマルチOS機能の追加

### Fixed
- ファン制御機能で他のGPIOピンに影響を与えていた処理を修正

### Removed
- Tier4 C1カメラのエラーログ抑止のため、サポートを削除
- IMX462 カメラサポートを削除

## [v5] - 2024-10-1
### Added
- Ubuntu 24.04のサポート
- Dockerのサポート
- Tier4 C1カメラのサポート
- ファン制御機能の追加
