# colab-llm-notebooks

在 Google Colab 上跑 LLM / VLM 的 notebook 收藏。

## qwen/

| Notebook | 說明 |
| --- | --- |
| [qwen38_27b_vllm_300k.ipynb](qwen/qwen38_27b_vllm_300k.ipynb) | Qwen3.8-27B · vLLM · 300K context · OpenAI-compatible API |
| [qwen38_flash_next_llamacpp.ipynb](qwen/qwen38_flash_next_llamacpp.ipynb) | Qwen3.8-Flash-Next(176B MoE,6B active)· llama.cpp · G4 |

## manga-ocr/

| Notebook | 說明 |
| --- | --- |
| [manga_ocr_arena.ipynb](manga-ocr/manga_ocr_arena.ipynb) | 漫畫 OCR 擂台:PaddleOCR-VL-1.5 vs manga-ocr vs Qwen3.8 |
| [manga_translate.ipynb](manga-ocr/manga_translate.ipynb) | 漫畫翻譯:PaddleOCR-VL → Qwen3.8(日 → 台灣繁中) |
| [gemini_ocr_test.ipynb](manga-ocr/gemini_ocr_test.ipynb) | 擂台加賽:Gemini Flash 讀漫畫日文 |
| [gemini_box_test.ipynb](manga-ocr/gemini_box_test.ipynb) | 擂台加賽 2:Gemini 自己切框,與 PaddleOCR-VL 的框算 IoU |

## strata/

| Notebook | 說明 |
| --- | --- |
| [Strata_A100_Colab_Quickstart_zh-TW.ipynb](strata/Strata_A100_Colab_Quickstart_zh-TW.ipynb) | Google AI Pro × Colab A100 × Strata:跑跑看 125B MoE(繁中版) |
| [Strata_A100_Colab_Quickstart_ja.ipynb](strata/Strata_A100_Colab_Quickstart_ja.ipynb) | 同上,日文原版的副本 |

## 使用方式

在 Colab 選「檔案 → 開啟筆記本 → GitHub」,勾選「包含私人存放區」後選擇這個 repo 的 notebook。
