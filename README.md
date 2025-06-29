# BioWE-LLM Project Report

### Demo Video

[Watch here](https://drive.google.com/file/d/1yhcl69R1aFlywOX3ZYm5EnBUBbmfAke-/view)

## Motivation

Our project aims to improve question-answering tasks in healthcare by developing a language model fine-tuned on biomedical literature. We want to create an accessible model that improves diagnostic precision, treatment recommendations, and patient care.

## Related Work

We were inspired by the BioGPT paper from Microsoft (September 2024), which showed the potential of pre-training on biomedical texts to improve QA performance. We built BioWE-LLM by combining BioBERT and BioELECTRA models.

## Architecture and Workflow

We use PubMedQA as the dataset, focusing on the labeled subset (PQA-L). BioBERT and BioELECTRA are combined using weighted ensemble methods. Diagrams illustrating the workflow, model architectures, and ensemble approach can be found in the figures section of the report.

## Advantages of Weighted Ensemble Methods

Weighted ensemble methods improve accuracy, robustness, generalization, and model interpretability by combining multiple models and leveraging their strengths.

## Dataset

We used the PQA-L subset of PubMedQA, which contains yes/no/maybe answers. Statistics on question length, context length, and answer length are provided in the report tables.

## Metrics and Evaluation

We measured accuracy as the primary metric. BioWE-LLM achieved an average accuracy of 79.8%, outperforming PubMedBERT, BioELECTRA, and BioGPT baselines.

## Experimental Analysis

Our analysis includes results across average and challenging scenarios. While average cases are handled well by our model, challenging cases require further training on unlabeled data for deeper contextual understanding.

## Contributions

* Improved performance in biomedical QA tasks
* Domain-specific understanding using ensemble methods
* Flexibility to incorporate future models
* Robustness and better generalization

## Figures and Tables

Detailed figures and tables are available in the original document, showing architecture diagrams, training and validation curves, and comparative results.

For any questions, feel free to reach out.
