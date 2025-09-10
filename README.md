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
# Kalana Gayan  — AI & Data Pipelines

Hi — I'm Gayan. I build AI pipelines that turn messy images into production-ready models and deployable apps.  
Live demo: **[Click](https://huggingface.co/spaces/Gayan32/Rack_Detector)**

• Contact: kalanagayan@protonmail.com

---

## 🔥 Highlight Projects

### 1) AI Retail Shelf Detector — YOLOv8 (Production prototype)  
**Repo:** [Rack Detector](https://github.com/Kalana-Gayan/AI-shelf-detector)  
**Live demo:** [Demo](https://huggingface.co/spaces/Gayan32/Rack_Detector)  
**One-liner:** End-to-end pipeline: semi-auto labeling → train → deploy.  
**Key metrics:** trained on **300+ images**, mAP50 ≈ **0.84**, inference ~**1s**/image (T4).  
**Screenshots:** <img width="1003" height="715" alt="Screenshot from 2025-09-10 14-34-11" src="https://github.com/user-attachments/assets/206b6b13-fce7-4324-909c-90e94313e113" />,
 <img width="1431" height="772" alt="Screenshot from 2025-09-10 14-34-54" src="https://github.com/user-attachments/assets/ddffe2e3-62d6-4212-94ec-59bc814d9ccb" />


---

### 2) Semi-Auto Labeling Pipeline (CVAT + YOLO)  
**Repo:** [Lable Pipeline](https://github.com/Kalana-Gayan/Semi-Auto-Labeling-Pipeline-with-CVAT-YOLO)  
**One-liner:** Model pre-label → CVAT import → human correct = **5–6x** faster labeling.  
**What I did:** convert model outputs → CVAT format + upload automation.  
**Screenshots:** https://github.com/Kalana-Gayan/Semi-Auto-Labeling-Pipeline-with-CVAT-YOLO/blob/c5beb3b97d2dd5b4a97819f58d83dadee641d274/raw_images/52128488.png ,
<img width="1177" height="694" alt="Screenshot from 2025-09-10 14-51-44" src="https://github.com/user-attachments/assets/3e5fbe82-04e1-4981-80f6-b2b3c72bcdaf" />



---

### 3) Dataset Wrangler (Resizer / Splitter / Augment)  
**Repo:** [Dataset Wrangler](https://github.com/Kalana-Gayan/dataset-wrangler)  
**One-liner:** Small toolkit of scripts to rename, datacleanup, split, and class balance, datasets.  
**Run demo:** `python cleanup_dataset.py --dir /path/to/folder [--dry-run]`

---

### 4) Dataset Labeling Demo (CVAT + Segmentation)  
**Repo:** [(https://github.com/Kalana-Gayan/Dataset-Labeling-Demo)]  
**One-liner:** Pixel-perfect segmentation examples exported to YOLO format.  
**Screenshots:** ![segmented](https://github.com/Kalana-Gayan/Dataset-Labeling-Demo/blob/ab6f7c0d9833f11322783aa9887fc3f50acc9a04/samples/segmented_rack01.png)

---

## 📦 How to test my work
- Clone any repo → follow README.  
- Quick run:  
```bash
git clone https://github.com/Kalana-Gayan/AI-shelf-detector.git
cd AI-shelf-detector
pip install -r requirements.txt
python inference.py --weights model/best.pt --source demo/in_001.jpg --save-result
```
## 📈 Why hire me

- I deliver end-to-end pipelines (data → model → UI) that save time and integrate into real workflows (CVAT, exports, Gradio).
- I focus on automation and robustness — not toy demos.
## 📬 Contact / Hire
Email: kalanagayan@protonmail.com

Fiverr: [(https://www.fiverr.com/s/LdXX954)]
