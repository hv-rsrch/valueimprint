
# A Technique for Classifying Human Values in RLHF Datasets

This repository contains code and resources for auditing and classifying the human values embedded in RLHF datasets.

## Repository Structure

### Code/

- `human_values_model_anthropic_rlhf.ipynb`: Notebook for training and evaluating a RoBERTa model on human values classification.
- `classifying_human_values_other_datasets.ipynb`: Notebook for applying the trained model to classify human values in other datasets.
- `downloading_anthropic_hh_rlhf.ipynb`: Notebook for downloading and preprocessing the Anthropic HH-RLHF dataset.

### Dataset/

- `valueimprint__gt.csv`: Annotated dataset for training the human values classifier.
- `valueimprint_anthropic_hhrlhf_chosen.csv`: Results of human values classification on chosen responses.
- `valueimprint_anthropic_hhrlhf_rejected.csv`: Results of human values classification on rejected responses.
- `valueimprint_openaiwebgpt.csv`: Results of human values classification on the OpenAI WebGPT Comparisons dataset.
- `valueimprint__alpacagpt4.csv`: Results of human values classification on the Alpaca GPT-4-LLM dataset.

## Human Values Taxonomy

We developed a hierarchical taxonomy of human values based on various ethical frameworks:

- Well-being/Peace
- Information Seeking
- Justice/Human Rights & Animal Rights
- Duty/Accountability
- Wisdom/Knowledge
- Civility/Tolerance
- Empathy/Helpfulness

For a detailed breakdown of these categories, please refer to the `Human_Values_Taxonomy.md` file.

## Getting Started

1. Clone this repository.
2. Run the Jupyter notebooks in the `Code/` directory in the order listed above.

## Contributing

Contributions to improve the analysis or extend it to other datasets are welcome. Please contact the authors for further questions.

## Cite our paper

Use this link to cite our paper here.

## License

This work is licensed under a CC BY 4.0 license
