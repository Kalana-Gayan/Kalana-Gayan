## Hi there 👋

<!--
**Kalana-Gayan/Kalana-Gayan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# Gayan Mukuru — AI & Data Pipelines

Hi — I'm Gayan. I build AI pipelines that turn messy images into production-ready models and deployable apps.  
Live demo: **[(https://huggingface.co/spaces/Gayan32/Rack_Detector)]** • Contact: kalanagayan@protonmail.com

---

## 🔥 Highlight Projects

### 1) AI Retail Shelf Detector — YOLOv8 (Production prototype)  
**Repo:** [(https://github.com/Kalana-Gayan/AI-shelf-detector)]  
**Live demo:** [(https://huggingface.co/spaces/Gayan32/Rack_Detector)]  
**One-liner:** End-to-end pipeline: semi-auto labeling → train → deploy.  
**Key metrics:** trained on **300+ images**, mAP50 ≈ **0.84**, inference ~**1s**/image (T4).  
**Demo GIF:** ![demo](path/to/demo_shelf.gif)

---

### 2) Semi-Auto Labeling Pipeline (CVAT + YOLO)  
**Repo:** [https://github.com/Kalana-Gayan/Semi-Auto-Labeling-Pipeline-with-CVAT-YOLO]  
**One-liner:** Model pre-label → CVAT import → human correct = **5–6x** faster labeling.  
**What I did:** convert model outputs → CVAT format + upload automation.  
**Screenshots:** ![before](https://github.com/Kalana-Gayan/Semi-Auto-Labeling-Pipeline-with-CVAT-YOLO/blob/c5beb3b97d2dd5b4a97819f58d83dadee641d274/raw_images/52128488.png) ![after](https://github.com/Kalana-Gayan/Semi-Auto-Labeling-Pipeline-with-CVAT-YOLO/blob/c5beb3b97d2dd5b4a97819f58d83dadee641d274/predictions/52128488.jpg)

---

### 3) Dataset Wrangler (Resizer / Splitter / Augment)  
**Repo:** [github.com/yourusername/dataset-wrangler]  
**One-liner:** Small toolkit of scripts to rename, resize (640×640), split, and augment datasets.  
**Run demo:** `python resize_images.py --input demo/ --output resized/`

---

### 4) Dataset Labeling Demo (CVAT + Segmentation)  
**Repo:** [github.com/yourusername/Dataset-labeling-Demo]  
**One-liner:** Pixel-perfect segmentation examples exported to COCO format.  
**Screenshots:** ![segmented](samples/segmented_rack.jpg)

---

## 📦 How to test my work
- Clone any repo → follow README.  
- Quick run:  
```bash
git clone https://github.com/yourusername/AI-shelf-detector.git
cd AI-shelf-detector
pip install -r requirements.txt
python inference.py --weights model/best.pt --source demo/in_001.jpg --save-result
