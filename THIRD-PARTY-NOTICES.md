# 第三者ソフトウェアの表記

| コンポーネント | 版・ライセンス |
| --- | --- |
| Electron | 44.7.0 / MIT。Chromiumなどの表記はアプリ本体フォルダのLICENSES.chromium.html |
| llama.cpp | b11429、CPU x64・Vulkan / MIT |
| Gemma 4 E4B Q4_0 | ggml-org変換GGUF / Apache-2.0 |
| Qwen3.5 4B Q4_K_M（旧版） | unsloth変換GGUF / Apache-2.0 |
| Microsoft Visual C++ Runtime | 再頒布ライセンスに従って必要なDLLを同梱 |

元のライセンスとモデルカードは、配布フォルダの「アプリ本体」内の `LICENSE`、`LICENSES.chromium.html`、`licenses`、`resources/ai/llama/LICENSE-LLVM-OpenMP` に保持しています。

- [Gemmaモデル](https://huggingface.co/google/gemma-4-E4B-it)
- [Gemma GGUF取得元](https://huggingface.co/ggml-org/gemma-4-E4B-it-GGUF)
- [Qwenモデル](https://huggingface.co/Qwen/Qwen3.5-4B)
- [GGUF変換元](https://huggingface.co/unsloth/Qwen3.5-4B-GGUF)
- [llama.cpp](https://github.com/ggml-org/llama.cpp)
- [Electron](https://www.electronjs.org/)

食品・器・背景は生成画像です。BGMはComfyUIで生成し、ループ用に調整したOgg Opus音源です。
ビルド・検証用のPython、Playwright、sharp、音楽生成モデルはゲームの実行には必要ありません。
