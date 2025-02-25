# CAMeL-2: Cultural Appropriateness Measure Set for LMs

This repository contains the Arabic-English parallel contexts and cultural entities of the CAMeL-2 dataset for measuring cultural biases in language models.

For more details, see the accompanying paper:\
["On The Origin of Cultural Biases in Language Models: From Pre-training Data to Linguistic Phenomena"](https://arxiv.org/pdf/2501.04662), **NAACL 2025**

## Entities

The folder ```entities``` contains the parallel Arabic-English entities for 7 different entity types, annotated for broad association with ```Arab``` or ```Western``` cultures.

## QA Contexts

The folder ```qa-contexts``` provides long contexts with implicit reference to the [MASK] which supports evaluation on extractive QA.

All QA contexts are parallel (provided in Arabic and English versions).

## Culturally-Contextualized Contexts

The folder ```camelco-contexts``` provides two culturally-contextualized contexts from the previous CAMeL benchmark, where only Arab entities are appropriate [MASK] fillings

We provide two versions of the contexts:
- a version for ```masked-lms``` where the [MASK] is placed anywhere in the context
- a version for ```causal-lms``` where we rewrite sentences for the cultural context to appear behind the [MASK]

The masked-lms contexts are annotated for sentiment (positive, negative, neutral) to support fairness evaluation on sentiment analysis.

All culturally-grounded contexts are parallel (provided in Arabic and English versions).

## Citation
```
@article{naous2025origin,
  title={On The Origin of Cultural Biases in Language Models: From Pre-training Data to Linguistic Phenomena},
  author={Naous, Tarek and Xu, Wei},
  journal={arXiv preprint arXiv:2501.04662},
  year={2025}
}
```

## Contact
**Tarek Naous**: [Scholar](https://scholar.google.com/citations?user=ImyLv44AAAAJ&hl=en) | [Github](https://github.com/tareknaous?tab=repositories) |
[Linkedin](https://www.linkedin.com/in/tareknaous/) |  [Research Gate](https://www.researchgate.net/profile/Tarek_Naous?ev=hdr_xprf) | [Personal Wesbite](https://tareknaous.github.io/)
| tareknaous@gatech.edu


