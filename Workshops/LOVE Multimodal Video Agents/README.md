# Workshop Notes: LOVE Multimodal Video Agents

Link [Here](https://sites.google.com/view/loveucvpr25)
## VILA – Song Han

- **AWQ for on-device deployment**
- **4-bit quantization**
- Achieves **3× speed-up** through quantization
- Improvement presented as **NVILA**
  - Uses **COAT**: Memory-efficient FP8 training
- **LongVILA R1**:
  - New reasoning model
  - Performs better with more frames (supports **128/256 frames**)
- Still uses **uniform sampling**
- Results are promising, but **multi-frame understanding** remains a challenge

---

## Sherry – Video Generation

**Paper**: [Video Generation for VLA](https://arxiv.org/html/2410.10076v3)

- Uses **video generation** to aid Vision-Language-Action (VLA) tasks  
  e.g., Generate a video of the action before a robot performs the target action
- The generated video **implicitly conveys what needs to be done**
- For complex tasks:
  - Break the task down into **subtasks**
  - Generate a video for each subtask
  - Use the **final frame** to select the correct generation and verify its accuracy
  - This forms a **decision tree** that gradually leads to the final outcome
- Requires:
  - **VLM feedback**
  - **Self-corrective training**
  - **Execution feedback**, especially if the video generation **hallucinates**
