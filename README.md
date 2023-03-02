# 🩺 Awesome Language Model Evaluations

👋 Hi, there. This is a collection of papers for Language Model evaluations, especially for the closed-source ChatGPT.

📫 Suggestions, PRs and all contributions are welcome. 
We really appreciate the lovely people who help us build a friendly community. 
Many thanks to the organizations and companies that provide amazing tools, model weights and inspiring ideas~

## 🛡️ Badges

- Model: ![ChatGPT](https://img.shields.io/badge/ChatGPT-black)
- Machine Translation: ![Translation](https://img.shields.io/badge/MT-orange)
- Natural Language Generation: ![Generation](https://img.shields.io/badge/NLG-green)
- Natural Language Understanding: ![Natural Language Understanding](https://img.shields.io/badge/NLU-red)
- Information Extraction: ![Information Extraction](https://img.shields.io/badge/IE-blue)

## 🥅 Leaderboard

🚧 Under active development, please stay tuned ~

| Model   | Task             | Dataset | Setting   | Score Type | Score | Ref                                                   |
| :------ | :--------------- | :------ | :-------- | :--------- | ----: | :---------------------------------------------------- |
| ChatGPT | Event Extraction | ACE05   | zero-shot | F1         |  29.5 | ([Wei et al. 2023](https://arxiv.org/abs/2302.10205)) |

## 📑 Papers

[arXiv 2023] [**How Robust is GPT-3.5 to Predecessors? A Comprehensive Study on Language Understanding Tasks**](https://arxiv.org/abs/2303.00293)<br />
_Xuanting Chen, Junjie Ye, Can Zu, Nuo Xu, Rui Zheng, Minlong Peng, Jie Zhou, Tao Gui, Qi Zhang, Xuanjing Huang_<br />
![ChatGPT](https://img.shields.io/badge/ChatGPT-black) ![Natural Language Understanding](https://img.shields.io/badge/NLU-red)
> The GPT-3.5 models have demonstrated impressive performance in various Natural Language Processing (NLP) tasks, showcasing their strong understanding and reasoning capabilities. However, their robustness and abilities to handle various complexities of the open world have yet to be explored, which is especially crucial in assessing the stability of models and is a key aspect of trustworthy AI. In this study, we perform a comprehensive experimental analysis of GPT-3.5, exploring its robustness using 21 datasets (about 116K test samples) with 66 text transformations from TextFlint that cover 9 popular Natural Language Understanding (NLU) tasks. Our findings indicate that while GPT-3.5 outperforms existing fine-tuned models on some tasks, it still encounters significant robustness degradation, such as its average performance dropping by up to 35.74\% and 43.59\% in natural language inference and sentiment analysis tasks, respectively. We also show that GPT-3.5 faces some specific robustness challenges, including robustness instability, prompt sensitivity, and number sensitivity. These insights are valuable for understanding its limitations and guiding future research in addressing these challenges to enhance GPT-3.5's overall performance and generalization abilities.

[arXiv 2023] [**A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity**](https://arxiv.org/abs/2302.04023)<br />
_Yejin Bang, Samuel Cahyawijaya, Nayeon Lee, Wenliang Dai, Dan Su, Bryan Wilie, Holy Lovenia, Ziwei Ji, Tiezheng Yu, Willy Chung, Quyet V. Do, Yan Xu, Pascale Fung_<br />
![ChatGPT](https://img.shields.io/badge/ChatGPT-black) ![Natural Language Understanding](https://img.shields.io/badge/NLU-red) ![Generation](https://img.shields.io/badge/NLG-green) ![Translation](https://img.shields.io/badge/MT-orange)
> This paper proposes a framework for quantitatively evaluating interactive LLMs such as ChatGPT using publicly available data sets. We carry out an extensive technical evaluation of ChatGPT using 23 data sets covering 8 different common NLP application tasks. We evaluate the multitask, multilingual and multi-modal aspects of ChatGPT based on these data sets and a newly designed multimodal dataset. We find that ChatGPT outperforms LLMs with zero-shot learning on most tasks and even outperforms fine-tuned models on some tasks. We find that it is better at understanding non-Latin script languages than generating them. It is able to generate multimodal content from textual prompts, via an intermediate code generation step. Moreover, we find that ChatGPT is 63.41% accurate on average in 10 different reasoning categories under logical reasoning, non-textual reasoning, and commonsense reasoning, hence making it an unreliable reasoner. It is, for example, better at deductive than inductive reasoning. ChatGPT suffers from hallucination problems like other LLMs and it generates more extrinsic hallucinations from its parametric memory as it does not have access to an external knowledge base. Finally, the interactive feature of ChatGPT enables human collaboration with the underlying LLM to improve its performance, i.e, 8% ROUGE-1 on summarization and 2% ChrF++ on machine translation, in a multi-turn "prompt engineering" fashion. We also release codebase for evaluation set extraction.

[arXiv 2023] [**Zero-Shot Information Extraction via Chatting with ChatGPT**](https://arxiv.org/abs/2302.10205)<br />
_Xiang Wei, Xingyu Cui, Ning Cheng, Xiaobin Wang, Xin Zhang, Shen Huang, Pengjun Xie, Jinan Xu, Yufeng Chen, Meishan Zhang, Yong Jiang, Wenjuan Han_<br />
![ChatGPT](https://img.shields.io/badge/ChatGPT-black) ![Information Extraction](https://img.shields.io/badge/IE-blue)
> Zero-shot information extraction (IE) aims to build IE systems from the unannotated text. It is challenging due to involving little human intervention. Challenging but worthwhile, zero-shot IE reduces the time and effort that data labeling takes. Recent efforts on large language models (LLMs, e.g., GPT-3, ChatGPT) show promising performance on zero-shot settings, thus inspiring us to explore prompt-based methods. In this work, we ask whether strong IE models can be constructed by directly prompting LLMs. Specifically, we transform the zero-shot IE task into a multi-turn question-answering problem with a two-stage framework (ChatIE). With the power of ChatGPT, we extensively evaluate our framework on three IE tasks: entity-relation triple extract, named entity recognition, and event extraction. Empirical results on six datasets across two languages show that ChatIE achieves impressive performance and even surpasses some full-shot models on several datasets (e.g., NYT11-HRL). We believe that our work could shed light on building IE models with limited resources.

[arXiv 2023] [**Can ChatGPT Understand Too? A Comparative Study on ChatGPT and Fine-tuned BERT**](https://arxiv.org/abs/2302.10198)<br />
_Qihuang Zhong, Liang Ding, Juhua Liu, Bo Du, Dacheng Tao_<br />
![ChatGPT](https://img.shields.io/badge/ChatGPT-black) ![Information Extraction](https://img.shields.io/badge/IE-blue) ![Natural Language Understanding](https://img.shields.io/badge/NLU-red)
> Recently, ChatGPT has attracted great attention, as it can generate fluent and high-quality responses to human inquiries. Several prior studies have shown that ChatGPT attains remarkable generation ability compared with existing models. However, the quantitative analysis of ChatGPT's understanding ability has been given little attention. In this report, we explore the understanding ability of ChatGPT by evaluating it on the most popular GLUE benchmark, and comparing it with 4 representative fine-tuned BERT-style models. We find that: 1) ChatGPT falls short in handling paraphrase and similarity tasks; 2) ChatGPT outperforms all BERT models on inference tasks by a large margin; 3) ChatGPT achieves comparable performance compared with BERT on sentiment analysis and question answering tasks. Additionally, several bad cases from inference tasks show the potential limitation of ChatGPT.

[arXiv 2023] [**Is ChatGPT A Good Translator? A Preliminary Study**](https://arxiv.org/abs/2301.08745v2)<br />
_Wenxiang Jiao, Wenxuan Wang, Jen-tse Huang, Xing Wang, Zhaopeng Tu_<br />
![ChatGPT](https://img.shields.io/badge/ChatGPT-black) ![Translation](https://img.shields.io/badge/MT-orange)
> This report provides a preliminary evaluation of ChatGPT for machine translation, including translation prompt, multilingual translation, and translation robustness. We adopt the prompts advised by ChatGPT to trigger its translation ability and find that the candidate prompts generally work well and show minor performance differences. By evaluating on a number of benchmark test sets, we find that ChatGPT performs competitively with commercial translation products (e.g., Google Translate) on high-resource European languages but lags behind significantly on low-resource or distant languages. For distant languages, we explore an interesting strategy named pivot prompting that asks ChatGPT to translate the source sentence into a high-resource pivot language before into the target language, which improves the translation performance significantly. As for the translation robustness, ChatGPT does not perform as well as the commercial systems on biomedical abstracts or Reddit comments but is potentially a good translator for spoken language. Scripts and data: [this https URL](https://github.com/wxjiao/Is-ChatGPT-A-Good-Translator)
