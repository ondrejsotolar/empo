# [EmPO: Theory-Driven Dataset Construction for Empathetic Response Generation through Preference Optimization]

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![DOI](https://img.shields.io/badge/DOI-10.xxxx/zenodo.xxxxxxx-blue)](https://doi.org/10.xxxx/zenodo.xxxxxxx)

## Abstract
Empathetic response generation is a desirable aspect of conversational agents, crucial for facilitating engaging and emotionally intelligent multi-turn conversations between humans and machines. Leveraging large language models for this task has shown promising results, yet challenges persist in ensuring both the empathetic quality of the responses and retention of the generalization performance of the models. In this paper, we propose a novel approach where we construct theory-driven preference datasets and use them to align LLMs with preference optimization algorithms to address these challenges. To measure empathetic response generation, we employ the EmpatheticDialogues dataset, assessing empathy with the diff-EPITOME and BERTscore metrics, and evaluate the generalization performance on the MMLU benchmark. We make all datasets, source code, and models publicly available.

## Authors

- **[Ondrej Sotolar]

## Installation

To replicate our results or use our code, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/xsotolar/empo
    ```
2. Navigate to the project directory:
    ```sh
    cd repo-name
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
TODO

### Example
TODO

```sh
python run_experiment.py --config config.json
