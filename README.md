# 🧠 Saman Zeitounian

**Data Scientist | Machine Learning Engineer | LLM Engineer**

📍 Tehran, Iran
📧 [samanzeitounian@gmail.com](mailto:samanzeitounian@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/saman-zeitounian-56a0a5164/) • [GitHub](https://github.com/samyvivo) • [Hugging Face](https://huggingface.co/samyhusy) • [Kaggle](https://www.kaggle.com/samanzeitounain)how to see readme.md in markdown version code in vs code

---

## 🧾 Professional Summary

Data Scientist and Machine Learning Engineer with 5+ years of experience building applied AI systems across FMCG sales, computer vision, and multilingual NLP. At **Payon Distribution Co.**, I develop time-series sales forecasts, intelligent decision dashboards, and Deeplearning-based shelf-share detection for chain-store environments.

I compare statistical and machine-learning forecasting algorithms, engineer calendar and commercial features, and tune models against time-ordered validation data. I track **RMSE, MAE, MAPE, and WAPE**, inspect bias and segment-level errors, and refine models to reduce forecast error. My computer-vision work includes collecting and annotating local shelf images, fine-tuning pretrained detectors, tuning training hyperparameters, and measuring brand presence on shelves. I also work with **PyTorch**, **Hugging Face Transformers**, **LoRA/PEFT**, and **RAG** for Persian and English AI applications.

---

## 🧰 Core Skills

| Category                    | Tools & Technologies                                                                                                                     |
| --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| **Languages**         | Python, R, SQL, Bash                                                                                                                     |
| **Frameworks**        | PyTorch, Ultralytics YOLO, Hugging Face Transformers, Scikit-learn, Power BI                                                             |
| **Forecasting & ML**  | Time-series validation, feature engineering, hyperparameter tuning, XGBoost, CatBoost, Prophet, Holt-Winters, RMSE, MAE, MAPE, WAPE      |
| **Computer Vision**   | Object detection, local dataset curation and annotation, model fine-tuning, precision, recall, mAP50, mAP50–95, shelf-share measurement |
| **Specialties**       | NLP, LLM fine-tuning (LoRA/PEFT), Transformer models, RAG                                                                                |
| **Data & Deployment** | SQL Server, Pandas, Docker, Gradio, Streamlit, AWS, GPU optimization                                                                     |

---

## 💼 Professional Experience

### **Data Scientist & Machine Learning Engineer**

**[Payon Distribution Co.](https://www.linkedin.com/company/payonco/)**, Tehran | *Current role*

- Built an intelligent FMCG sales dashboard combining interactive KPIs, customer/product/channel analysis, scenario planning, and time-series forecasts for commercial decisions.
- Developed and compared statistical and ML forecasting approaches, including Holt-Winters, Prophet, gradient-boosted trees, and ensemble methods; engineered Persian calendar and sales features and evaluated forecasts with time-ordered splits.
- Monitored **RMSE, MAE, MAPE, WAPE, and forecast bias** by period and business segment; tuned features, algorithms, and hyperparameters to improve forecast accuracy and expose error patterns to stakeholders.
- Developed a **Deeplearning-based live shelf detection and shelf-share pipeline** for large chain stores, identifying Payon brands and competing products and calculating brand share from product detections.
- Curated and annotated a local dataset of store shelves and product packaging; fine-tuned pretrained detection models and tuned image size, learning rate, batch size, augmentation, and training duration to adapt the model to local shelves and products.
- Tracked **precision, recall, mAP50, and mAP50–95** across validation runs; reviewed false positives, missed products, and class confusion to identify annotation and model errors, then refined the local dataset and training settings to improve detection quality.
- Built data preparation and reporting workflows with Python, SQL Server, Power BI, and Streamlit for sales analysis and forecasting.

---

### **LLM Engineer & Machine Learning Engineer**

**[Targoman Intelligent Processing](https://www.linkedin.com/company/targoman-intelligent-processing/people/?keywords=freepaper)**, Tehran | *Jul 2018 – Jan 2023*

- Developed bilingual Seq2Seq translation models using RNN/LSTM with attention for Persian–English translation.
- Transitioned RNN architectures to transformer-based LLMs (LLaMA, BERT, T5) trained on large Persian corpora.
- Integrated ML models into production services with monitoring and performance evaluation.

---

### **Independent / Open-Source Contributor**

*Feb 2023 – Present*

- Designed multilingual text/image captioning pipelines using **LoRA fine-tuning** on Persian datasets.
- Developed **RAG architectures** enabling efficient context retrieval with minimal latency.
- Optimized quantization and mixed-precision inference for **60% faster** performance on **A100/T4 GPUs**.
- Contributed to open-source repositories for **OCR**, **translation**, and **text-to-text** tasks.

---

## 🚀 Selected Projects

| Project                                    | Description                                                                                                                                          | Link                                                                            |
| ------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| **Object Studio – Live Detection**  | Browser-camera object detection and tracking for 31 product classes, with live statistics, snapshots, MP4 recording, and CSV/JSON exports.           | [GitHub](https://github.com/samyhusy/Object_Detection)                           |
| **Intelligent Sales Dashboard**      | Persian-language FMCG analytics, scenario planning, and time-series forecasting with model comparison and RMSE, MAE, MAPE, and WAPE evaluation.      | [GitHub](https://github.com/samyvivo/payonco)                                    |
| **Chain-Store Shelf Share**          | Locally fine-tuned YOLO detector for own and competing products; estimates brand share and tracks precision, recall, and mAP across validation runs. | —                                                                              |
| **Seq2Seq Translator**               | Bilingual Transformer translator for English–Persian text with BLEU evaluation and attention visualization.                                         | [GitHub](https://github.com/samyvivo/seq2seq_translator)                         |
| **OCR – DeepSeek Multilingual VLM** | Multilingual OCR app using DeepSeek-OCR for Persian & English text extraction, deployed on Hugging Face Spaces.                                      | [GitHub](https://github.com/samyvivo/OCR)                                        |
| **SnapFood Sentiment Analysis**      | Fine-tuned BERT model achieving 91% accuracy on restaurant reviews with custom tokenization.                                                         | [GitHub](https://github.com/samyvivo/Snap_Food_Sentiment_Analysis_BERT_Model_en) |
| **Tehran Real Estate Prediction**    | Ensemble regression model with engineered spatial and textual features (R² = 0.89).                                                                 | [GitHub](https://github.com/samyvivo/Tehran_Real_Estate_House_Price_Prediction)  |
| **Loan Status Prediction**           | Robust ML pipeline with feature selection, LightGBM & CatBoost model comparison (96% accuracy).                                                      | [GitHub](https://github.com/samyvivo/Loan-Status-Prediction-eng)                 |
| **Medicine Recommendation System**   | NLP-based recommendation engine suggesting alternatives from textual prescriptions.                                                                  | [GitHub](https://github.com/samyvivo/Medicine_Recommendation_System)             |

### About Object Studio

Object Studio is an app that sends browser-camera frames over WebRTC to a local YOLO11 model for live detection and tracking. It shows class-colored boxes, confidence scores, tracking IDs, movement trails, and session statistics. Users can download annotated snapshots and MP4 recordings or export detection logs as CSV or JSON. The app supports CPU and NVIDIA GPU inference, HTTPS access on a local network, and optional Docker deployment.

See the [project README](./README.md) for setup and usage.

### About Intelligent Sales Dashboard

Intelligent Sales Dashboard is a Persian-language application for exploring sales data and planning future sales. It accepts Excel and CSV files and combines interactive analytics, scenario planning, monthly machine-learning forecasts, and comparisons of time-series foundation models. A companion app provides daily forecasts. The project uses Python, Pandas, Plotly, scikit-learn, CatBoost, XGBoost, LightGBM, Holt-Winters, and Prophet. Forecast evaluation includes RMSE, MAE, MAPE, and WAPE, with attention to error by product, channel, and period.

See the [Payon project README](https://github.com/samyvivo/payonco#readme) for setup instructions and details about the forecasting workflows.

### About Chain-Store Shelf Share

The shelf-share project adapts YOLO to locally captured chain-store images so it can distinguish Payon products from competing brands. I evaluate **precision** (how many predicted products are correct) and **recall** (how many labeled products the model finds). I monitor **mAP50** at an intersection-over-union threshold of 0.50 and **mAP50–95** across thresholds from 0.50 to 0.95, which makes localization quality visible beyond a single threshold. Comparing these metrics by class and training run helps identify false detections, missed products, and inconsistent bounding boxes; I use those findings to revise annotations, add representative local images, and tune model hyperparameters before calculating shelf share.

---

## 🎓 Education

**Master of Computer Science – Artificial Intelligence**
*Damghan University of Technology (2023)*
GPA: 18.88 / 20

---

## 🏅 Certifications

- [Data Scientist (Professional)](https://verify.w3schools.com/1Q41HDZLQB)
- [Data Analyst (Advanced)](https://verify.w3schools.com/1Q41HFGY29)
- [Python Developer (Advanced)](https://verify.w3schools.com/1PNLGEFK8F)
- [R Developer (Professional)](https://verify.w3schools.com/1PUOR16YJ5)
- [SQL Developer (Professional)](https://verify.w3schools.com/66T43YDZM)

---

## 🌍 Languages

- English — Fluent
- Persian — Native

---

## 💡 Interests

Open-Source AI Research • Multilingual NLP • Algorithm Optimization • Generative Models

---

> 📄 **Download PDF version:** [Saman_Zeitounian.pdf](./Saman_Zeitounian.pdf)
