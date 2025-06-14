# Sight and Sound Workshop Summary

This workshop explores recent advances in **audio-visual fusion** for various computer vision and audio tasks. The official workshop site can be found [here](https://sightsound.org/).

---

## 📄 Paper Presentations

### **CAV-MAE Sync: Improving Contrastive Audio-Visual Mask Autoencoders via Fine-Grained Alignment**
- Combines vision-masked autoencoders and contrastive learning.
- Learns using paired video frames and audio windows.
- Focused on improving visual-audio representations.

### **Diagnosing and Treating Audio-Video Deepfake Detection**
- Introduces **DeepSpeak v1** for detecting mismatches in visual-audio deepfakes.
- Uses **jitter augmentation** to outperform silent baselines.
- Recommended for **Q1 experiments**.

### **UWAV: Uncertainty-Weighted Weakly-Supervised Audio-Visual Video Parsing**
- AVVP method for identifying sound event types in videos.
- Handles noisy and imprecise labels effectively.

### **STM2DVG: Synthetically Trained Music-to-Dance Video Generation**
- Uses a **latent diffusion framework** to generate dance videos based on music input.

### **AVS-Net: Audio-Visual Scale Network for Self-Supervised Monocular Metric Depth Estimation**
- Combines audio and visual cues for depth estimation.
- Builds on **ZoeDepth**.
- Uses **chirps** as audio signals.
- Relevant for **Q2 low-light or non-depth camera scenarios**.

### **SAVGBench: Benchmarking Spatially Aligned Audio-Video Generation** – *Jialiang Lu*
- Proposes a benchmark for evaluating **audio-visual spatial alignment**.

### **Human Pose Estimation via Audio**
- Explores estimating human pose using audio signals.
- Specific technical details not disclosed.

### **Visual Sound Source Localization**
- Assesses models using both **positive** (visible source) and **negative** (non-visible source) audio.
- Enhances the **VGG-Sound Source dataset**.
- Reveals poor model performance on negative samples.

---

## 🎤 Speaker Keynotes

### **James M. Rehg – Learning to Infer Audio-Visual Attention in Social Communication**
- Focus on **egocentric** and **exocentric** gaze estimation.
- Introduces **GazeLLE** built on **DINOv2**.
- Combines multiple vision tasks (depth, pose, etc.).
- Valuable for **autism and social behavior research**.
- Summary: Understanding group conversational behavior.

### **David Harwarth – Sight and Sound with Large Language Models**
- **Applications of MLLMs**:
  - **Video Dubbing**:
    - Inputs: Silent video, transcript, speaker voice reference.
    - Challenges: Lip-sync, emotion alignment.
    - Uses **quantizers** and **neural codecs** to manage 16kHz audio.
  - **Spatial Sound Understanding**:
    - Identifies sound source locations.
    - Applications: AR/VR, search & rescue, autonomous driving.
    - Introduces a new **spatial sound dataset**.

### **Ziyuan Chen – Learning Sight and Sound with Generative AI**
- Converts audio to **spectrogram art**.
- Multimodal conditional **foley generation** using video, text, and audio.
- Combines **VGGSound** and **HQSFX** for improved data quality.

### **Stella Yu**
- Advocates **instance-level representation** over class-based supervision.
- Enables better transfer to downstream tasks.
- Adaptable to audio domains.
- Also explores **unsupervised object segmentation** in videos using optical flow.

---

## 🧠 Workshop Summary

This workshop presented diverse techniques for **multimodal audio-visual learning**, including:

- **Representation learning**: 
  - CAV-MAE Sync, UWAV (AVVP).
- **Specialized tasks and benchmarks**: 
  - Sound localization benchmarks, positive vs. negative audio analysis.
- **Video generation**: 
  - Using music/audio to drive visuals (e.g., STM2DVG).
- **Cross-modal estimations**: 
  - Pose estimation using audio, and depth estimation combining video and chirps.

---

## 🔍 Relevance to Q Team

- **Q1**:
  - Deepfake detection using **DeepSpeak v1** is directly applicable.
- **Q2**:
  - Depth estimation using **AVS-Net** may help in **low-light scenarios** where depth sensors are unreliable.
- **Q3**:
  - **AVVP task** (UWAV) could be explored, though datasets are general and **not tailored for homeland-specific contexts**.

### Notable Datasets and Benchmarks:
- **VGGSounder**: Useful for training in **audio-video captioning**.
- **SAVGBench**: Helpful for evaluating **sound localization** accuracy.

---

## 🚫 Limitations for Q Team

While keynote talks present interesting applications and research directions for multimodal AI, many currently lack **direct applicability** to Q Team goals. However, select components may be useful in the future:

- **AudioLM model training**: Use of quantizers for high-frequency data.
- **Behavioral monitoring**: Gaze estimation may assist in **crime prediction** or surveillance research.

---
