# The Grammar of Transformers:

This repository contains the database and analysis code accompanying our paper:

**"The Grammar of Transformers: A Systematic Review of Interpretability Research on Syntactic Knowledge in Language Models"**  
*Authors: Nora Graichen and Iria de-Dios-Flores and Gemma Boleda*  
Accepted at EMNLP 2026
[https://arxiv.org/abs/2601.19926]

## Overview

This repository provides the database underlying our systematic review of research on syntactic knowledge in Transformer-based language models (TLMs). For a detailed description of the systematic review methodology, annotation scheme, analyses, and findings, please refer to our paper.


## Repository structure

```
project-name/
├── README.md              # Project overview
├── data/                  # Input data/database
├── notebooks/             # Jupyter notebooks for demo/analysis code
└── LICENSE
```

## Extended version: *main_findings*

Apart from the ```data/database_final.csv```, we also upload ```data/database_findings.csv```, which includes an additional variable, *main_findings*. This column contains an AI-generated summary that provides an overview, in prose, of the main insights into syntactic competence and processing, as well as any model comparisons in the study. We specifically chose to prompt for paragraph-style summaries for this field, to maintain compact, integrated information, rather than fragmented notes. Because the use of AI-generated summaries remains contentious, this variable has been omitted in the final version; however, we share this extension to facilitate further exploration of the database and support researchers who may find these integrated summaries useful.

## Citation

If you use our database, please cite our paper, published as a main conference paper at EMNLP 2026:
```
@misc{graichen:etal:2026,
      title={The Grammar of Transformers: A Systematic Review of Interpretability Research on Syntactic Knowledge in Language Models}, 
      author={Nora Graichen and Iria de-Dios-Flores and Gemma Boleda},
      year={2026},
      eprint={2601.19926},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2601.19926}, 
}
```
## License

This project is licensed under the MIT License.
