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

Hi! I'm Siwei Han(韩偲蔚), a first-year Ph.D. student at <a href="https://cs.unc.edu/">Department of Computer Science</a>, <a href="https://www.unc.edu/">UNC-Chapel Hill</a>, advised by Prof. <a href="https://www.huaxiuyao.io">Huaxiu Yao</a>. Before that, I received my Bachelor of Science degree at Fudan University. I am interested in LLM/VLM Alignment and Multimodal Multiagent System, aiming to build more reliable and functional models and agents.

<p style="border: 1px solid #ff4d4f; background-color: #fff2f0; color: #ff4d4f; padding: 8px; border-radius: 5px;">
I’m open to 2026 summer internships, feel free to reach out!
</p>

---

# 🔥 News

_**2025.09** Three paper are accepted by NIPS 2025, including one spotlight!_

_**2025.09** One paper is accepted by EMNLP 2025 as an Oral!_

_**2025.03** We present MDocAgent: A Multi-Modal Multi-Agent Framework for Document Understanding! The paper is available on [arXiv](https://arxiv.org/abs/2503.13964)._

_**2025.02** MMIE is selected to be presented as an Oral!_

_**2025.01** MMIE is accepted by ICLR 2025!_

---

# 📝 Selected Publications
<a href="https://scholar.google.com/citations?user=oT1QQs8AAAAJ">Full Publications</a>

†: Equal contribution 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='https://github.com/user-attachments/assets/e4481250-1858-4970-93ac-51a3e50096f8' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
We present the Alignment Tipping Process (ATP), a critical post-deployment risk unique to self-evolving LLM agents. Unlike training-time failures, ATP arises when continual interaction drives agents to abandon alignment constraints established during training in favor of reinforced, self-interested strategies. We formalize and analyze ATP through two complementary paradigms: Self-Interested Exploration, where repeated high-reward deviations induce individual behavioral drift, and Imitative Strategy Diffusion, where deviant behaviors spread across multi-agent systems. Building on these paradigms, we construct controllable testbeds and benchmark Qwen3-8B and Llama-3.1-8B-Instruct. Our experiments demonstrate that alignment of LLM agents is not a static property but a fragile and dynamic one, vulnerable to feedback-driven decay during deployment. Our data and code are available at <a href="https://github.com/aiming-lab/ATP">github</a>.
</div>
  
<div markdown="1">
[Alignment Tipping Process: How Self-Evolution Pushes LLM Agents Off the Rails](https://arxiv.org/abs/2510.04860)<br>
<strong>Siwei Han</strong>, Jiaqi Liu, Yaofeng Su, Wenbo Duan, Xinyuan Liu, Cihang Xie, Mohit Bansal, Mingyu Ding, Linjun Zhang, Huaxiu Yao
</div>
</div>

<img width="1950" height="1064" alt="CleanShot 2025-10-07 at 12 11 12@2x" src="https://github.com/user-attachments/assets/e4481250-1858-4970-93ac-51a3e50096f8" />

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='https://github.com/user-attachments/assets/b5879006-dfb6-4086-95ab-fa5e4d4ce97f' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
We present MDocAgent (A Multi-Modal Multi-Agent Framework for Document Understanding), a novel RAG and multi-agent framework that leverages both text and image to solve DocQA problems. Our system employs five specialized agents: a general agent, a critical agent, a text agent, an image agent and a summarizing agent. These agents engage in multi-modal context retrieval, combining their individual insights to achieve a more comprehensive understanding of the document's content. This collaborative approach enables the system to synthesize information from both textual and visual components, leading to improved accuracy in question answering. Our data and code are available at [github](https://github.com/aiming-lab/MDocAgent).
</div>
  
<div markdown="1">
[MDocAgent: A Multi-Modal Multi-Agent Framework for Document Understanding](https://arxiv.org/abs/2503.13964)<br>
**Siwei Han**, Peng Xia, Ruiyi Zhang, Tong Sun, Yun Li, Hongtu Zhu, Huaxiu Yao<span style="opacity: 0;">placeholderplaceholderplaceholder</span>
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025 Main (Oral)</div><img src='https://github.com/user-attachments/assets/d1259661-64f4-47f5-858d-98cee0b7b1f8' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
In this paper, we introduce GLIMPSE, a benchmark designed to evaluate whether large vision-language models (LVLMs) can truly think with videos rather than rely on static frames. Unlike prior video benchmarks that resemble image-based tasks, GLIMPSE emphasizes holistic temporal reasoning through 3,269 videos and 4,342 human-crafted questions across 11 categories. Each question requires full-context understanding of the entire video. While humans achieve 94.82% accuracy, the best LVLM, GPT-o3, reaches only 66.43%, revealing significant gaps in genuine video reasoning.
</div>

<div markdown="1">
[GLIMPSE: Do Large Vision-Language Models Truly Think With Videos or Just Glimpse at Them?](https://arxiv.org/abs/2507.09491)<br>
Yiyang Zhou†, Linjie Li†, Shi Qiu†, Zhengyuan Yang, Yuyang Zhao, **Siwei Han**, Yangfan He, Kangqi Li, Haonian Ji, Zihao Zhao, Haibo Tong, Lijuan Wang, Huaxiu Yao
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NIPS 2025 Spotlight</div><img src='https://github.com/user-attachments/assets/e948404d-81e1-4ba6-8547-7ceebbe30d7a' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
In this paper, we introduce MJ-BENCH-VIDEO, a large-scale video preference benchmark designed to evaluate video generation across five critical aspects: Alignment, Safety, Fineness, Coherence & Consistency, and Bias & Fairness. This benchmark incorporates 28 fine-grained criteria to provide a comprehensive evaluation of video preference. Building upon this dataset, we propose MJ-VIDEO, a Mixture-of-Experts (MoE)-based video reward model designed to deliver fine-grained reward. MJ-VIDEO can dynamically select relevant experts to accurately judge the preference based on the input text-video pair. This architecture enables more precise and adaptable preference judgments.
</div>

<div markdown="1">
[MJ-VIDEO: Fine-Grained Benchmarking and Rewarding Video Preferences in Video Generation](https://arxiv.org/abs/2502.01719)<br>
Haibo Tong†, Zhaoyang Wang†, Zhaorun Chen, Haonian Ji, Shi Qiu, **Siwei Han**, Zhongkai Xue, Yiyang Zhou, Peng Xia, Kexin Geng, Mingyu Ding, Rafael Rafailov, Chelsea Finn, Huaxiu Yao
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

# 📖 Educations

<img src="../images/fdu.png" alt="fdu" style="zoom:20%; float: left" />&emsp; [Fudan University](https://www.fudan.edu.cn/en/)    
&emsp; Undergraduate student in Computer Science and Technology. *2021.09 - 2025.06*

<img src="../images/unc.png" alt="unc" style="zoom:24%; float: left" />&emsp; [University of North Carolina at Chapel Hill](https://www.unc.edu/)    
&emsp; Exchange student. *2023.08 - 2023.12*
<br><br>

---

# 💻 Internships

<img src="../images/atc.png" alt="atc" style="zoom:60%; float: left" />&emsp; [Advantest, China](https://www.advantest.com/)    
&emsp; R&D Associate Engineer. *2024.01 - 2024.05*

<img src="../images/unc.png" alt="unc" style="zoom:24%; float: left" />&emsp; [University of North Carolina at Chapel Hill](https://www.unc.edu/)    
&emsp; Research Intern(remote). *2024.01 - 2025.02*
<br><br>

---

# 🏆 Selected Honors & Awards
- NeurIPS Spotlight Presentation (Top 5%), 2025
- EMNLP Oral Presentation, 2025 (Top 2%), 2025
- KDD 2025 Health Day Distinguished Vision Award, 2025
- ICLR Oral Presentation (Top 1.8%), 2025

---

# 💼 Academic Services
- Workshop Co-Organizer: <a href="https://r2-fm.github.io/">ICML 2025 Workshop on Reliable and Responsible Foundation Models</a>

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
  <img src="https://github.com/user-attachments/assets/0753edf7-98b4-4e0d-8c0f-8c8c24bb5aa9" style="display: inline-block;margin: 10px;width: 45%;">

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
