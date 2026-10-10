# colab-llm-notebooks

在 Google Colab 上跑 LLM / VLM 的 notebook 收藏。

## Colab 運算單元哪裡來

訂閱 **Google AI Pro** 方案會附 **200 個 Colab 運算單元(compute units / credits)**,不用另外買 Colab Pro 就能選 A100、G4 這類高階 GPU 來跑這裡的 notebook。

- 高階 GPU 連線期間會持續消耗運算單元,用完記得中斷並刪除執行階段。
- 有運算單元不代表一定分配得到 A100 / G4,尖峰時段可能選不到。
- 實際額度與方案內容以 Google 官方說明為準。

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

把 GitHub 網址的 `github.com` 換成 `colab.research.google.com/github` 就能直接在 Colab 開啟,例如:

<https://colab.research.google.com/github/virgil724/colab-llm-notebooks/blob/main/qwen/qwen38_27b_vllm_300k.ipynb>

或在 Colab 選「檔案 → 開啟筆記本 → GitHub」,輸入 `virgil724/colab-llm-notebooks`。
