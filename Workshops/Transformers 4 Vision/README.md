# Transformers for Vision Workshop Notes

## Adobe Representative

- Discussed **shared vs. separate weights** for multimodal models.
- Proposed an **X-fusion layer** architecture:
  - Allows for **separate weights** in each modality (language/image) but maps them to the **same embedding space**.
  - Results in **double the weights**, but maintains the **same FLOPs**.
  - Can leverage **pretrained weights**:
    - Example: Use a pretrained LLM (language tower) and a separate pretrained VLM (vision tower), such as **Qwen2-VL**.
    - Possibility to **freeze one modality** and **fine-tune the other**.
- Mentioned models:
  - **YoLLaVA**
  - **YoChameleon**

---

## Microsoft Speaker: MLLM & Embodied Agents

- Evolution from **vision foundation models** (e.g., GLIP, CLIP) → **MLLMs** → **Embodied Agents**.
- Introduced **SoM (Set of Mark)** prompting:
  - A spatial awareness technique for MLLMs (e.g., GPT-4V).
  - Uses **visual markers** to label objects in images.
- Introduced **ToM (Trace of Mark)**:
  - A method for training **VLA (Vision-Language-Action)** models.
- Highlighted **Magma**:
  - A **multimodal, agentic foundation model** connecting MLLMs to VLAs/agents.
  - Excels at:
    - **Action benchmarks** like **OpenVLA**.
    - **Spatial understanding**.
    - **UI navigation tasks**.

---

## NUS: Mike Zheng

- Compared **autoregressive (AR)** vs. **diffusion-based** generation:
  - AR models generate **one token at a time**, well-suited for **text generation and understanding**.
  - **Diffusion models** perform **parallel generation**, primarily used in **image synthesis**.
- Proposed **SHOWO**:
  - A unified model architecture for both **understanding and generation**.
- Mentioned **DeepSeek-Janus**:
  - Another unified approach combining:
    - **AR–AR** or **AR–Flow** strategies.
