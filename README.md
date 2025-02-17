# AMP-LoRAgen: Generation of species-aware antimicrobial peptides using GPT and Low-Rank Adaptation

## Abstract
Antimicrobial peptides (AMPs) have emerged as promising alternatives to traditional antibiotics due to their broad-spectrum activity and low propensity for inducing resistance. However, the discovery and design of potent, species-aware AMPs remain challenging due to limited availability of training data. Recent advances in natural language processing, particularly the development of parameter-efficient fine-tuning on Generative Pre-trained Transformer (GPT) models, have shown promise in generating biologically relevant sequences. In this study, we present a protein language modeling approach for generating potent, species-aware AMP sequences using a GPT model enhanced with parameter-efficient fine-tuning. Building upon a pre-trained GPT model trained on 44.88 million peptide sequences to capture general peptide characteristics, we implemented Low-Rank Adaptation (LoRA) fine-tuning using curated species-specific AMP sequences to generate AMPs tailored to specific microbial species. The performance of the LoRA fine-tuned GPT model was evaluated using physicochemical property analysis, AMP activity, and hemolytic activity predictions. Our results demonstrate that the parameter-efficient LoRA method significantly improves the model's ability to generate potent AMP sequences, outperforming other deep learning-based AMP generation models. We further analyzed species-awareness of the generated AMP sequences through species-specific minimum inhibitory concentration (MIC) predictions and confirmed that the species-aware samples are more potent than the non species-aware samples. This study showcases the potential of leveraging parameter-efficient fine-tuning techniques in language models for the discovery and design of novel, species-specific antibiotics, advancing the development of targeted antimicrobial therapies.

## 

## Contact
Hansol Lee (hansol.lee@gist.ac.kr)

Hojung Nam* (hjnam@gist.ac.kr)

*Corresponding Author

