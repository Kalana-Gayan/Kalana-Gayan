    # Kalana Gayan — AI & Automation Architect

Hi — I'm Gayan. I'm a **Retail Annotation Expert** (my day job at Trax Retail) who builds the **AI-powered automation pipelines** that will define the future of this industry.

My core strength is combining deep **domain expertise** (I know *exactly* what a good annotation looks like) with the ability to **architect end-to-end AI systems**. I use generative AI as my "junior developer," which allows me to design and build complex, production-ready solutions faster than a traditional team.

* **Live Demo:** [**AI Retail Shelf Detector (YOLOv8)**](https://huggingface.co/spaces/Gayan32/Rack_Detector)
* **Email:** kalanagayan@protonmail.com
* **Fiverr:** [**My Fiverr Profile**](https://www.fiverr.com/s/LdXX954)

---

## 🔥 Featured Portfolio: From Manual Work to Full Automation

My portfolio shows my journey from a manual "Stitcher" to an AI Architect. I build the tools I wish I had.

### 1) AI Retail Shelf Detector (Full Pipeline)
This is my flagship project. It's an end-to-end system that identifies and segments retail shelves, ready for deployment.

* **Repo:** [AI-shelf-detector](https://github.com/Kalana-Gayan/AI-shelf-detector)
* **Live Demo:** [Hugging Face Spaces](https://huggingface.co/spaces/Gayan32/Rack_Detector)
* **What it is:** A complete pipeline starting from data processing, moving to semi-automated labeling, training a **YOLOv8-Seg** model, and deploying it to a **Gradio UI**.
* **Key Metrics:** Trained on **300+ images**, achieved mAP50 ≈ **0.84**, with inference ~**1s**/image (T4 GPU).

| Gradio UI Demo | Example Segmentation Output |
| :---: | :---: |
| <img width="800" alt="Screenshot of the Gradio Web UI for the shelf detector" src="https://github.com/user-attachments/assets/206b6b13-fce7-4324-909c-90e94313e113" /> | <img width="800" alt="Example of YOLOv8 segmentation on a retail shelf" src="https://github.com/user-attachments/assets/ddffe2e3-62d6-4212-94ec-59bc814d9ccb" /> |

### 2) Semi-Auto Labeling Pipeline (CVAT + YOLO)
This pipeline solves the biggest bottleneck in AI: labeling. Instead of labeling from scratch, this system uses a "model-in-the-loop" to accelerate the process by 5-6x.

* **Repo:** [Semi-Auto-Labeling-Pipeline-with-CVAT-YOLO](https://github.com/Kalana-Gayan/Semi-Auto-Labeling-Pipeline-with-CVAT-YOLO)
* **What it does:**
    1.  A baseline **YOLO model** makes initial predictions ("pre-labels") on new images.
    2.  A Python script **converts these YOLO predictions** into the `CVAT XML` format.
    3.  The pre-labeled data is automatically uploaded to CVAT, where a human labeler's job is now to **correct** the AI's work, not start from zero.

| YOLO Pre-Labeling | Data Ready for CVAT Correction |
| :---: | :---: |
| <img width="800" alt="YOLO model pre-labeling new images" src="https://github.com/Kalana-Gayan/Semi-Auto-Labeling-Pipeline-with-CVAT-YOLO/blob/c5beb3b97d2dd5b4a97819f58d83dadee641d274/raw_images/52128488.png" /> | <img width="800" alt="Pre-labeled data imported into CVAT for human correction" src="https://github.com/user-attachments/assets/3e5fbe82-04e1-4981-80f6-b2b3c72bcdaf" /> |

### 3) AI Document Chatbot (RAG API)
This is the core technology for "Chat with your PDF" gigs. It's a backend API that uses a Large Language Model (LLM) to answer natural language questions about a private document.

* **Repo:** [pdf_chat_api](https://github.com/Kalana-Gayan/pdf_chat_api)
* **Tech Stack:** `FastAPI`, `LangChain`, `OpenAI`, `ChromaDB` (Vector Store)
* **What it does:**
    1.  **`POST /upload`**: An endpoint to upload a PDF. The API splits it, creates vector embeddings, and saves them in a **ChromaDB** vector store.
    2.  **`POST /ask`**: An endpoint that takes a user's question. It uses **RAG (Retrieval-Augmented Generation)** to find relevant text chunks from the PDF and feeds them to **GPT-4o** to generate a grounded, factual answer.

### 4) E-commerce Deal Finder Bot (Full Data Pipeline)
An automated bot that scrapes 6pm.com for high-value deals and delivers them to a user in real-time.

* **Repo:** [6pm_product_scrapper](https://github.com/Kalana-Gayan/6pm_product_scrapper)
* **Tech Stack:** `Python`, `Selenium-Stealth`, `Google Sheets API`, `Telegram API`
* **What it does:**
    1.  Uses **Selenium** to scrape a dynamic JavaScript-heavy website.
    2.  Parses data and calculates real-time discount percentages.
    3.  Appends all found deals directly to a **Google Sheet** via API.
    4.  Sends an **instant Telegram alert** for high-priority deals.

---

## 📈 Why Hire Me

* **I'm an Architect, Not Just a Coder:** I don't just write scripts; I design, build, and deploy the *entire system* (Data → Model → API → UI).
* **I'm a Domain Expert:** I've worked as a manual data annotator ("stitcher") at Trax Retail. I don't just build AI for fun; I build it to solve real-world business bottlenecks that I have personally experienced.
* **I'm an AI Orchestrator:** I use AI as a tool to build faster and more reliably. I focus on the architecture and logic, and I use AI to handle the syntax, allowing me to deliver production-grade systems on a freelance timeline.

## 📦 How to Test My Work

The **AI Retail Shelf Detector** is the easiest to test.

1.  **Try the Live Demo:** [**Hugging Face Spaces**](https://huggingface.co/spaces/Gayan32/Rack_Detector)
2.  **Or, run it locally:**
    ```bash
    git clone [https://github.com/Kalana-Gayan/AI-shelf-detector.git](https://github.com/Kalana-Gayan/AI-shelf-detector.git)
    cd AI-shelf-detector
    pip install -r requirements.txt
    python app.py
    ```

## 📬 Contact / Hire

* **Email:** `kalanagayan@protonmail.com`
* **Fiverr:** [**fiverr.com/s/LdXX954**](https://www.fiverr.com/s/LdXX954)
