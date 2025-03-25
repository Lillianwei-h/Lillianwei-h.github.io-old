---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

Hi! I'm Siwei Han(韩偲蔚), a senior at Fudan University, majoring in Computer Science and Technology. I am interested in alignment and application of LLMs, VLMs and multimodal models, currently interning in [Prof. Huaxiu Yao](https://www.huaxiuyao.io)'s team at UNC.

---

# 🔥 News

_**2025.01** MMIE is accepted by ICLR 2025!_

_**2025.02** MMIE is selected to be presented as an Oral!_

_**2025.03** We present MDocAgent: A Multi-Modal Multi-Agent Framework for Document Understanding! The paper is available on [arXiv](https://arxiv.org/abs/2503.13964)._

---

# 📝 Publications 
†: Equal contribution

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='https://github.com/user-attachments/assets/b5879006-dfb6-4086-95ab-fa5e4d4ce97f' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
We present MDocAgent (A Multi-Modal Multi-Agent Framework for Document Understanding), a novel RAG and multi-agent framework that leverages both text and image to solve DocQA problems. Our system employs five specialized agents: a general agent, a critical agent, a text agent, an image agent and a summarizing agent. These agents engage in multi-modal context retrieval, combining their individual insights to achieve a more comprehensive understanding of the document's content. This collaborative approach enables the system to synthesize information from both textual and visual components, leading to improved accuracy in question answering. Our data and code are available at [github](https://github.com/aiming-lab/MDocAgent).
</div>
  
<div markdown="1">
[MDocAgent: A Multi-Modal Multi-Agent Framework for Document Understanding](https://arxiv.org/abs/2503.13964)<br>
**Siwei Han**, Peng Xia, Ruiyi Zhang, Tong Sun, Yun Li, Hongtu Zhu, Huaxiu Yao
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025 Oral</div><img src='https://github.com/user-attachments/assets/07cfaa1e-f99b-47e7-846d-65337948d517' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
In this paper, we introduce MMIE, a robust, knowledge-intensive benchmark to evaluate interleaved multimodal comprehension and generation in LVLMs. With 20K+ examples covering 12 fields and 102 subfields, including mathematics, coding, physics, literature, health, and arts. It supports both interleaved inputs and outputs, offering a mix of multiple-choice and open-ended question formats to evaluate diverse competencies. Moreover, we propose a reliable automated evaluation metric, leveraging a scoring model fine-tuned with human-annotated data and systematic evaluation criteria, aimed at reducing bias and improving evaluation accuracy. We publicly release our benchmark and code on [MMIE](https://mmie-bench.github.io).
</div>
  
<div markdown="1">
[MMIE: Massive Multimodal Interleaved Comprehension Benchmark for Large Vision-Language Models](https://arxiv.org/abs/2410.10139)<br>
Peng Xia†, **Siwei Han†**, Shi Qiu†, Yiyang Zhou, Zhaoyang Wang, Wenhao Zheng, Zhaorun Chen, Chenhang Cui, Mingyu Ding, Linjie Li, Lijuan Wang, Huaxiu Yao
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/CompToT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
In this paper, we propose a novel comparison-based CoT generation algorithm that directly identifies the most promising thoughts with the noisy feedback from the LLM. In each round, we randomly pair intermediate thoughts and directly prompt the LLM to select the more promising one from each pair, allowing us to identify the most promising thoughts through an iterative process. To further model the noise in the comparison, we resort to the techniques of ensemble and dueling bandits and propose two variants of the proposed algorithm.
</div>

<div markdown="1">
[Generating Chain-of-Thoughts with a Direct Pairwise-Comparison Approach to Searching for the Most Promising Intermediate Thought](https://arxiv.org/abs/2402.06918)<br>
Zhen-Yu Zhang, **Siwei Han**, Huaxiu Yao, Gang Niu, Masashi Sugiyama
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='https://github.com/user-attachments/assets/aec63668-5766-41f5-bb49-dfaf61f2dad2' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
In this paper, we introduce GRAPE: Generalizing Robot Policy via Preference Alignment. Specifically, GRAPE aligns VLAs on a trajectory level and implicitly models reward from both successful and failure trials to boost generalizability to diverse tasks. Moreover, GRAPE breaks down complex manipulation tasks to independent stages and automatically guides preference modeling through customized spatiotemporal constraints with keypoints proposed by a large vision-language model. We evaluate GRAPE across a diverse array of tasks in both real-world and simulated environments. Experimental results demonstrate that GRAPE enhances the performance of state-of-the-art VLA models.
</div>
  
<div markdown="1">
[GRAPE: Generalizing Robot Policy via Preference Alignment](https://arxiv.org/abs/2411.19309)<br>
Zijian Zhang†, Kaiyuan Zheng†, Zhaorun Chen†, Joel Jang, Yi Li, **Siwei Han**, Chaoqi Wang, Mingyu Ding, Dieter Fox, Huaxiu Yao
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='https://github.com/user-attachments/assets/e948404d-81e1-4ba6-8547-7ceebbe30d7a' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
In this paper, we introduce MJ-BENCH-VIDEO, a large-scale video preference benchmark designed to evaluate video generation across five critical aspects: Alignment, Safety, Fineness, Coherence & Consistency, and Bias & Fairness. This benchmark incorporates 28 fine-grained criteria to provide a comprehensive evaluation of video preference. Building upon this dataset, we propose MJ-VIDEO, a Mixture-of-Experts (MoE)-based video reward model designed to deliver fine-grained reward. MJ-VIDEO can dynamically select relevant experts to accurately judge the preference based on the input text-video pair. This architecture enables more precise and adaptable preference judgments.
</div>
  
<div markdown="1">
[MJ-VIDEO: Fine-Grained Benchmarking and Rewarding Video Preferences in Video Generation](https://arxiv.org/abs/2502.01719)<br>
Haibo Tong†, Zhaoyang Wang†, Zhaorun Chen, Haonian Ji, Shi Qiu, **Siwei Han**, Zhongkai Xue, Yiyang Zhou, Peng Xia, Kexin Geng, Mingyu Ding, Rafael Rafailov, Chelsea Finn, Huaxiu Yao
</div>
</div>

# 📖 Educations

<img src="../images/fdu.png" alt="fdu" style="zoom:20%; float: left" />&emsp; [Fudan University](https://www.fudan.edu.cn/en/)    
&emsp; Undergraduate student in Computer Science and Technology. *2021.09 - now* <span style="float: right;">**GPA: 3.5/4**</span>

<img src="../images/unc.png" alt="unc" style="zoom:24%; float: left" />&emsp; [University of North Carolina at Chapel Hill](https://www.unc.edu/)    
&emsp; Exchange student. *2023.08 - 2023.12* <span style="float: right;">**GPA: 3.9/4**</span>
<br><br>

---

# 💼 Internships

<img src="../images/atc.png" alt="atc" style="zoom:60%; float: left" />&emsp; [Advantest, China](https://www.advantest.com/)    
&emsp; R&D Associate Engineer. *2024.01 - 2024.05*

<img src="../images/unc.png" alt="unc" style="zoom:24%; float: left" />&emsp; [University of North Carolina at Chapel Hill](https://www.unc.edu/)    
&emsp; Research Intern(remote). *2024.01 - now*
<br><br>

---

# 💻 Projects
### [LLM Reviser](https://github.com/Lillianwei-h/weak_aligner) Mar. 2024 - Jun. 2024
Leverage a reviser model to enhance the quality of the response from the original LLM and further preference tuning the LLM with the LLM-generated responses as dispreferred answers and the revised answers as preferred answers.

<img src="../images/revisor.png" alt="revisor" style="zoom:20%;" />

### [THSH shell](https://github.com/Lillianwei-h/Comp-530/tree/lab1) Oct. 2023
This shell can run standard linux shell commands. It also supports creating new built-in commands. It
includes features like pipelines, input/output redirection, script input, and debugging.

### [LLMEVAL - Fudan University’s NLP Laboratory](http://www.llmeval.com/) Apr. 2023 - Jun. 2023
Designing questions and evaluation criteria for assessing large language models' capability of solving questions in Chinese. Mainly resiponsible for story generation and paragraph edition parts.
<br><br>

---

# 🗺️ Languages
- Chinese: Native
- English: TOEFL 110
- Japanese: Elementary
<br><br>

---

# 🌟 Interests
- 🎨 Drawing illustration and manga(some of my paintings⬇)
  
  <img src="https://github.com/user-attachments/assets/ae307f9b-2659-44a5-90f6-4015fda273d9" style="display: inline-block;margin: 10px;width: 25%;">
  <img src="https://github.com/user-attachments/assets/a6875d43-8573-4527-ac3b-f270291a7bd4" style="display: inline-block;margin: 10px;width: 25%;">
  <!-- <img src="https://github.com/user-attachments/assets/42eff4d0-3bbb-4844-b87e-2cfe3d0a9962" style="display: inline-block;margin: 10px;width: 45%;"> -->

- 🎹 Improvisational piano playing and piano recomposition
- 🎮 Games
  - Baldur's Gate 3
  - Divinity: Original Sin 2
  - The Legend of Zelda: Breath of the Wild
  - The Elder Scrolls V: Skyrim
  - ...
- 🎶 Musicals
  - The Phantom of the Opera
  - Elisabeth
  - Dracula
  - ...
- 🐈 Kitty!
  <br>
  <img src="https://github.com/user-attachments/assets/3e87b4f1-f8f7-44b0-aaf2-91eceb4ecce7" style="margin: 10px;width: 45%;border-radius: 20px;">

<br><br>

---

# 📊 Statistics
[![](https://github-readme-stats-git-master-lillianwei-hs-projects.vercel.app/api?username=lillianwei-h&show_icons=true&theme=swift&rank_icon=github)](https://github.com/lillianwei-h)

[![](https://github-readme-stats-git-master-lillianwei-hs-projects.vercel.app/api/top-langs/?username=lillianwei-h&layout=donut&langs_count=8&theme=swift)](https://github.com/lillianwei-h)

<div style="width: 400px;margin-left: 0;">
<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=080808&w=a&t=tt&d=4ZvHHwuoR_IRMQg5YfStYBXhWFO0W5lc6-yTkWpTzCs&co=f2f2f2&cmo=387da3&cmn=ff8a00&ct=000000'></script>
</div>
