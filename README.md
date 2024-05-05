# Assessing the Generational Capabilities of Retrieval Augmented Systems using Fine-Tuned Embedding Model

## Authors:
- Dhiraj Pimparkar (dkpimpar@iu.edu)
- Fahad Mehfooz (fmehfooz@iu.edu)
- Prantar Borah (pborah@iu.edu)
- Sarth Kulkarni (sakulk@iu.edu)

## Abstract:
Retrieval Augmented Generative (RAG) systems have emerged as pivotal tools in natural language processing, facilitating enhanced information retrieval and generation tasks. However, their effectiveness hinges on the ability to accurately retrieve relevant information, particularly when confronted with domain-specific documents. This challenge is exacerbated by the limited pre-training of embedding models on such domains. Previous research suggests that fine-tuning embedding models can ameliorate retrieval performance in RAG systems. Yet, scant attention has been paid to whether this enhancement extends to the generation phase. This study addresses this gap by leveraging fine-tuning techniques on embedding models and evaluating the resultant impact on the generative capabilities of RAG systems. Leveraging a diverse dataset, we conduct extensive experiments to assess the efficacy of the new RAG system in comparison to conventional RAG systems across various retrieval scenarios. Our findings shed light on the potential of fine-tuning embedding models to augment both retrieval and generation processes within RAG systems, thereby advancing their utility in real-world applications.

## Contents:
- This repository contains a Jupyter notebook (`experimentations.ipynb`) that conducts all the experimentations for the project.
- Datasets for retrieval evaluation:
  - Uber and Lyft's annual reports are included in the repository.
- Dataset for generation evaluation:
  - The Patronus AI Finance dataset is shared in a Google Drive folder. Access it using the following link: [Patronus AI Finance Dataset](https://drive.google.com/drive/folders/1-1RhBQzfagQlL9dO6qeCFJg3riodV8g1?usp=sharing).
