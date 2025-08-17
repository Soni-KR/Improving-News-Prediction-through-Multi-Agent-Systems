# Improving News Prediction through Multi-Agent Systems

This repository contains the code and experiments for our internship project on predicting country–disease links from Arabic health news using a multi-agent pipeline and Graph Convolutional Networks (GCNs).

---

## Abstract
Recent advances in graph neural networks (GNNs) and large language models (LLMs) provide promising opportunities for public health surveillance.  
In this project, we design a multi-agent pipeline that processes Arabic health news, extracts entities and relations, and trains a GCN model to predict country–disease links.  
Our system achieves **F1 = 0.98** and **AUC = 0.98**, significantly outperforming baseline methods.  

---

## Repository Structure
- `finalwork.ipynb` — Main notebook with preprocessing, multi-agent pipeline, and GCN experiments.
- `data/` — (not included in this repo) Raw and processed datasets used in training. 
            The Hana-MC dataset can be accessed via [link/doi].
- `results/` — (optional) Figures and metrics generated during experiments, shown in the report.


---

## Installation
Clone this repo and install dependencies:

```bash
git clone https://github.com/Soni-KR/Improving-News-Prediction-through-Multi-Agent-Systems.git
cd Improving-News-Prediction-through-Multi-Agent-Systems
pip install -r requirements.txt

