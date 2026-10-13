# ConvRot image workflow

Purpose: Create one image with a ConvRot-quantized diffusion model and compatible text encoder.

# Mage-Flow W4A8 + ARA workflow

File: `Mage_Flow_W4A8_ARA.json`

Purpose: Create one image with the 4-bit Mage-Flow build from [SearchingMan/Mage-Flow-W4A8-ARA](https://huggingface.co/SearchingMan/Mage-Flow-W4A8-ARA) and its accuracy recovery adapter (ARA).

Needs the custom node [ComfyUI-MageFlow-ARA](https://github.com/kgonia/ComfyUI-MageFlow-ARA). The text encoder is the INT8 ConvRot Qwen3-VL-4B from the same Hugging Face repo; Comfy-Org's `qwen3vl_4b_bf16.safetensors` works in the same `CLIPLoader` with about 3.7 GB more VRAM.
