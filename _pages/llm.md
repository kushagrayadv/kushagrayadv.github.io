---
layout: page
title: "LLM Projects"
---

<div class="project-card">
  <div class="project-card-content">
    <h3>VoxelFormer: Parameter-Efficient Multi-Subject Visual Decoding from fMRI</h3>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python"><img src="https://img.shields.io/badge/wandb-FFBE00?style=flat&logo=weightsandbiases&logoColor=black" alt="WandB"><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black" alt="HuggingFace">
      <ul>
        <li>Designed a lightweight transformer architecture for image reconstruction from fMRI, enabling multi-subject training without subject-specific layers.</li>
        <li>Developed Token Merging Transformer (ToMer) to compress voxel inputs dynamically, reducing memory usage while retaining essential features.</li>
        <li>Integrated a query-driven Q-Former to produce fixed-size latent vectors aligned with CLIP’s image embedding space.</li>
        <li>Achieved competitive performance with just 39M parameters, showing a 12x – 24x reduction in model size compared to prior work (MindEye1/2).</li>
      </ul>
      <p><a href="https://github.com/kushagrayadv/voxel-former" target="_blank" rel="noopener noreferrer">View Project</a></p>
  </div>
  <img src="/assets/projects/brain-decoding.jpg" alt="p2p" class="project-card-img" />
</div>

<div class="project-card">
  <div class="project-card-content">
    <h3>Subdomain-Savvy RAG: Enabling ROS2 Developers with Navigation Support</h3>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python"><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch"><img src="https://img.shields.io/badge/LangChain-121212?style=flat&logo=chainlink&logoColor=white" alt="LangChain"><img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black" alt="HuggingFace"><img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white" alt="MongoDB"><img src="https://img.shields.io/badge/Qdrant-FF4F64.svg?style=flat&logo=qdrant&logoColor=white" alt="Qdrant">
      <ul>
        <li>Developed an ROS2 robotics-specific RAG system, using PyTorch, involving data ingestion and engineering, LLMs fine-tuning, and prompt engineering to deliver a high-performing agent navigation solution.</li>
        <li>Created an ETL pipeline using ClearML to ingest media sources and store data in MongoDB, implemented featurization with vector DB Qdrant, and fine-tuned LLaMA-3.2-3B model using LoRA, achieving 81.67% accuracy and 68% style score</li>
        <li>Designed query expansion and cross-encoder-based inference using LangChain and hugging face transformers</li>
        <li>Deployed a Gradio-based application with Huggingface Hub and Ollama integration for code generation instructions</li>
      </ul>
      <p><a href="https://github.com/kushagrayadv/ai-rag-system" target="_blank" rel="noopener noreferrer">View Project</a></p>
  </div>
  <img src="/assets/projects/p2p.png" alt="p2p" class="project-card-img" />
</div>

<div class="project-card">
  <div class="project-card-content">
    <h3>PRobot: Context-Aware PR Automation Agent</h3>
    <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL">
    <img src="https://img.shields.io/badge/aiohttp-2C5F77?style=flat&logo=aiohttp&logoColor=white" alt="aiohttp">
    <img src="https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white" alt="Slack">
    <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white" alt="GitHub Actions">
    <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white" alt="Pydantic">
    <img src="https://img.shields.io/badge/MCP-000000?style=flat&logo=modelcontextprotocol&logoColor=white" alt="MCP">
    
    <ul>
      <li>Developed an MCP (Model Context Protocol) server that bridges GitHub Actions, Git repositories, and Slack to automate PR workflows, enabling AI assistants like Claude to analyze code changes and manage CI/CD pipelines</li>
      <li>Created a comprehensive tool suite including automated PR analysis, template suggestion based on code changes, CI/CD status monitoring, and Slack notification formatting with markdown support</li>
      <li>Designed a modular architecture with FastMCP exposing 6+ tools and 6+ prompt templates, enabling seamless integration with AI assistants for context-aware PR management and deployment summaries</li>
    </ul>
    
    <p><a href="https://github.com/kushagrayadv/probot" target="_blank" rel="noopener noreferrer">View Project</a></p>
  </div>
  <img src="/assets/projects/probot.png" alt="PRobot" class="project-card-img" />
</div>