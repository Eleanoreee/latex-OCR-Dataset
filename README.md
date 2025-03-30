# LaTeX-OCR-Dataset

Commom-use trainning date for latex OCR use formulas from arxiv, wikipedia, stack exchange. But recent large models actually needs very big amount of data and we are insparied what if we try to use LLM to generate formulas for us?
Thanks to works from [im2latex](https://github.com/Miffyli/im2latex-dataset) which creats a trustworthy dataset for latex OCR. This project can be seen as a complement to im2latex

## Contends
- `generate_data/src/generate_zephyr.py`
  We finalwly decides to use zephyr based on ollama which is a small 7b fine-tuning model based on Mistral-7b to generate formulas in latex code
- `generate_data/src/generate2formulas.py`
  The script aims to format generated formulas into more readable one and can easily used.
- `generate_data/src/formula2image copy.py`
  The original script comes from [im2latex](https://github.com/Miffyli/im2latex-dataset) to convert images from formula file.
