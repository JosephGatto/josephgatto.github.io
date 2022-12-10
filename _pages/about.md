---
permalink: /
title: "Publications"
excerpt: "Ph.D. Student at Dartmouth College"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

1. [Scope of Pre-trained Language Models for Detecting Conflicting Health Information (2022)](https://arxiv.org/pdf/2209.11102.pdf)


*Abstract*: An increasing number of people now rely on online platforms to meet their health information needs. Thus identifying inconsistent or conflicting textual health information has become a safety-critical task. Health advice data poses a unique challenge where information that is accurate in the context of one diagnosis can be conflicting in the context of another. For example, people suffering from diabetes and hypertension often receive conflicting health advice on diet. This motivates the need for technologies which can provide contextualized, user-specific health advice. A crucial step towards contextualized advice is the ability to compare health advice statements and detect if and how they are conflicting. This is the task of health conflict detection (HCD). Given two pieces of health advice, the goal of HCD is to detect and categorize the type of conflict. It is a challenging task, as (i) automatically identifying and categorizing conflicts requires a deeper understanding of the semantics of the text, and (ii) the amount of available data is quite limited.

In this study, we are the first to explore HCD in the context of pre-trained language models. We find that DeBERTa-v3 performs best with a mean F1 score of 0.68 across all experiments. We additionally investigate the challenges posed by different conflict types and how synthetic data improves a model's understanding of conflict-specific semantics. Finally, we highlight the difficulty in collecting real health conflicts and propose a human-in-the-loop synthetic data augmentation approach to expand existing HCD datasets. Our HCD training dataset is over 2x bigger than the existing HCD dataset and is made publicly available on Github.
