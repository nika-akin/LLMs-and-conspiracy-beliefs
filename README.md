
## Conspiracy Narratives on Voat: A Longitudinal Analysis of Cognitive Activation and Evolutionary Psychology Features

This repository contains an annotated Voat.co dataset and a script for prompting GPT-3.5-turbo related to establishing minimal sufficienct features for conspiracy narratives from evolutionary psychology.
Binary features for each posting/comment are:

`Secrecy`
`Pattern`
`Action`
`Actor`
`Threat`

The corresponding text spans are:
`Secrecy_span`
`Pattern_span`
`Action_span`
`Actor_span`
`Threat_span`

Further, `overall_ct` was annotated to to assess the conspiracy status irrespective of the five features.

### Dataset

The dataset is based on Voat.co a deplatformed online platform that resembles in structur Reddit and was known to host deplatformed Sub-Reddits (Mekacher & Papasavva, 2022). The dataset (_N_ = 3,384) is a  span-level multi-label conspiracy dataset [voat_annotation.csv]. It consists of postings and comments between 2014-06-20 and 2020-12-23 that each have been annotated on a text span level for the presence of five minimal sufficient evolutionary psychology features. The present subset builds on a dataset that has been originally collected by: 

Mekacher, A., & Papasavva, A. (2022, May). " I Can’t Keep It Up." A Dataset from the Defunct Voat. co News Aggregator. In _Proceedings of the International AAAI Conference on Web and Social Media_ (Vol. 16, pp. 1302-1311). https://doi.org/10.5281/zenodo.5841668

Different subverses have been sampled for this dataset, namely:

- `/v/anon`, `/v/Conspiracy`, `/v/GreatAwakening`, `/v/pizzagate`, `/v/theredpill` ( each _n_ = 1,880)
- `/v/gaming`, `/v/news`, `/v/Science`, `/v/Showerthoughts` (each _n_ = 1,504)


You can find the dataset file in the `data/` directory.

### Prompting Script

The `prompting_script.txt` file in this repository provides a script for generating prompts for GPT-3 and the underlying annotation logic to discern the five features from each other.



<!--[Language of conspiracy (LOCO) corpus](https://pubmed.ncbi.nlm.nih.gov/34697754/)-->

<!--Miani, A., Hills, T., & Bangerter, A. (2021). LOCO: The 88-million-word language of conspiracy corpus. *Behavior research methods*, 1-24.-->

<!--## Resources -- Prompting LLMs
<!-- - Götz, F. M., Maertens, R., Loomba, S., & van der Linden, S. (2023). Let the algorithm speak: How to use neural networks for automatic item generation in psychological scale development. *Psychological Methods*. Advance online publication. [osf](https://psyarxiv.com/m6s28/)
<!-- - Horton, J. J. (2023). Large Language Models as Simulated Economic Agents: What Can We Learn from Homo Silicus?. arXiv preprint arXiv:2301.07543.
<!-- - Jakesch, M., Hancock, J. T., & Naaman, M. (2023). Human heuristics for AI-generated language are flawed. Proceedings of the National Academy of Sciences, *120*(11), e2208839120. [https://doi.org/10.1073/pnas.2208839120](https://osf.io/284yv/)
<!-- - Levy, S., Saxon, M., & Wang, W. Y. (2021). Investigating memorization of conspiracy theories in text generation. arXiv preprint [arXiv:2101.00379.](https://arxiv.org/abs/2101.00379)
<!-- - Li, X., Li, Y., Liu, L., Bing, L., & Joty, S. (2022). Is GPT-3 a Psychopath? Evaluating Large Language Models from a Psychological Perspective. arXiv preprint [arXiv:2212.10529](https://arxiv.org/pdf/2212.10529.pdf).
<!-- - Liu, P., Yuan, W., Fu, J., Jiang, Z., Hayashi, H., & Neubig, G. (2023). Pre-train, prompt, and predict: A systematic survey of prompting methods in natural language processing. *ACM Computing Surveys*, *55*(9), 1-35. [preprint arXiv:2302.03735](https://arxiv.org/pdf/2107.13586.pdf)
<!-- - Madaan, A., Tandon, N., Gupta, P., Hallinan, S., Gao, L., Wiegreffe, S., ... & Clark, P. (2023). Self-refine: Iterative refinement with self-feedback. arXiv preprint [arXiv:2303.17651.](https://selfrefine.info/)
<!--- Peng, B., Li, C., He, P., Galley, M., & Gao, J. (2023). Instruction Tuning with GPT-4 (arXiv:2304.03277). arXiv. [http://arxiv.org/abs/2304.03277](https://arxiv.org/abs/2304.03277)
<!-- - Zhou, Y., Muresanu, A. I., Han, Z., Paster, K., Pitis, S., Chan, H., & Ba, J. (2023). Large Language Models Are Human-Level Prompt Engineers (arXiv:2211.01910). arXiv. [https://doi.org/10.48550/arXiv.2211.01910](https://arxiv.org/abs/2211.01910)
## Resources -- NLP
<!--- Introduction to [Transformer-based Language Models](https://github.com/chkla/Transformers-MZES)-->
<!--- General [computational social science resources](https://github.com/gesiscss/css_methods_python)-->
<!--- [Media Research tool collection](https://docs.google.com/spreadsheets/d/1GHh7rw1XQqla9xvXg9hTNm67TGmeOXTu_Og_thIO8QI/edit#gid=1084385301)-->
<!--- Tools by [SciencesPo Medialab](https://medialab.sciencespo.fr/en/tools/)-->

