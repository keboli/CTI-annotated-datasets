# CTI-ANN: A Self-Training-Based Annotation Framework with Tailored Augmentation for Cyber Threat Intelligence Posts

This repository contains two datasets curated for the paper **"CTI-ANN: A Self-Training-Based Annotation Framework with Tailored Augmentation for Cyber Threat Intelligence Posts."**  
All datasets contain LLM-generated **summarized versions of X posts** in compliance with X’s privacy policies. These summaries are designed to preserve the original semantics without redistributing any raw content. They are approximate and serve only to convey the general meaning of the posts for academic and research purposes. The original post contents can be retrieved using the provided post IDs via the X API.

## Included Files
- `X-sample-dataset-with-summaries.csv`: Manually cross-annotated X-Annotated Dataset
- `X-full-dataset-with-summaries.csv`: Automatically annotated X-CTI-ANN Dataset generated via self-training
- `unlabeled_data_ids.csv`: X-CTI-Entire Dataset used to generate the X-CTI-ANN Dataset (shared for reproducibility purposes)

## Description
Each dataset contains post IDs from the social media platform **X** and their corresponding labels. Labels are:
- `CTI-Positive`: Post is related to cyber threat intelligence (CTI)
- `CTI-Negative`: Post is not related to CTI

Please note that only post IDs and labels are provided, in compliance with platform policies.

