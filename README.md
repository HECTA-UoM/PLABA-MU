# PLABA-MU: Plain Language Adaptation of Biomedical Abstract by Manchester United (MMU + UoM) Researchers

Read our pre-print: https://arxiv.org/abs/2309.13202 

#title 
Large Language Models and Control Mechanisms Improve Text Readability of Biomedical Abstracts



# Abstract
Biomedical literature often uses complex language and inaccessible professional terminologies. That is why simplification plays an important role in improving public health literacy. Applying Natural Language Processing (NLP) models to automate such tasks allows for quick and direct accessibility for lay readers. In this work, we investigate the ability of state-of-the-art large language models (LLMs) on the task of biomedical abstract simplification, using the publicly available dataset for plain language adaptation of biomedical abstracts (\textbf{PLABA}). The methods applied include domain fine-tuning and prompt-based learning (PBL) on: 1) Encoder-decoder models (T5, SciFive, and BART), 2) Decoder-only GPT models (GPT-3.5 and GPT-4) from OpenAI and BioGPT, and 3) Control-token mechanisms on BART-based models. We used a range of automatic evaluation metrics, including BLEU, ROUGE, SARI, and BERTscore, and also conducted human evaluations. BART-Large with Control Token (BART-L-w-CT) mechanisms reported the highest SARI score of 46.54 and T5-base reported the highest BERTscore 72.62. In human evaluation, BART-L-w-CTs achieved a better simplicity score over T5-Base (2.9 vs. 2.2), while T5-Base achieved a better meaning preservation score over BART-L-w-CTs (3.1 vs. 2.6). We also categorised the system outputs with examples, hoping this will shed some light for future research on this task. Our code, fine-tuned models, and data splits are available at \url{[this https URL](https://github.com/HECTA-UoM/PLABA-MU)}


# Citation 

@misc{li2023large,
      title={Large Language Models and Control Mechanisms Improve Text Readability of Biomedical Abstracts}, 
      author={Zihao Li and Samuel Belkadi and Nicolo Micheletti and Lifeng Han and Matthew Shardlow and Goran Nenadic},
      year={2023},
      eprint={2309.13202},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
