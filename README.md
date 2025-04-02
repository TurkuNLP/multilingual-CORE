# Multilingual CORE

This repository contains a collection of web-crawled documents annotated with a hierarchical register scheme based on the CORE taxonomy, originally developed for English by Biber and Egbert ([2018](https://doi.org/10.1017/9781316388228)) and Laippala et al. ([2022](https://link.springer.com/article/10.1007/s10579-022-09624-1)). This scheme has been applied to **16 languages**, with five large subcorpora (English, Finnish, French, Swedish, Turkish) and eleven smaller ones (Arabic, Catalan, Spanish, Persian, Hindi, Indonesian, Japanese, Norwegian, Portuguese, Urdu, Chinese).

The data in this repository was used to train our **multilingual register classifier**, available on [Hugging Face](https://huggingface.co/TurkuNLP/web-register-classification-multilingual).

## Usage

If you use this dataset in your research or projects, please cite the following paper (currently under review for publication):

```bibtex
@misc{henriksson2024automaticregisteridentificationopen,
      title={Automatic register identification for the open web using multilingual deep learning}, 
      author={Erik Henriksson and Amanda Myntti and Saara Hellström and Anni Eskelinen and Selcen Erten-Johansson and Veronika Laippala},
      year={2024},
      eprint={2406.19892},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2406.19892}, 
}
```

## Register Label Scheme

The register annotation scheme used in this corpus is hierarchical, with the following categories:

- **MT**: Machine translated or generated
- **LY**: Lyrical
- **SP**: Spoken
  - it: Interview
- **ID**: Interactive discussion
- **NA**: Narrative
  - ne: News report
  - sr: Sports report
  - nb: Narrative blog
- **HI**: How-to or instructions
  - re: Recipe
- **IN**: Informational description
  - en: Encyclopedia article
  - ra: Research article
  - dtp: Description of a thing or person
  - fi: Frequently asked questions
  - lt: Legal terms and conditions
- **OP**: Opinion
  - rv: Review
  - ob: Opinion blog
  - rs: Denominational religious blog or sermon
  - av: Advice
- **IP**: Informational persuasion
  - ds: Description with intent to sell
  - ed: News & opinion blog or editorial
