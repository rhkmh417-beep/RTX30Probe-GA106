# 参考文献・技術情報源

## 1. 目的

本資料は、RTX30Probe-GA106に関連する公開技術資料および参考情報源を整理したものです。

ハードウェア仕様、GPUアーキテクチャ、演算性能および実験結果の評価においては、公式技術資料を優先します。

## 2. NVIDIA公式製品資料

### GeForce RTX 30 Series Laptop GPUs

発行元：NVIDIA

URL: https://www.nvidia.com/ja-jp/geforce/laptops/30-series/

研究との関連性：

- GPUの公式仕様
- CUDAコア構成
- GPUメモリ構成
- Laptop GPUの動作特性

## 3. GPUアーキテクチャおよびCUDA技術資料

### NVIDIA Ampere GPU Architecture Tuning Guide

発行元：NVIDIA

URL: https://docs.nvidia.com/cuda/ampere-tuning-guide/

研究との関連性：

- Ampereアーキテクチャの特性
- Compute Capability 8.6
- Tensor Coreの演算特性
- GPU演算スループット

### CUDA Toolkit Documentation

発行元：NVIDIA

URL: https://docs.nvidia.com/cuda/landing/index.html

研究との関連性：

- CUDAプログラミングモデル
- GPU演算アーキテクチャ
- 数値演算精度
- GPU性能評価

### CUDA C++ Best Practices Guide

発行元：NVIDIA

URL: https://docs.nvidia.com/cuda/cuda-c-best-practices-guide/

研究との関連性：

- GPU性能測定
- 演算効率
- ベンチマーク測定方法
- 性能最適化

## 4. 公開ハードウェア資料およびソース関連資料

### NVIDIA Open GPU Kernel Modules

発行元：NVIDIA

URL: https://github.com/NVIDIA/open-gpu-kernel-modules

研究との関連性：

- GPU識別情報
- 対応GPU情報
- 公開されているLinux GPUドライバーの構造

本リポジトリはLinux GPUカーネルモジュールに関するものであり、非公開のWindows GPUドライバーの完全な仕様を示すものではありません。

### NVIDIA Open GPU Documentation

発行元：NVIDIA

URL: https://github.com/NVIDIA/open-gpu-doc

研究との関連性：

- 公開ハードウェアインターフェース資料
- GPUアーキテクチャ関連資料
- ハードウェア技術用語

## 5. 参考情報の評価方針

外部技術情報は、以下の原則に基づいて評価します。

- 公式技術資料を優先する。
- GPUアーキテクチャごとの相違点を考慮する。
- 他のGPUで確認された現象をGA106にも適用できるとは断定しない。
- コミュニティによる研究結果と公式仕様を区別する。
- AIによる技術的解釈には独立した検証を必要とする。
- 実験上の仮説を確定事実として扱わない。

## 6. 著作権およびライセンス

外部技術資料、ソースコード、商標および知的財産には、それぞれの権利者による所有権およびライセンス条件が適用されます。

参考情報は、技術的な出典の明示および研究上の背景説明を目的として掲載しています。

参考文献への掲載は、公式な承認、提携関係、または資料の再配布許可を意味するものではありません。

## 7. 参考文献の確認状況

本資料に掲載した参考文献は、本プロジェクトの技術的な背景を理解するための資料です。

これらの資料は、対象GPUにおける人為的なTensor Core性能制限の存在、または性能変更の成功を証明するものではありません。

追加の参考文献については、内容の確認後に掲載します。

最終更新日：2026年11月24日
