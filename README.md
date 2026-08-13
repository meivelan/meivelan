<div align="center">

# Meivelan Murugesan

<a href="https://readme-typing-svg.demolab.com">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1000&color=10B981&center=true&vCenter=true&width=560&lines=AI%2FML+Engineer+in+the+making;LLM+Evaluation+%C2%B7+Computer+Vision+%C2%B7+Deep+Learning;Fine-tuning+transformers+%26+building+ML+systems" alt="Typing SVG" />
</a>

<p>
  <a href="https://linkedin.com/in/meivelanmurugesan"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://kaggle.com/meivelan"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" /></a>
  <a href="https://portfolio-meivelan.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:jobs.meivelanmurugesan@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

</div>

---

### 👋 About

Final-year CS undergrad at **CIT Coimbatore** with production experience in **LLM evaluation**, **transformer fine-tuning**, and **end-to-end ML & Computer Vision systems**. I like working close to the metal — from evaluation frameworks that catch model hallucinations to change-detection pipelines on satellite imagery.

- 🔭 Currently an **SDE Intern @ ShopUp**, building evaluation pipelines for LLM-based invoice extraction agents
- 🎓 Wrapping up my **B.E. in Computer Science** (May 2026) · CGPA **7.79**
- 🌱 Deep into **Computer Vision, NLP, and LLM evaluation**
- 📫 Reach me at **jobs.meivelanmurugesan@gmail.com** · Tamil Nadu, India

---

### 💼 Experience

**Software Development Engineer Intern** — ShopUp &nbsp;·&nbsp; `Feb 2026 – Present`

- Designed and built an **evaluation framework** for AI-powered invoice extraction agents (Gemini 2.5 Flash, Claude), measuring field-level accuracy against human-annotated ground truth across Arabic & English ZATCA-compliant invoices.
- Uncovered **LLM hallucination patterns** — e.g. the Gemini OCR model fabricating Dutch VAT numbers from training knowledge.
- Implemented a **recursive comparison engine** handling nested JSON with date-format normalization (10+ formats), numeric tolerance for financial rounding, and fuzzy string matching for OCR variations.
- Cut evaluation cost with **module-scoped test fixtures** that run LLM inference once across 108 invoices and reuse outputs.
- Designed **pass@k** and **pass^k** metrics to measure non-deterministic LLM output consistency across inference runs.

<sub><b>Stack:</b> Python · pytest · Gemini API · Claude API · FastAPI · Pydantic</sub>

---

### 🚀 Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🛰️ SAR-to-EO Image Translation</h4>
      Paired image-to-image translation pipeline (Pix2Pix — U-Net generator + PatchGAN discriminator) on the Sentinel-1/2 terrain-agnostic dataset. A controlled ablation isolating discriminator receptive field (PatchGAN vs. PixelGAN) reduced <b>LPIPS by ~30%</b> and improved FID, SSIM, and PSNR.
      <br/><br/>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/torchvision-EE4C2C?logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/Pix2Pix-10B981" />
    </td>
    <td width="50%" valign="top">
      <h4>🌍 Binary Change Detection (EO-SAR)</h4>
      End-to-end change-detection pipeline on satellite image pairs. Engineered a cross-modal difference channel and addressed <b>1.57% class imbalance</b> via Dice + Focal loss, reaching <b>F1 = 0.355</b> with a U-Net / EfficientNet-B0 backbone.
      <br/><br/>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/segmentation--models--pytorch-10B981" /> <img src="https://img.shields.io/badge/Rasterio-3776AB" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🔬 Vision Transformer on CIFAR-10</h4>
      Fine-tuned a pretrained ViT (<code>vit_small/base_patch16_224</code> from timm) on CIFAR-10 to <b>98.64%</b> accuracy. Benchmarked the accuracy / training-time / model-size trade-off (21.7M params) on a Tesla T4 GPU.
      <br/><br/>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/timm-10B981" /> <img src="https://img.shields.io/badge/CIFAR--10-3776AB" />
    </td>
    <td width="50%" valign="top">
      <h4>📈 FinBERT Sentiment Analysis <sub>· Research</sub></h4>
      Fine-tuned FinBERT for 3-class sentiment on FiQA and Indian financial news; applied <b>SHAP</b> for token-level interpretability to surface the words driving predictions. Achieved <b>97.8% accuracy</b> and F1-score of 97.8.
      <br/><br/>
      <sub>Jan–Mar 2025 · under Prof. K. Priyadarsini, CIT Coimbatore</sub><br/><br/>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black" /> <img src="https://img.shields.io/badge/SHAP-10B981" />
    </td>
  </tr>
</table>

---

### 🏆 Achievements

- 🎯 **Top 9%** out of **22,000+ teams** — Amazon ML Challenge 2025 <sub>(XGBoost · CatBoost · BERT · Qwen)</sub>
- 🥈 **2nd Place** — Competitive Programming, Nexera, CIT (2026)

---

### 🛠️ Skills

**Languages** &nbsp;
<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white" />

**ML / DL** &nbsp;
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white" />
<img src="https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white" />
<img src="https://img.shields.io/badge/RasterIO-3776AB" />

**Domains** &nbsp;
<img src="https://img.shields.io/badge/Computer%20Vision-10B981" />
<img src="https://img.shields.io/badge/NLP-10B981" />
<img src="https://img.shields.io/badge/Image%20Segmentation-10B981" />
<img src="https://img.shields.io/badge/Change%20Detection-10B981" />
<img src="https://img.shields.io/badge/LLM%20Evaluation-10B981" />

**Tools** &nbsp;
<img src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white" />

---

### 📊 Competitive Programming

| Platform | Rating / Rank |
|---|---|
| **Kaggle** | Highest competition rating **2403 / 12998** |
| **LeetCode** | Rating **1577** · **600+** problems solved |
| **CodeChef** | **3 star** |

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=meivelan&show_icons=true&hide_border=true&theme=dark&bg_color=09090b&title_color=10b981&icon_color=10b981&text_color=a1a1aa" height="165" alt="GitHub stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=meivelan&hide_border=true&background=09090b&stroke=10b981&ring=10b981&fire=10b981&currStreakLabel=10b981&sideLabels=a1a1aa&dates=a1a1aa&currStreakNum=a1a1aa&sideNums=a1a1aa" height="165" alt="GitHub streak" />

</div>
