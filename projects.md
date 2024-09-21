---
layout: page
permalink: /projects/index.html
title: Projects
---
### Edge Multi-Modal Large Model (Ongoing Project)
We are developing a large model that supports multimodal information input and can be deployed at the edge (e.g., in vehicles). Our design will be based on a Mixture of Experts (MoE) architecture, initially completing model design, training, and quantization on GPUs, followed by FGGA circuit design for deployment on FPGA. This project has just begun—stay tuned!

### How Chain-of-Thought Works? (Finished)
This project focuses on LLMs Reasoning Analysis, exploring the mechanisms of Chain-of-Thought(CoT) reasoning. Previous research primarily examined text-level differences and their impact on outputs. This study analyzes model behavior during CoT responses from three perspectives: <strong>decoding</strong>, <strong>activation</strong>, and <strong>projection</strong>. Notably, we found that during the decoding phase, the model effectively mimics and understands CoT prompts, demonstrating increased confidence and specificity in its responses. Compared to standard prompts, CoT prompts activate a broader range of knowledge acquired during pre-training.<br>

### RDBVis: Automated Visualization of Table Data in Relational Databases (Finished)

In real-world scenarios, most data is stored in relational databases. To visualize this data, it is first necessary to generate a structured query statements based on the user’s visualization requirements(NL2SQL), and then proceed with the subsequent visualization operations. This study breaks down the task of automatic visualization of tabular data in relational databases into three main steps:  generating SQL, determining the chart type, and mapping data to visual
channels. We utilize the Chain-of-Thought(CoT) technique of generative large language models to address the task of automatic visualization of tabular data. Finally, we evaluated our approach on the nvBench dataset, and the results show that CoT-based automatic visualization of tabular data performs well.<br>
<img src="{{ site.url }}/images/workflow.jpg" class="bio-photo" width="500" height="200">
