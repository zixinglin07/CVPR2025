# Conference Papers

This table compiles the papers presented at the conference, including a brief description, poster images, and links to resources such as the paper, code, and video. Some papers are highlighted, best paper candidates, or award candidates.

## Icons Legend

- 🏅 **Best Paper**: This paper has been selected as the best paper of the conference.
- 🏆 **Award Candidate**: This paper is an award candidate.
- 🌟 **Highlighted**: This paper is featured due to its innovation or significance.

## 3D

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **VGGT: Visual Geometry Grounded Transformer** 🏅 | ![Poster Image](assets/vggt.png) | [📄 Paper](https://arxiv.org/abs/2503.11651) <br> [💻 Code](https://github.com/facebookresearch/vggt) <br> [🎥 Video](https://youtu.be/7ZYwJEpCUUA) | 2D video or image to 3d scene model in seconds |
| **S3D: Sketch Driven 3D Model Generation**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Generate 3D face from sketch |
| **Continuous 3D Perception Model with Persistent State**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | 3D perception from video that can be used on dynamic scenes|
| **Robust Multi-Object 4D Generation for In-the-wild Videos**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Chu_Robust_Multi-Object_4D_Generation_for_In-the-wild_Videos_CVPR_2025_paper.pdf) <br> [💻 Code]<br> [🎥 Video] | Can generate dynamic 4d scenes from 2d videos. Motion is captured through a learnt deformation network |
| **CAT4D: Create Anything in 4D with Multi-View Video Diffusion Models**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Chu_Robust_Multi-Object_4D_Generation_for_In-the-wild_Videos_CVPR_2025_paper.pdf) <br> [💻 Code]<br> [🎥 Video] | Create 4D scenes from single video |
| **Uni4D: Unifying Visual Foundation Models for 4D Modeling from a Single Video**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2503.21761) <br> [💻 Code]<br> [🎥 Video] | Create 4D models from single video |

## Audio Video Fusion

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **Adapting to the Unknown: Training-Free Audio-Visual Event Perception with Dynamic Thresholds**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Audio Visual Event understanding to boost foundation models |
| **AVS-Net: Audio-Visual Scale Network for Self-Supervised Monocular Metric Depth Estimation**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Audio-visual approach to depth estimation using echolocation |
| **UWAV: Uncertainty-weighted Weakly-supervised Audio-Visual Video Parsing**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | AVVP approach that overcomes weakness in inter-segment dependencies and achieve SOTA |
| **LongVALE: Vision-Audio-Language-Event Benchmark Towards Time-Aware Omni-Modal Perception of Long Videos**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | A multimodal vision audio language dataset for temporal understanding, and audio-visual event captioning/detection. Also has their own model with training recipe which has good performance for temporal events. |
| **LiveCC: Learning Video LLM with streaming speech transcription at scale**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Live closed-captioning / commentary of streaming video events in real time |
| **Supervising Sound Localization by In-the-wild Egomotion**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Min_Supervising_Sound_Localization_by_In-the-wild_Egomotion_CVPR_2025_paper.pdf) <br> [💻 Code]<br> [🎥 Video] | Sound direction prediction with respect to the position / motion of the camera. Code out soon |
| **AVIGATE: Learning Audio-guided Video Representation with Gated Attention for Video-Text Retrieval**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2504.02397) <br> [💻 Code]<br> [🎥 Video] | A gated fusion approach to toggle audio on and off for video understanding depending learnt relevance. Audio + Video encoded together and identify relevance through gated function with text embeddings. Open Source eventually.  |
| **Robust Audio-Visual Segmentation via Audio-Guided Visual Convergent Alignment**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2503.12847) <br> [💻 Code]<br> [🎥 Video] | Audio Visual segmentation approach through learnt visual audio representations. Open source eventually. |
| **Crab: A Unified Audio-Visual Scene Understanding Model with Explicit Cooperation**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/html/2503.13068v1) <br> [💻 Code]<br> [🎥 Video] | Audio Visual scene understanding architecture that can be used via finetuning |

## Image Restoration / Enhancement

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **HVI: A New Color Space for Low-light Image Enhancement**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Real time deblurring, denoising, low-light and overexposure enhancement |
| **OSDFace: One-Step Diffusion Model for Face Restoration**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2411.17163) <br> [💻 Code]<br> [🎥 Video] | Promising efficient face image enhancer/deblurrer. Can be used in a FR pipeline where initial match uses the blur image with original/augmented database before performing restoration and use it on the actual database if the initial match is beyond a certain threshold |


## Detection, Tracking and Re-identification

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **AG-VPReID 2025: The 2nd Aerial-Ground Person ReID Challenge**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2503.08121) <br> [💻 Code](https://github.com/agvpreid25/AG-VPReID) <br> [🎥 Video](https://youtu.be/00DhDxvwbiY)| Aerial-Ground view re-identification, from 8m to 120m height. Can be used for G2G, G2A, A2G |
| **CaMuViD: Calibration-Free Multi-View Detection** | ![Poster Image](./assets/poster2.png) | [Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Daryani_CaMuViD_Calibration-Free_Multi-View_Detection_CVPR_2025_paper.pdf) <br> [Code](https://github.com/amiretefaghi/CaMuViD) <br> [Video](https://youtu.be/LJzFkKqth6g) | This paper presents [short description of the paper]. Award candidate. |
| **MambaVLT: Time-Evolving Multimodal State Space Model for Vision-Language Tracking**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Vision Language Tracker using State Space model Mamba which is faster than transformers |
| **SAMWISE: Infusing Wisdom in SAM2 for Text-Driven Video Segmentation**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Prompt based segmentation implementation with temporal modelling and error correction for accurate video-based tracking. Can maybe test open vocab POI tracking and re-id |
| **Improving Open-World Object Localization by Discovering Background**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Algorithm Approach to localize scene objects and ignoring background through the use of recognizing top occuring patches and features. Useful for case exhibit use cases and more lightweight |
| **DIFFER: Disentangling Identity Features via Semantic Cues for Clothes-Changing Person Re-ID**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2503.22912) <br> [💻 Code]<br> [🎥 Video] | Re-id aimed to use learnt features from VLM to re-identifying persons that changed clothes through the use of Gradient-Reversal Layers |
| **Focusing on Tracks for Online Multi-Object Tracking**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Shim_Focusing_on_Tracks_for_Online_Multi-Object_Tracking_CVPR_2025_paper.html) <br> [💻 Code](https://github.com/kamkyu94/TrackTrack)<br> [🎥 Video] | Tracking approach to leverage more on tracklets to track than heavy reliance on detection from regular trackers |
| **All-Day Multi-Camera Multi-Target Tracking**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://cvpr.thecvf.com/virtual/2025/poster/35125)<br> [💻 Code]<br> [🎥 Video] | Day and Night multicamera and multitarget tracking algorithm/models with built in re-id for cross-camera association |
| **EntitySAM: Segment Everything in Video**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://cvpr.thecvf.com/virtual/2025/poster/35125)<br> [💻 Code] (https://github.com/yuanc3/Pose2ID)<br> [🎥 Video] | SAM based tracking with memory encoder using features from Dinov2 as prompt into SAM |
| **Pose2ID: From Poses to Identity: Training-Free Person Re-Identification via Feature Centralization**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://cvpr.thecvf.com/virtual/2025/poster/35125)<br> [🎥 Video] | Uses human + pose estimation to generate more images of the target person for feature enhancement through the use of StableDiffusion. Training free and modular, allowing for use of other re-id and pose estimation model. Speed may not be optimized. |
| **Learning from Synchronization: Self-Supervised Uncalibrated Multi-View Person Association in Challenging Scenes**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2503.13739)<br> [🎥 Video] | Approach to handle multiview association for synchronized footage (same timestamp) for detection tracking and re-id. Only intended for overlapping cameras. |
| **On Denoising Walking Videos for Gait Recognition**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2505.18582)<br> [🎥 Video] | An update from OpenGait to denoise walking videos for better gait extraction. Code out soon.|

## Deepfake

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **Diagnosing and Treating Audio-Video Fake Detection**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Introduces DeepSpeak, an audio-video deepfake detector |
| **Rethinking Vision-Language Model in Face Forensics: Multi-Modal Interpretable Forged Face Detector**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Multimodal Forged Face detector using VLM for text-based identification and explainability |


## Edge Models

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **EdgeVidSum: Real-Time Personalized Video Summarization at the Edge**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Video Summarisation on Edge |
| **EdgeTAM: On-Device Track Anything Model**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | SAM2 Tracking on edge with 20x speed up on edge device|
| **LLMPi: Optimizing LLMs for High Throughput on Raspberry Pi**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Research on efficient Best-in-Slot edge deployment of LLMs and proposed speech to speech pipeline |

## Foundation Models and Encoders

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **Token Cropr: Faster ViTs for Quite a Few Tasks**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Faster ViT |
| **Perception Encoder: The best visual embeddings are not at the output of the network**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | New CLIP by meta, surpass CLIP for image tasks, with limited video capability due to poor temporal knowledge |
| **REN: Fast and Efficient Region Encodings from Patch-Based Image Encoders**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | High Speed and efficient image region encoders |
| **CAV-MAE Sync: Improving Contrastive Audio-Visual Mask Autoencoders via Fine-Grained Alignment**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Better audio visual representation |
| **AdaVid: Adaptive Video-Language Pretraining**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Scalable Video-Language foundation model for various compute requirements |
| **HoVLE: Unleashing the Power of Monolithic Vision-Language Models with Holistic Vision-Language Embedding**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2412.16158) <br> [💻 Code]<br> [🎥 Video] | Alleviates loss of textual capability in LLMs when training into a VLM through the conversion of multimoda embeddings into hollistic embeddings |
| **MambaVision: A Hybrid Mamba-Transformer Vision Backbone**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2407.08083) <br> [💻 Code]<br> [🎥 Video] | Alleviates loss of textual capability in LLMs when training into a VLM through the conversion of multimoda embeddings into hollistic embeddings |


## Video Understanding / Summary

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **VideoICL: Confidence-based Iterative In-context Learning for Out-of-Distribution Video Understanding**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2412.02186) <br> [💻 Code](https://github.com/KangsanKim07/VideoICL)<br> [🎥 Video](https://youtu.be/00DhDxvwbiY)| In Context Learning approach for video understanding. |
| **STPro: Spatial and Temporal Progressive Learning for Weakly Supervised Spatio-Temporal Grounding**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Process Spatial and Temporal separately for better understanding |
| **Open World Scene Graph Generation using VLM**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | A trainingless VLM and grounding DINO appoach to generate scene graph |
| **SimCache: Similarity Caching for Efficient VLM-based Scene Understanding**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Proposed idea of software cache to store scene embeddings and reduce need for redundant frame inference for similar frames. No paper. |
| **Video-XL: Extra-Long Vision Language Model for Hour-Scale Video Understanding**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] (https://arxiv.org/abs/2409.14485) <br> [💻 Code](https://github.com/VectorSpaceLab/Video-XL/tree/main/Video-XL-2) <br> [🎥 Video] | Proposed Llava + compression + dynamic interval pipeline. Frame cosine similarity to decide dynamic sampling interval (low fps for high similarity) |
| **SEAL: Semantic Attention Learning for Long Video Representation**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] (https://arxiv.org/abs/2412.01798) <br> [💻 Code](https://github.com/VectorSpaceLab/Video-XL/tree/main/Video-XL-2) <br> [🎥 Video] | Overcoming challenges in video understanding by decomposing to scene, object and action based understanding. Through specialized tokens and incorporation of other modules such as SAM for more hollistic and accurate understanding. |



## VLM

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **Dispider: Enabling Video LLMs with Active Real-Time Interaction via Disentangled Perception, Descision and Reaction**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Streaming VLM that can proactively provide streaming response over time without the need for repeated use prompting |
| **FastVLM: Efficient Vision Encoding for Vision Language Models**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2412.13303) <br> [💻 Code]<br> [🎥 Video] | 0.5b to 7b VLM that can process HD videos in speeds faster than Smolvlm 0.5b through the use of their custom FastViTHD backbone. By Apple. |
| **Dino.txt: DINOv2 Meets Text: A Unified Framework for Image- and Pixel-Level Vision-Language Alignment**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2412.13303) <br> [💻 Code]<br> [🎥 Video] | Enhancing dinov2 with text ability, surpasses CLIP for image-text association and representation learning  |


## Video Grounding / Search

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **VideoGEM: Training-free Action Grounding in Videos**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Perform prompt decomposition and use static and dynamic weighting GEM module to do action recognition |
| **Re-thinking Temporal Search for Long-Form Video Understanding**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Smart frame selector leveraging on cue and target object search using additional module for zero-shot detection and scoring to identify possible locality before zooming into segment for in depth analysis |
| **RELOCATE: A Simple Training-Free Baseline for Visual Query Localization Using Region-Based Representations**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Using SAM and DINO to perform image-based object query on videos |
| **BIMBA: Selective Scan Compression for Long Range Video QA**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Uses MAMBA for video search and scanning of spatial-temporal tokens. Said to be more efficient than transformer based architectures |
| **Number it: Temporal Grounding Videos like Flipping Manga**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Simple idea of video search by appending a frame/page number to the top left of the image, allowing VLM to identify which frame contains the information of interest |
| **ReVisionLLM: Recursive Vision-Language Model for Temporal Grounding in Hour-Long Videos**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2411.14901) <br> [💻 Code]<br> [🎥 Video] | Idea to train an encoder module to identify the rough location of the target video scene in 5min chunk, before zooming into frame-level for specific target segment|

## Temporal and Motion in VLM

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **Temporal Alignment-Free Video Matching for Few-shot Action Recognition**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Few shot action recognition for unseen or OOD actions via clustering |
| **MotionBench: Benchmarking and Improving Fine-grained Video Motion Understanding for Vision Language Models**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | A motion focused dataset and benchmark for VLM, including novel TE-Fusion module to enhance pre-trained VLM's with better finegrained motion understanding |
| **Context-Enhanced Memory-Refined Transformer for Online Action Detection**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Real Time Action detection |

## Pre-training, Finetuning and Visualization

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **Prompt-CAM: Making Vision Transformers Interpretable for Fine-Grained Analysis**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | A simple finetune model to visualize a pre-trained model's attention behaviour |
| **Molmo and PixMo: Open Weights and Open Data for State-of-the-Art Vision-Language Models**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2409.17146) <br> [💻 Code]<br> [🎥 Video] | Presents state of the art VLM and dataset by Ai2 that excels in academia, image-based counting and pointing  |
| **Identifying and Mitigating Position Bias of Multi-image Vision-Language Models**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2503.13792) <br> [💻 Code]<br> [🎥 Video] | An evaluation of multi-image VLM captioning and attention bias, and proposes a way to overcome it using  SOFt Attention (SOFA) |
| **Mitigating Hallucinations in Large Vision-Language Models via DPO: On-Policy Data Hold the Key**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2501.09695) <br> [💻 Code]<br> [🎥 Video] | A novel DPO framework called On-Policy Alignment-DPO (OPA-DPO) to further reduce hallucination to overcome the KL divergence between updated policy and reference policy in standard DPO  |
| **Thinking in Space: How Multimodal Large Language Models See, Remember, and Recall Spaces**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2412.14171#:~:text=We%20probe%20models%20to%20express,do%20emerge%20within%20these%20models.) <br> [💻 Code]<br> [🎥 Video] | Identifies inherent limitation with VLMs in video-based spatial awareness extending to counting, distance and referencing objects. Paper proposes dataset repurposed from 3D dataset to alleviate some of these problems  |
| **Overcoming Shortcut Problem in VLM for Robust Out-of-Distribution Detection**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2503.13792) <br> [💻 Code]<br> [🎥 Video] | Identifies the issue of background interference in VLM's for OOD data, associating background of in-domain training for classification. Proposes finetuning dataset to overcome this problem |
| **LoRASculpt: Sculpting LoRA for Harmonizing General and Specialized Knowledge in Multimodal Large Language Models**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2503.16843) <br> [💻 Code]<br> [🎥 Video] | Approach to overcome catastrophic forgetting issue from lora - via freezing connector. Surpass lora peft based approaches. |

## Segmentation

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **CALICO: Part-Focused Semantic Co-Segmentation with Large Vision-Language Models**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Part Segmentation Model for human/animal parts |
| **Describe Anything: Detailed Localized Image and Video Captioning**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] |Efficient VLM to describe SAM segments in detail, could be used for detailed PAR/VAR |
| **Mamba as a Bridge: Where Vision Foundation Models Meet Vision Language Models for Domain-Generalized Semantic Segmentation**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2504.03193) <br> [💻 Code]<br> [🎥 Video] | Using MAMBA to bridge the capabilites of CLIP in text-alignment and DINOv2 in capturing features to perform semantic segmentation |
| **Your ViT is Secretly an Image Segmentation Model**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2503.19108) <br> [💻 Code]<br> [🎥 Video] | Low-param transformer only segmentation model, can explore for lightweight options |
| **Effective SAM Combination for Open-Vocabulary Semantic Segmentation**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2411.14723) <br> [💻 Code]<br> [🎥 Video] | Efficient open vocab segmentation for SAM using proposes ESC-Net pipeline |

## Video Anomaly Detection

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **Track Any Anomalous Object: A Granular Video Anomaly Detection Pipeline**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Pixel Level anomaly detection and tracking for more fine-grained anomaly detection compared to scene or object anomaly |
| **VERA: Explainable Video Anomaly Detection via Verbalized Learning of Vision-Language Models**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Verbalized Learning approach for VLM to detect anomaly using learnable guide prompts. The anomaly detection module is a small module based on the VLM to learn a set of guiding questions based on the input prompt to help the VLM verbalize and generalize better. |
| **Shopformer: Transformer-Based Framework for Detecting Shoplifting via Human Pose**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Pose-based shoplifting detection based on US privacy laws |
| **AssistPDA: An Online Video Surveillance Assistant for Video Anomaly Prediction, Detection, and Analysis**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Live VLM based anomaly and crime detection by NUS. No code yet |



## Traffic Understanding

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **RoadSocial: A Diverse VideoQA Dataset and Benchmark for Road Event Understanding from Social Video Narratives**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | A dataset collected from traffic videos all over the world, including violation videos for traffic event QA, captioning and violation detection etc. The team finetuned their own Llava OV model on the dataset which can be tested |
| **EchoTraffic: Enhancing Traffic Anomaly Understanding with Audio-Visual Insights**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://openaccess.thecvf.com//content/CVPR2025/papers/Xing_EchoTraffic_Enhancing_Traffic_Anomaly_Understanding_with_Audio-Visual_Insights_CVPR_2025_paper.pdf) <br> [💻 Code]<br> [🎥 Video] | Audio-Visual-Text approach for traffic anomaly understanding using a fusion of audio spectro signal to identify possible emergency brakes, collisions and repeated horning. Proposes dataset and finetuned model |
| **Embodied Scene Understanding for Vision Language Models via MetaVQA**  | ![Poster Image](./assets/poster1.png) | [📄 Paper] <br> [💻 Code]<br> [🎥 Video] | Embodied traffic scene understanding for vla via MetaVQA, trained on real and ego-centric video. But do not have knowledge of violation due to vla focus. |


## Vision Language Action (VLA)

| Paper Title | Poster | Resources | Description |
|-------------|--------|-----------|-------------|
| **Magma: A Foundation Model for Multimodal AI Agentst**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/abs/2502.13130) <br> [💻 Code]<br> [🎥 Video] | All in one robot based VLM includng various VLA and agentic tasks. Still limited in terms of robot navigation, expected to have a updated version later in 2025 |
| **From Multimodal LLMs to Generalist Embodied Agents: Methods and Lessons**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/html/2412.08442v1) <br> [💻 Code]<br> [🎥 Video] | Proposed method to train generalist embodied agents for VLA from MLLMs |
| **Plug-and-Play Versatile Compressed Video Enhancement**  | ![Poster Image](./assets/poster1.png) | [📄 Paper](https://arxiv.org/html/2412.08442v1) <br> [💻 Code]<br> [🎥 Video] | Method to overcome reduction in video quality from compressed video, proposes enhancement approach. Code to be out soon. |
