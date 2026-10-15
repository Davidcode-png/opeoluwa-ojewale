---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can also download my full CV as PDF (upload yours to `files/`): [CV.pdf](/files/CV.pdf)

Education
======
* **B.Sc. Computer Science, First Class Honours (3.59/4.00)**, University of Ibadan, Ibadan, Nigeria, 2019--2025
  * Thesis: *Audiosum: Development of a Multimodal Video Summarization Framework Using Pre-trained CNN Models.* [Manuscript & results](https://drive.google.com/open?id=1ifysSjw_GcsJUe7GUZ252RC7v9fhoKe7&usp=drive_fs)
  * Coursework: Machine Learning, Intelligent Systems, Human-Computer Interaction, Software Engineering, Design and Analysis of Algorithms, OOP, Web Programming, Database Systems.
  * Interests: Deep Learning, Computer Vision, Computer Graphics, Transformers, Compression, Visual Recognition.

Research experience
======
* **Research Assistant, Computer Vision** (Jul 2025 -- Dec 2025), University of Ibadan -- Multi-Cue Person Detection and Recognition in Unstructured Environments
  * Engineered deep models over posture, movement, and shadow signatures; fine-tuned YOLO for real-time posture detection; built UNET pipeline for shadow-signature extraction; curated/annotated large-scale video dataset in CVAT.
* **B.Sc. Research Project** (Aug 2024 -- Feb 2025), University of Ibadan -- Audiosum
  * Novel multimodal summarization with ResNet50/VGG16 visual features + custom audio extractor; FC-layer fusion; LSTM temporal modeling.
* **Project Lead** (Oct 2023 -- Dec 2023) -- Data Mining System for Sales Prediction in a Publishing House Using ANN
  * LSTM vs RNN vanishing-gradient study; KDD + sentiment features; precision/F1 evaluation; co-authored decision-support study for inventory optimization.

Work experience
======
* **Backend & Data Engineer (Data/ML focus)** (Apr 2023 -- Present), Kole Software, Lagos (Remote)
  * BigQuery analytics + BigQuery ML + Vertex AI training/serving; Airflow + dbt ETL/ELT; RAG with Bedrock + vector embeddings; Playwright pricing pipeline; Postgres tuning (+65% retrieval); Terraform (Lambda/SQS/S3) + GitLab CI zero-downtime ECS; Django REST sub-200ms APIs.
* **Software Engineer Fellow** (Sep 2025 -- Dec 2025), Major League Hacking, New York (Remote)
  * Fixed flaky Consul.NET tests, +15% coverage, Agile code reviews/sprints.
* **Backend Engineer** (Sep 2022 -- Mar 2023), Ikook, Lagos
  * Indexed queries + Redis caching (-30% latency); Flutterwave/Stripe/Paystack webhooks; Docker + AWS/Heroku (-25% release cycles).
* **Software Engineer Intern** (Jan 2022 -- Jun 2022), Imisi 3D, Lagos
  * Laval Virtual hackathon VR Energy Sustainability demo (Unity); AR/VR PoCs (ARCore/ARKit/Vuforia); Lagos AR/VR meetup keynote on AR; volunteer at Africa's first XR event.

Skills
======
* **ML:** supervised/unsupervised, classification, forecasting, precision/recall/F1, feature engineering, scikit-learn, PyTorch, TensorFlow, Hugging Face Transformers
* **Multimodal & CV:** video summarization, audio-visual fusion, YOLOv8/v11, UNET, ResNet50/VGG16, LSTM, ViT, OpenCV, CVAT, Albumentations
* **GenAI & Search:** embeddings, semantic retrieval, RAG (Bedrock, LangChain), sentiment analysis
* **Cloud:** GCP (BigQuery, BigQuery ML, Vertex AI), AWS (S3/Lambda/SQS/ECS/Bedrock), Azure
* **Data & SQL:** Python, advanced SQL (CTEs, windows, tuning), Pandas/NumPy/SciPy, Jupyter, Airflow, dbt, PostgreSQL/MongoDB/Redis
* **Viz:** Matplotlib, Seaborn, Streamlit, Grafana, Weights & Biases
* **MLOps & Eng:** Docker, Terraform, GitLab CI/CD, FastAPI/Django/.NET Core, C#/Rust/JS, Git, LaTeX; XR: Unity, ARCore/ARKit, Vuforia

Honors, awards & affiliations
======
* Black in AI Emerging Leaders in AI (ELAI '26) -- cohort mentorship for competitive AI graduate programs
* NHEF Scholar 2024 -- Top 100 nationally
* Dean's Roll of Honour 2024, University of Ibadan
* Certificate of Excellence, BSFUI 2024 (First Class)
* Memberships: Black in AI, MLH Fellow, NHEF Scholar, Google Developers Club

Leadership & service
======
* Conference Team Lead, NACOSS "Tech Fusion" 2025 -- end-to-end planning, 300+ attendees
* Media & Library Secretary (2024), Baptist Student Fellowship, University of Ibadan

Workshops & conferences
======
* UNESCO AI Education Workshop; NACOSS UI 2025; NHEF Workshop Conferences

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Portfolio
======
  <ul>{% for post in site.portfolio reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
