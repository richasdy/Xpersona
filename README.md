## XPersona: Evaluating Multilingual Personalized Chatbot
<img src="plot/pytorch-logo-dark.png" width="10%"> [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

<img align="right" src="plot/HKUST.jpg" width="12%">

This is the source code of the paper:

**XPersona: Evaluating Multilingual Personalized Chatbot**. [[PDF]](https://arxiv.org/pdf/2003.07568.pdf)

If you use any source codes or datasets included in this toolkit in your work, please cite the following paper. The bibtex is listed below:
<pre>
@article{lin2020xpersona,
  title={XPersona: Evaluating Multilingual Personalized Chatbot},
  author={Lin, Zhaojiang and Liu, Zihan and Winata, Genta Indra and Cahyawijaya, Samuel and Madotto, Andrea and Bang, Yejin and Ishii, Etsuko and Fung, Pascale},
  journal={arXiv preprint arXiv:2003.07568},
  year={2020}
}
</pre>

## Dataset
<p align="center">
<img src="plot/dataset.png" width="80%" />
</p>

XPersona dataset is an extension of the persona-chat [dataset](https://www.aclweb.org/anthology/P18-1205/).  Specifically, we extend the [ConvAI2](http://convai.io) to other six languages: Chinese, French, Indonesian, Italian, Korean, and Japanese.

## Baselines
<p align="center">
<img src="plot/baseline.png" width="80%" />
</p>
In this work, we provided multilingual and crosslingual trained baselines. See multilingual and crosslingual folder for more details.

## Acknowledgement
This repository is implemented base on [**Huggingface**](https://github.com/huggingface/transformers)