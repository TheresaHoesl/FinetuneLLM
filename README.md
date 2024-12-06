# FinetuneLLM

In this repo an existing pre-trained large language model `unsloth/llama-3.2-1b-instruct-bnb-4bit` which is a quantized model of the `meta-llama/Llama-3.2-1B-Instruct` gets finetuned on the `mlabonne/FineTome-100k` data set using LoRA adaptation.

* Lab2: the `unsloth/Llama-3.2-1B-Instruct` model gets fine-tuned on the mentioned dataset and saved as `sreyanghosh/lora_model`.
* Lab2_inference: using Gradio, an UI is created and one can chat with the model.
