# RTX30Probe-GA106

## プロジェクト概要

NVIDIA GeForce RTX 3060 Laptop GPUを対象とした、GPU初期化動作、UEFI診断およびTensor Coreの性能特性に関する独立技術研究プロジェクトです。

主な研究目的は、AI動画処理を中心としたAIワークロードにおけるGPUの性能特性を理解することです。

## 実機環境

| 項目 | 仕様 |
|---|---|
| PC | GALLERIA XL7R-R36 |
| CPU | AMD Ryzen 7 5800H |
| GPU | NVIDIA GeForce RTX 3060 Laptop GPU |
| アーキテクチャ | Ampere（GA106） |
| PCI Device ID | 10DE:2520 |
| VRAM | 6 GB |
| RAM | 32 GB |
| Compute Capability | 8.6 |
| OS | Windows 11 |
| ファームウェア環境 | UEFI |

## 研究進捗

現在の開発世代：GEN27

主な研究内容：

- UEFI環境でのPCIデバイス検出
- GPUのPCI構成空間診断
- GPU初期化状態の観測
- ファームウェア初期化動作の解析
- Tensor Coreの性能測定
- 公開技術資料との比較検証

## 基準性能

過去に実施したGEMMベンチマークの測定結果：

| 演算精度 | 実測性能 |
|---|---:|
| FP16 | 21.33 TFLOPS |
| BF16 | 20.86 TFLOPS |
| TF32 | 11.30 TFLOPS |
| FP32 | 7.19 TFLOPS |

これらは既存のハードウェアおよびソフトウェア環境における実測値であり、人為的な性能制限の存在を証明するものではありません。

## 現在の状況

GPUの検出および複数のUEFI診断工程に成功しています。

ファームウェアの初期化動作については引き続き調査中です。FWSECの正常実行は確認されていません。

現段階では、Tensor Coreの性能向上も確認されていません。

## 技術的な情報提供について

GPUの初期化動作、診断結果の解釈、性能測定方法、関連する公開技術資料について、技術的な意見や情報提供を歓迎します。

第三者による独立した技術評価や、研究内容に対する訂正も歓迎します。

## 公開方針

本リポジトリでは、研究資料、診断結果および性能測定結果を中心に公開します。

プロプライエタリなファームウェアバイナリ、個人情報、セキュリティ保護機構の回避実装は公開対象に含めません。

## 免責事項

本プロジェクトは独立した技術研究であり、NVIDIA、GALLERIAおよび関連メーカーの公式プロジェクトではありません。

実験による観測結果と、検証済みの技術的結論を区別して記載します。

最終更新日：2026年11月24日

## 研究資料一覧

[English README](README.md)

| 研究資料 | 英語版 | 日本語版 |
|---|---|---|
| ハードウェアおよび検証環境 | [English](docs/HARDWARE.md) | [日本語](docs/HARDWARE_JP.md) |
| 研究開発履歴 | [English](docs/RESEARCH_HISTORY.md) | [日本語](docs/RESEARCH_HISTORY_JP.md) |
| 現在の研究状況 | [English](docs/CURRENT_STATUS.md) | [日本語](docs/CURRENT_STATUS_JP.md) |
| Tensor Core基準性能測定 | [English](benchmarks/TENSOR_CORE_BASELINE.md) | [日本語](benchmarks/TENSOR_CORE_BASELINE_JP.md) |
| 参考文献・技術情報源 | [English](docs/REFERENCES.md) | [日本語](docs/REFERENCES_JP.md) |
| 更新履歴 | [English](CHANGELOG.md) | [日本語](CHANGELOG_JP.md) |

## ライセンス

特記がない限り、独自の研究資料および性能測定資料にはCC BY 4.0ライセンスが適用されます。

詳細は [LICENSE](LICENSE) を参照してください。
