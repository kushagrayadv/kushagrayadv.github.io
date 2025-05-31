---
layout: page
title: "Big Data Projects"
---

<div class="project-card">
  <div class="project-card-content">
    <h3>WISDM Activity Recognition System</h3>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch"><img src="https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=apachespark&logoColor=white" alt="Spark"><img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white" alt="Kafka"><img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black" alt="HuggingFace"><img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white" alt="Streamlit">
      <ul>
        <li>End-to-end streaming pipeline: ingests raw phone and watch accelerometer/gyroscope data via Kafka, aligns and normalises on the fly, and assembles 100 × 6 windows at 50 Hz.</li>
        <li>Lightweight CNN–BiLSTM-attention model trained on WISDM v2.0 (18 classes) with subject-wise splits; achieves 91 % validation accuracy using Parquet-sharded windows for fast PyTorch loading.</li>
        <li>Live inference service: background Kafka consumer with GPU model server delivers activity labels in under 200 ms end-to-end latency while buffering irregular samples and handling multiple devices concurrently.</li>
        <li>Interactive Streamlit dashboard displays real-time six-axis sensor plots and a dynamic activity badge with confidence score, providing instant feedback for fitness tracking or clinical monitoring.</li>
      </ul>
      <p><a href="https://github.com/kushagrayadv/CSGY-6513-big-data-project" target="_blank" rel="noopener noreferrer">View Project</a></p>
  </div>
  <img src="/assets/projects/activity-rec.jpg" alt="activity rec" class="project-card-img" />
</div>
