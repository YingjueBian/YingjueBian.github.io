---
permalink: /
title: "Hi, this is Yingjue Bian, a BME student"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Bio
===

I'm a second-year master's student from the [BME Department](https://www.cmu.edu/bme/), [Carnegie Mellon University](https://www.cmu.edu/), currently in the CMU BME Research Program.
I am very fortunate to be advised by [Prof. Tai-Sing Lee](https://www.cnbc.cmu.edu/~tai/) from the [School of Computer Science](https://www.cs.cmu.edu/) and the [Neuroscience Institute](https://www.cmu.edu/ni/) at Carnegie Mellon University. During my undergraduate studies, I had the privilege of being mentored by [Prof. Mohamad Sawan](https://en.westlake.edu.cn/faculty/mohamad-sawan.html), Chair Professor at [Westlake University](https://en.westlake.edu.cn/), and by Prof. [Sheng Ge](https://bme.seu.edu.cn/2017/0919/c463a198545/page.htm) from the School of Biomedical Engineering, Southeast University.


**Research Summary:** 
My research explores neural and AI representations, aiming to bridge biological and artificial models of perception and cognition. I use digital-twin models of macaque V4 to explore visual representation, develop multimodal neural decoding with EEG, fNIRS, and wearable sensors, and investigate large-scale pretraining for speech and language. Ultimately, I seek to align and integrate representations across brain and machine, enabling them to inform and advance one another.

**Interests:** 
Computational Neuroscience · Neural Interfaces · NeuroAI · Brain-Inspired AI · Representation Learning · Multimodal

**I am actively seeking PhD opportunities from 2026!**

## Research Experience

### Neural Coding of Macaque V4 via Digital‑Twin Modeling  
*Research Assistant, [School of Computer Science](https://www.cs.cmu.edu/) & [Neuroscience Institute](https://www.cmu.edu/ni/), [Carnegie Mellon University](https://www.cmu.edu) — Prof. [Tai‑Sing Lee](https://www.cs.cmu.edu/~tai)*  
*Pittsburgh, USA · Sep 2024 – Present*

- Integrated a deep-learning V4 digital twin with natural-scene and shape–texture batteries; proposed **Unit Preference Index** and Dispersity to quantify selectivity; observed **dispersion–tuning correlation**.
- Designed 3D–2D object stimuli in Blender; identified neuron subtypes with modality-specific selectivity; indices (Dispersion, Shape–Texture) showed **consistent negative correlations** with preference.  
- Used VLMs (Qwen-2.5-VL) to caption maximally driving stimuli, linking semantic descriptors to neural tuning profiles..

### Hands Motor Imagery via Action Observation: An EEG‑fNIRS Study  
*Visiting Student, [CenBRAIN](https://cenbrain.westlake.edu.cn/index.htm), [Westlake University](https://www.westlake.edu.cn/) — Prof. [Mohamad Sawan](https://cenbrain.westlake.edu.cn/info/1052/1152.htm)*  
*Hangzhou, China · Jun 2023 – Nov 2023*

- Proposed a brain-computer interface protocol including motor execution, motor imagery, picture-guided motor imagery, and video-guided motor imagery tasks and collected EEG & fNIRS data from 42 volunteers.
- Conducted time-frequency analysis of EEG data, applying advanced signal processing techniques to investigate neural activity across different frequency bands.
- Applied statistical parametric mapping to analyze fNIRS data with NIRSlab, investigating brain activity and extracting meaningful neural correlates.

### Diagnosis of Early‑Stage Parkinson’s Disease via Inertial Sensors  
*Team Lead, Medical Imaging & AI Lab, Southeast University — Dr. Ping Zhou*  
*Nanjing, China · Jan 2022 – Apr 2022*

- Developed an LSTM‑FCN classifier with Model‑Agnostic Meta‑Learning (MAML), boosting diagnostic accuracy from 75% to 80%.  
- Collected and augmented gait data from 110 participants; performed denoising, axis calibration, period segmentation, and zero‑padding alignment.
- Built baseline 1‑D CNN and LSTM models and executed few‑shot transfer learning to ensure robustness on limited clinical samples.

---

## Projects

### [On going] Large-Scale Multilingual S2ST Corpus Construction and Benchmarking
*Jul 2025 - Present*
- **Developed a 100K+ hour multilingual S2ST corpus** from YouTube auto-dubbed multi-track videos, incorporating domain-aware sampling, audio alignment, and quality filtering to address temporal asynchrony and ensure high-quality parallel speech pairs.
- **Implemented and evaluated a transformer-based end-to-end S2ST baseline** ，using the open-source StreamSpeech (ACL’24) framework, benchmarking offline and simultaneous translation with BLEU, TER, and MCD metrics.

### [On going] Exploring Unsupervised Pretraining Paradigms for Speech Representation Learning
*Jul 2025 - Present*
- **Contrastive and Masked Modeling at Scale** Investigated self-supervised objectives including contrastive learning (e.g., CLIP/BLIP-inspired audio-text alignment) and masked autoencoding (AudioMAE), analyzing their scaling behavior, invariance properties, and downstream transferability.
- **Autoregressive Pretraining vs. Causal Decoding** Compared autoregressive pretraining approaches (Apple AIM series) with non-causal masked autoencoders, evaluating the potential of causal decoding for temporally coherent speech modeling and its trade-offs against bidirectional masked objectives.

### End-to-End Large Language Model Training and Alignment System
*Jul 2025 - Aug 2025*
- Built an end-to-end language model training and alignment pipeline from scratch, including a custom byte-level BPE tokenizer, Transformer implementation, and AdamW-based training loop; pre-trained and fine-tuned a LLaMA-style model on TinyStories and OpenWebText.
- Developed a scalable data processing pipeline for Common Crawl, incorporating deduplication, filtering, and contamination detection, producing a high-quality training corpus with unified loading and splitting workflows.
- Applied supervised fine-tuning and RLHF (PPO/DPO) for mathematical reasoning and instruction-following tasks, optimizing KV cache and batching strategies to reduce inference latency and memory usage; achieved stable PPL convergence and significant task performance gains over unaligned baselines.

### Robust Joint‑Moment Estimation via IMU  
*Wearable Human Technology, Carnegie Mellon University*  
*Pittsburgh, USA · Feb 2025 – May 2025*

- Implemented a Late Fusion framework (per-sensor LSTM encoders + MLP) with stochastic modality dropout, preserving baseline accuracy when one or two sensors failed.
- Designed a two-stage **Self-Supervised Transformer**: pre-training on AMASS + MoVi, followed by fine-tuning.
- Ran leave-one-subject-out and transfer-learning analyses; showed that fine-tuning on data from **three** subjects suffices for generalization and identified the pelvis IMU as the most informative channel.

### Brain Age Prediction from Structural MRI  
*SEU Student Research Training Program (SRTP)*  
*Nanjing, China · Dec 2022 – Nov 2023*

- Harmonised multi‑site T1‑weighted MRI data (OASIS, ADNI, UK Biobank) and built a full preprocessing pipeline (resampling, skull‑strip, N4, affine MNI).  
- Fine‑tuned a pre‑trained 3‑D CNN with age‑aware smooth‑L1 loss, reducing MAE versus scratch training.

### Eye‑Tracking Virtual Keyboard BCI  
*SEU Student Research Training Program (SRTP)*  
*Nanjing, China · Jan 2021 – Jan 2022*

- Devised a queue‑based DBSCAN variant to cluster streaming gaze points with < 5 ms latency.  
- Fused centroid trajectories via a Kalman filter, enabling dwell‑based keystroke selection with 90 % character accuracy across 12 users.

## Honors & Awards

- Biomedical Engineering Department Head’s Fellowship, Department of Biomedical Engineering, Carnegie Mellon University (\$5,000).
- Academic Excellence Fellowship, Department of Biomedical Engineering, Carnegie Mellon University (\$5,000).
- BME Research Excellence Award, Department of Biomedical Engineering, Carnegie Mellon University (\$6,000).




<!--A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.-->
