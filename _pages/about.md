---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# **Welcome to my homepage!**

I am currently an **AI Infrastructure / Training Systems Engineer** at **[AutoCoder.cc](https://www.autocoder.cc/)**

My work focuses on **large-scale LLM training systems**, where I optimize system efficiency and hardware utilization through **Model FLOPs Utilization (MFU) improvement**, **communication–computation overlap**, **operator / kernel fusion**, and **runtime-level scheduling and memory optimization**. I work closely with distributed training stacks to improve scalability, throughput, and cost-efficiency of foundation model training.

Previously, I was a **Senior Researcher at [Huawei Cloud Architecture Innovation Lab (Cloud Lab)](https://www.huaweicloud.com/lab/cloud/home.html)**, working in Fellow- and Academician-led research environments on **MoE inference**, **memory offloading**, and **cloud-scale AI infrastructure**. I also conducted research at the **[Guangming Laboratory](https://www.gml.ac.cn/kytd/189.html)** (Intelligent Recommendation & Resource Scheduling Group).

My research and engineering interests include:
- Large-scale LLM training systems and AI infrastructure
- Model FLOPs Utilization (MFU) optimization and system efficiency
- Communication–computation overlap and operator / kernel fusion
- Distributed training systems and memory-efficient execution
- Scalable inference systems for large models (LLMs, MoE)

# 🔥 News
<span id="news"></span>
<div style="height: 200px; overflow-y: auto; border: 1px solid #ddd; padding: 10px; border-radius: 5px; background-color: #f9f9f9;">
<ul style="margin:0; padding-left:20px; list-style-type:disc;">
  <li><strong>2026.01</strong>: 🎉 Paper <strong>EcoThink</strong> accepted to <strong>WWW 2026</strong> (Acceptance Rate: 21.7%)</li>
  <li><strong>2025.12</strong>: 🚀 Joined <strong>AutoCoder.cc</strong> as LLM Algorithm Engineer</li>
  <li><strong>2025.07</strong>: 🎉 Ranked <strong>14 / 5200+</strong> in Huawei ICT Software Competition — Top 3 in Huawei Cloud, 1st in Chengdu Research Institute (20+ product lines)</li>
  <li><strong>2025.03</strong>: 🚀 Led MoE memory offloading system with <strong>&lt;3%</strong> operator overhead</li>
  <li><strong>2024.09</strong>: 🏆 Received <strong>Golden Cloud Award</strong> & <strong>HCS Cloud Summit Star</strong></li>
  <li><strong>2023.08</strong>: 📈 FRCP capacity forecasting system deployed at large scale</li>
</ul>
</div>

# 📄 Publications & Patents
<span id="publications"></span>

> *\* denotes corresponding author. \*\* denotes equal contribution.*

### Conference Papers

<span id="ecothink"></span>
<u><b>EcoThink: A Green Adaptive Inference Framework for Sustainable and Accessible Agents</b></u>
Linxiao Li\*, Zhixiang Lu\*
*TheWebConference 2026 (WWW'26)* ✅ **Accepted**

- Proposes an energy-aware adaptive inference framework for LLM-based agents
- Introduces a lightweight distillation-based router to skip unnecessary reasoning
- Achieves **40.4% average energy reduction** (up to **81.9%**) with no statistically significant performance loss
- Aligns with **UN SDG 13 (Climate Action)** and **SDG 10 (Reduced Inequalities)**

### Patents
<span id="moe-patent"></span>
- <u><b>Inference Optimization Method for MoE Models</b></u>, Invention Patent (High-potential)

### Technical Systems & Engineering Artifacts
- Large-scale MoE inference system with expert memory offloading
- Energy-aware adaptive inference framework for LLM agents
- Distributed QoS modeling and capacity forecasting platform

# 💻 Experience
<span id="experience"></span>

### AutoCoder.cc
**LLM Algorithm Engineer (AI Infrastructure / Training Systems)**
*2025.12 – Present*

- Focus on **LLM training infrastructure** and system-level optimization
- Improve **MFU (Model FLOPs Utilization)** through:
  - Communication–computation overlap
  - Operator fusion and kernel-level optimization
  - Pipeline scheduling and memory efficiency techniques
- Work on scalable, high-performance distributed training systems for large models

---

### Huawei Technologies Co., Ltd.
**Senior Researcher / Algorithm Engineer (Huawei Cloud Lab, Fellow-led Team)**
*2022.04 – 2025.12, Chengdu, China*

- Level-4 Algorithm Expert (Role Certification)
- Worked under **[Huawei Cloud CTO & Academician Gu Jingjing](https://developer.huawei.com/consumer/cn/forum/topic/0202743458671690687)**
- Member of **[Huawei Cloud Architecture Innovation Lab (Cloud Lab)](https://www.huaweicloud.com/lab/cloud/home.html)**

**Research & Engineering Focus:**
- Flexible General Computing & Flexible Intelligent Computing
- Large-scale MoE inference, memory offloading, and distributed systems
- Cloud-native AI infrastructure spanning "Cloud + Network + X"

**Key Contributions:**
- Designed and implemented **MoE inference memory offloading** via Ascend operator interception
- Achieved **<3% runtime overhead**, **TTFT <3s**, **TPOP <100ms**
- Supported **BF16 / W8A8 / W4A8** quantization and logical memory extension via DDR
- Led system architecture design with ~90% core code contribution

---

### Flexible Computing – Capacity Forecasting & QoS Modeling
**Architect / Developer**
*2023.08 – 2025.12*

- Built FRCP capacity forecasting system based on **iTransformer**
- Designed a **QoS MoE large model** with contrastive pretraining (ts2vec)
- End-to-end ownership: data aggregation, cleaning, modeling, training, inference, deployment
- Systems deployed at scale within Huawei Cloud production environments

---

### Pulsar-based Distributed Messaging System
**Architect / Core Developer**

- Replaced native BookKeeper with customized storage engine
- Ensured low latency, high concurrency, and high reliability
- **0 P3 incidents** over 6+ months in production

# 🎖 Honors and Awards
<span id="honors"></span>
- *2025* **Huawei ICT Software Competition**: Ranked 14 / 5200+ overall, Top 3 in Huawei Cloud, 1st in Chengdu Research Institute; awarded at AT Conference by institute leadership
- *2024* **Huawei "Tomorrow Star" Award**
- *2024* **Golden Cloud Award**
- *2024* **HCS Cloud Summit Star**
- *2022* **Huawei "Tomorrow Star" Award**
- **Huawei Trusted Professional Certification**

# 📖 Educations
<span id="education"></span>

**The University of Sydney**
Bachelor of Advanced Computing (Honours), Computer Science
*2017.09 – 2021.12*
GPA: 89 / 100 | First Class Honours
Supervisor: **[Prof. Wei (Wilson) Li](https://www.sydney.edu.au/engineering/about/our-people/academic-staff/weiwilson-li.html)**

- Full Scholarship PhD Offer, The University of Sydney
- GRE: 334 (Q170, V164, AW 5.5)

---

**University of California, Los Angeles (UCLA)**
Exchange Program, Computer Science
*2018.03 – 2019.03*
GPA: 3.8 / 4.0

---

**Shanghai Jiao Tong University**
Summer School, Computer Science
*2019.11 – 2020.02*
GPA: 4.0 / 4.0

---

**Fudan University**
Summer School, Computer Science
*2020.12 – 2021.03*
GPA: 4.0 / 4.0

<hr class="horizontal-line">
<div style="width: 30%; margin: 0 auto;">
  <p style="text-align: center; color: grey; font-size: small;">
    © Leo (Linxiao) Li | Last updated: Jan 2026
  </p>
</div>
