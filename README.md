# Awesome Language Model Evaluations

A collection for Language Model evaluations, especially for closed-source ChatGPT.

## Badges

- Model: ![ChatGPT](https://img.shields.io/badge/ChatGPT-black)
- Machine Translation: ![Translation](https://img.shields.io/badge/MT-orange)
- Natural Language Generation: ![Generation](https://img.shields.io/badge/NLG-green)
- Natural Language Understanding: ![Natural Language Understanding](https://img.shields.io/badge/NLU-red)
- Information Extraction: ![Information Extraction](https://img.shields.io/badge/IE-blue)

## Leaderboard

|Dataset|Task|Model|Score Type|Score|
|:-|:-|:-|:-|-:|
||||||

## Papers

[arXiv 2023] [**How Robust is GPT-3.5 to Predecessors? A Comprehensive Study on Language Understanding Tasks**](https://arxiv.org/abs/2303.00293)<br />
_Xuanting Chen, Junjie Ye, Can Zu, Nuo Xu, Rui Zheng, Minlong Peng, Jie Zhou, Tao Gui, Qi Zhang, Xuanjing Huang_<br />
![ChatGPT](https://img.shields.io/badge/ChatGPT-black)
> The GPT-3.5 models have demonstrated impressive performance in various Natural Language Processing (NLP) tasks, showcasing their strong understanding and reasoning capabilities. However, their robustness and abilities to handle various complexities of the open world have yet to be explored, which is especially crucial in assessing the stability of models and is a key aspect of trustworthy AI. In this study, we perform a comprehensive experimental analysis of GPT-3.5, exploring its robustness using 21 datasets (about 116K test samples) with 66 text transformations from TextFlint that cover 9 popular Natural Language Understanding (NLU) tasks. Our findings indicate that while GPT-3.5 outperforms existing fine-tuned models on some tasks, it still encounters significant robustness degradation, such as its average performance dropping by up to 35.74\% and 43.59\% in natural language inference and sentiment analysis tasks, respectively. We also show that GPT-3.5 faces some specific robustness challenges, including robustness instability, prompt sensitivity, and number sensitivity. These insights are valuable for understanding its limitations and guiding future research in addressing these challenges to enhance GPT-3.5's overall performance and generalization abilities.

[arXiv 2023] [**A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity**](https://arxiv.org/abs/2302.04023)<br />
_Yejin Bang, Samuel Cahyawijaya, Nayeon Lee, Wenliang Dai, Dan Su, Bryan Wilie, Holy Lovenia, Ziwei Ji, Tiezheng Yu, Willy Chung, Quyet V. Do, Yan Xu, Pascale Fung_<br />
![ChatGPT](https://img.shields.io/badge/ChatGPT-black)
> This paper proposes a framework for quantitatively evaluating interactive LLMs such as ChatGPT using publicly available data sets. We carry out an extensive technical evaluation of ChatGPT using 23 data sets covering 8 different common NLP application tasks. We evaluate the multitask, multilingual and multi-modal aspects of ChatGPT based on these data sets and a newly designed multimodal dataset. We find that ChatGPT outperforms LLMs with zero-shot learning on most tasks and even outperforms fine-tuned models on some tasks. We find that it is better at understanding non-Latin script languages than generating them. It is able to generate multimodal content from textual prompts, via an intermediate code generation step. Moreover, we find that ChatGPT is 63.41% accurate on average in 10 different reasoning categories under logical reasoning, non-textual reasoning, and commonsense reasoning, hence making it an unreliable reasoner. It is, for example, better at deductive than inductive reasoning. ChatGPT suffers from hallucination problems like other LLMs and it generates more extrinsic hallucinations from its parametric memory as it does not have access to an external knowledge base. Finally, the interactive feature of ChatGPT enables human collaboration with the underlying LLM to improve its performance, i.e, 8% ROUGE-1 on summarization and 2% ChrF++ on machine translation, in a multi-turn "prompt engineering" fashion. We also release codebase for evaluation set extraction.

[arXiv 2023] [**Is ChatGPT A Good Translator? A Preliminary Study**](https://arxiv.org/abs/2301.08745v2)<br />
_Wenxiang Jiao, Wenxuan Wang, Jen-tse Huang, Xing Wang, Zhaopeng Tu_<br />
![ChatGPT](https://img.shields.io/badge/ChatGPT-black)
> This report provides a preliminary evaluation of ChatGPT for machine translation, including translation prompt, multilingual translation, and translation robustness. We adopt the prompts advised by ChatGPT to trigger its translation ability and find that the candidate prompts generally work well and show minor performance differences. By evaluating on a number of benchmark test sets, we find that ChatGPT performs competitively with commercial translation products (e.g., Google Translate) on high-resource European languages but lags behind significantly on low-resource or distant languages. For distant languages, we explore an interesting strategy named pivot prompting that asks ChatGPT to translate the source sentence into a high-resource pivot language before into the target language, which improves the translation performance significantly. As for the translation robustness, ChatGPT does not perform as well as the commercial systems on biomedical abstracts or Reddit comments but is potentially a good translator for spoken language. Scripts and data: [this https URL](https://github.com/wxjiao/Is-ChatGPT-A-Good-Translator)
