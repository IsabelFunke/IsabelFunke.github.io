---
layout: homepage
---

## About Me

I am a computer vision researcher working on surgical video analysis. During my PhD, I developed deep learning-based methods to enable automatic analysis and interpretation of minimally-invasive surgical videos, with applications in the operating room and in simulation-based surgical training. 

## News

- **[Jan 2026]** We released the [LASANA](https://huggingface.co/datasets/nct-tso/lasana) video dataset for Laparoscopic Skill Analysis and Assessment.
- **[Jan 2026]** I successfully defended my PhD!
- **[Dez 2025]** I became member of the editorial board of the [International Journal of Computer Assisted Radiology and Surgery](https://link.springer.com/journal/11548).
- **[Nov 2025]** Hanna talked about the AIxSuture project at the [journal club](https://research.bidmc.org/surgical-informatics/blog) of the Surgical Informatics Lab, Harvard Medical School. 
- **[Sep 2025]** Success at the MICCAI [Trauma THOMPSON Challenge](https://t3challenge25.grand-challenge.org/): Our team ranked 1st place in Task 1 (Action recognition and anticipation) and Task 4 (Realism assessment).
- **[Sep 2025]** I was awarded the [MICCAI](https://conferences.miccai.org/2025/en/) Outstanding Reviewer Award.
- **[Jul 2025]** I have submitted my doctoral thesis at TU Dresden. Thank you to my supervisor Prof. Stefanie Speidel!
- **[Jun 2025]** IEEE TBME selected the TUNeS paper as featured article.
- **[Jul 2024]** I gave a lecture on surgical phase recognition at the [Surgical Data Science Summer School](https://www.edu4sds.org/archives-2024/).
- **[May 2023]** I identified a bug in the popular [MatLab evaluation code](https://github.com/YuemingJin/TMRNet/tree/main/code/eval/result) used for surgical phase recognition. Details in our [paper](https://arxiv.org/abs/2305.13961)! 
- **[Jun 2021]** I was awarded the [IPCAI](https://ipcai2021.github.io/) Distinguished Reviewer Award.
- **[Oct 2020]** I was recognized as reviewer at [MICCAI](https://miccai2020.org/en/) (honorable mention).
- **[Oct 2018]** I was awarded the Best Oral Presentation Award (Joint First Place) at the MICCAI Workshop on Context-Aware Operating Theaters (OR 2.0).

## Research Highlights

### Surgical Skill Analysis
- Development of a deep learning approach to automatically assess surgical training videos and recognize task-specific errors. 
- Collaborative effort together with the University Hospital Carl Gustav Carus Dresden to create a large-scale dataset of video recordings of laparoscopic training tasks ([LASANA](https://huggingface.co/datasets/nct-tso/lasana)), crucial for building and validating automatic methods for surgical skill analysis. 
- Collaboration with the University Hospital RWTH Aachen to validate the skill assessment method on an open suturing task, using the [AIxSuture](https://zenodo.org/records/7940583) dataset.
- Implementation of automatic, real-time, video-based skill analysis in a minimalistic training box setup for laparoscopic surgery. For the peg transfer task, the software counts the number of dropped pins, estimates the number of successfully transferred pins, and rates the task execution on a scale from 0 to 100. See the demo video of an example run below! 

{% include_relative _includes/boxtrainer.html %}

#### Publications

{% include_relative _includes/publications.md %}

### Surgical Workflow Analysis (temporal video segmentation)

To recognize fine-grained gestures/actions and high-level phases in surgical videos, I investigated deep learning-based approaches focusing on
- modeling global temporal information by integrating attention mechanisms, and
- improving the modeling of local visual information by training in a self-supervised manner, training with extended temporal context, or moving from frame-wise analysis (image models) to clip-wise analysis (video models).

I also pointed out differences in evaluation protocols and how they may hinder the fair comparison of methods for surgical phase recognition.

#### Publications

{% include_relative _includes/publications_2.md %}
