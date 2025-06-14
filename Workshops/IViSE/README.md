# IViSE 2025 – 1st International Workshop on Interactive Video Search and Exploration

🔗 [Workshop Website](https://sites.google.com/view/ivise2025)

The 1st International Workshop on Interactive Video Search and Exploration (IViSE), held at CVPR 2025, addresses the growing challenge of long-form video understanding through human-machine collaboration.

While automated video analysis has seen significant progress, existing methods still struggle with long-form content (videos ranging from 3 to 30 minutes). IViSE aims to push the boundaries of video retrieval and question answering with a dual-track challenge:
- **Automated Track**: Fully automated solutions.
- **Interactive Track**: Real-time, human-in-the-loop systems under time constraints.

## Challenge Overview

Participants will utilize the **V3C dataset** and compete in two main tasks:

- **Known-Item Search (KIS)**  
  Locate a specific video segment based on a detailed textual description.

- **Video Question Answering (VQA)**  
  Answer questions using information from a specific video.

The challenge format draws inspiration from established benchmarks such as **TRECVID** and the **Video Browser Showdown**, encouraging both automated innovation and interactive systems.

---

## Selected Submissions & Methods

### 🏆 CadenceRAG – Winner for VQA

- Utilizes multiple VLMs (e.g., CLIP) to extract features.
- Temporal windowing applied.
- Long queries decomposed into sub-queries.
  - Each sub-query is matched to keyframes.
- Hierarchical retrieval:
  - **Video-level retrieval** → **Shot-level localization**.
- Final step uses a Multimodal LLM (MLLM) for verification.

---

### 🔍 Toward Automation in Text-Based Video Retrieval with LLM Assistance

- Embeddings generated using **SigLIP** and **EVA-LIP**.
- Keyframe retrieval with VLMs.
- Two-stage approach:
  1. **Initial Retrieval**
  2. **LLM-Assisted Reranking**
- Effective pipeline:
  - `ffmpeg` + EVA for keyframe extraction.
  - LLM for final reranking.

---

### 🎥 An LLM Framework for Long-form Video Retrieval and AVQA Using Qwen2/2.5

- Limited performance noted.
- Conceptually similar to others but less effective.

---

### 🌏 VRAG – Vietnamese-Japanese Team (Top KIS, 2nd in VQA)

- Query processing via LLMs (rewrite/decomposition).
- Multimodal retrieval system for initial filtering.
- Workflow:
  - Retrieve candidate videos → Chunk → MLLM Scoring.
- Reranking using MLLMs based on relevance.
- Additional steps:
  - Search surrounding shots for better context.
  - Two-step verification via MLLM QA.
- For VQA, operates in 15s video chunks.
- Uses embedding models rather than caption-based ones for MLLM scoring.

---

## 🔎 Summary of Common Pipeline Components

Most top-performing systems follow a similar pipeline:

1. **Keyframe/Chunk Extraction**
2. **Embedding with CLIP, SigLIP, EVA-LIP, etc.**
3. **LLM-Based Query Decomposition**
   - Break long queries into sub-components.
4. **Relevance Scoring**
   - Match sub-queries to frame/chunk embeddings.
5. **Verification**
   - Use VLM or MLLM QA to confirm final selection.
   - May include point-based or confidence-based scoring.

---

### 🧠 Tools & Models Frequently Used

- **Embedding Models**: CLIP, SigLIP, EVA-LIP
- **Keyframe Extraction**: `ffmpeg` with EVA
- **Query Handling**: GPT-based LLMs for rewriting/decomposition
- **Verification**: BLIP, MLLM QA models

---

For more details, visit the [IViSE 2025 Workshop Website](https://sites.google.com/view/ivise2025).
