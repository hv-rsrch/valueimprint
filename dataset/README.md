# Human Values in RLHF Datasets

## Overview

This dataset contains annotations and classifications of human values in the Anthropic HH RLHF dataset.

## Files

### `human_values_annotation_groundtruth.csv`

- Contains manually annotated data used for training the human values classifier.
- **Columns**: `Text`, `Label`

### `chosen_human_values_roberta.csv`

- Contains classifications of human values in chosen responses from the Anthropic HH-RLHF dataset.
- **Columns**: `Text`, `Prediction`

### `rejected_human_values_roberta.csv`

- Contains classifications of human values in rejected responses from the Anthropic HH-RLHF dataset.
- **Columns**: `Text`, `Prediction`

## Data Description

### `human_values_annotation_groundtruth.csv`

- **Text**: Contains preference text annotated for human values.
- **Label**: The human value category assigned to each text sample.

### `chosen_human_values_roberta.csv` and `rejected_human_values_roberta.csv`

- **Text**: Contains the preference text from the Anthropic HH-RLHF dataset (either chosen or rejected responses).
- **Prediction**: The human value category predicted by the RoBERTa-based classifier.

## Human Values Taxonomy

The labels in these datasets correspond to the following human values categories:

- Well-being/Peace
- Information Seeking
- Justice/Human Rights & Animal Rights
- Duty/Accountability
- Wisdom/Knowledge
- Civility/Tolerance
- Empathy/Helpfulness

For a detailed description of each category, please refer to the Human Values Taxonomy document in this repository.

## Data Collection

- The groundtruth dataset was manually annotated based on the developed human values taxonomy.
- The Anthropic HH-RLHF dataset was obtained from the Hugging Face datasets library and processed using the trained classifier.

## Usage

This dataset can be used for:

- Analyzing the distribution of human values in RLHF datasets
- Training and evaluating models for human values classification
- Studying the relationship between chosen/rejected responses and human values in AI training data

## Limitations

- The classifications in the chosen and rejected datasets are predictions and may contain errors.
- The human values taxonomy, while comprehensive, may not capture all possible human values.

## Ethical Considerations

When using this dataset, please consider:

- The potential biases in the original RLHF dataset and in the annotation process.
- The implications of categorizing human expressions into discrete value categories.
- The responsible use of these insights in AI development and research.

## Citation

If you use this dataset in your research, please cite: [Insert our citation information]

## Contact

For questions or additional information about this dataset, please contact the authors.

## License

This work is licensed under a CC BY 4.0 license

