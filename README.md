from pathlib import Path
content = r'''<h1 align="center">Hi 👋, I'm Garima Chaubey</h1>

<h3 align="center">PhD Research Scholar | Continual Learning | Reinforcement Learning | Foundation Models</h3>

<p align="center">
  I am a PhD Research Scholar at the Indian Institute of Information Technology Allahabad (IIIT Allahabad), India.
  My research focuses on building adaptive and efficient learning systems that can acquire new knowledge while
  retaining previously learned information.
</p>

<p align="center">
  <a href="https://garimachaubey.github.io/Garima_Chaubey/">
    <img src="https://img.shields.io/badge/Website-Visit-2F80ED?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"/>
  </a>
  <a href="https://scholar.google.com/citations?user=V1QXFP0AAAAJ&hl=en">
    <img src="https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"/>
  </a>
  <a href="https://orcid.org/0009-0009-4141-8685">
    <img src="https://img.shields.io/badge/ORCID-Profile-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"/>
  </a>
  <a href="https://www.linkedin.com/in/garima3107">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/GarimaChaubey">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=GarimaChaubey&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views"/>
</p>

## 🔬 Research Interests

- Continual Learning and lifelong adaptation
- Reinforcement Learning and adaptive decision-making
- Foundation Models and parameter-efficient fine-tuning
- Large Language Models and agentic AI
- Multi-Agent Reinforcement Learning
- Machine Unlearning and trustworthy AI
- Representation Learning

I am particularly interested in how learning systems and AI agents can adapt to evolving tasks, learn from experience, and retain useful knowledge over time.

## 🧪 Current Research

**ReinforceTree: PPO-Guided Adaptive LoRA Routing for Continual Learning**

My current research explores reinforcement-learning-guided adaptive selection of LoRA adapters for continual learning. The broader goal is to improve model adaptation across evolving tasks while mitigating catastrophic forgetting.

*Status: Submitted to IEEE Transactions on Artificial Intelligence; under review.*

## 📚 Publications

1. **K. Lohani, G. Chaubey, et al.**, “A Study of Fairness and Bias of Deep Learning Models,” *2025 IEEE International Conference on Computer Vision and Machine Intelligence (CVMI)*, 2025. [DOI](https://doi.org/10.1109/CVMI66673.2025.11337368)

2. **G. Chaubey, K. P. Singh, and M. Ojha**, “ReinforceTree: PPO-Guided Adaptive LoRA Routing for Continual Learning,” submitted to *IEEE Transactions on Artificial Intelligence* (under review).

## 🛠️ Technical Skills

**Programming:** Python, C, C++, Java, SQL

**Deep Learning & ML Frameworks:** PyTorch, TensorFlow, Keras, Scikit-learn

**Scientific Computing & Data Analysis:** NumPy, Pandas, OpenCV

**AI & Research Areas:** Continual Learning, Reinforcement Learning, Representation Learning, Bayesian Modeling, LLMs, Vision Transformers (ViTs), Vision-Language Models (VLMs)

**Tools & Platforms:** Linux, Git, Docker, Kubernetes, Jupyter Notebook, Google Colab, VS Code, LaTeX

**Cloud Platforms:** Google Cloud Platform (GCP), AWS, Microsoft Azure

## 🎓 Education

- **Ph.D. in Information Technology**, Indian Institute of Information Technology Allahabad, India — Jan 2025–Present
- **M.Sc. in Computational Science and Applications**, Banaras Hindu University — 2022–2024
- **B.Sc. in Computer Science and Mathematics**, Mahatma Gandhi Kashi Vidyapith — 2019–2022

## 👩‍🏫 Teaching & Academic Service

**Teaching Assistant**
- Advanced Programming and Practices (APP), IIIT Allahabad
- Design and Analysis of Algorithms (DAA), IIIT Allahabad
- Programming and Data Structures with Python, IIT Patna
- Introduction to Machine Learning, IIIT Allahabad
- Natural Language Processing, IIT Patna

**Academic Service**
- Reviewer: NeurIPS 2026 Workshops (WiML and NewInML), IEEE CVMI 2026, AIKP 2026
- Program Committee Member: ICAIMS 2026
- Former Vice Chair, ACM Student Chapter, Banaras Hindu University

## 🏆 Awards & Achievements

- **UGC NET Junior Research Fellowship (JRF):** Qualified in Computer Science and Applications, June 2024; 97.44 percentile.
- **NPTEL Elite Certification in Data Mining:** 90%, among the top 5% of learners.
- **MeitY–NASSCOM AI–Data Scientist Training Programme:** Six-month programme, NSQF Level 8.

## 📫 Get in Touch

- **Email:** [rsi2025001@iiita.ac.in](mailto:rsi2025001@iiita.ac.in)
- **Website:** [garimachaubey.github.io/Garima_Chaubey](https://garimachaubey.github.io/Garima_Chaubey/)
- **Google Scholar:** [View profile](https://scholar.google.com/citations?user=V1QXFP0AAAAJ&hl=en)
- **LinkedIn:** [garima3107](https://www.linkedin.com/in/garima3107)
- **ORCID:** [0009-0009-4141-8685](https://orcid.org/0009-0009-4141-8685)

---

<p align="center">
  <i>Interested in research collaborations and discussions on continual learning, reinforcement learning, foundation models, and adaptive AI agents.</i>
</p>
'''
path = Path("/mnt/data/README.md")
path.write_text(content, encoding="utf-8")
print(f"Created: {path} ({path.stat().st_size} bytes)")
