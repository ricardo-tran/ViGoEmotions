# ViGoEmotions: A Benchmark Dataset For Fine-grained Emotion Detection on Vietnamese Texts

## Dataset information: 
+ Link dataset (Gated): https://huggingface.co/datasets/uitnlp/vigoemotions   
+ Datasize: 20,664 comments from social network sites.
+ Label: 27 categories of emotion, each comment can have multiple emotions.

## Label mapping: 
| Index | Emotion |
|------:|---------|
| 0 | amusement |
| 1 | excitement |
| 2 | joy |
| 3 | love |
| 4 | desire |
| 5 | optimism |
| 6 | caring |
| 7 | pride |
| 8 | admiration |
| 9 | gratitude |
| 10 | relief |
| 11 | approval |
| 12 | realization |
| 13 | surprise |
| 14 | curiosity |
| 15 | confusion |
| 16 | fear |
| 17 | nervousness |
| 18 | remorse |
| 19 | embarrassment |
| 20 | disappointment |
| 21 | sadness |
| 22 | grief |
| 23 | disgust |
| 24 | anger |
| 25 | annoyance |
| 26 | disapproval |
| 27 | neutral |


## Source codes:
The source code is published in the "model" directory, containing the Jupyter files. 

## License: 
- The dataset is only used for non-profit research for natural language processing and education.      
- The dataset is not allowed to be used in commercial systems.    
- Do not redistribute the dataset. This dataset may be modified or improved to serve a research purpose better, but the edited dataset may not be distributed.     
- Summaries, analyses, and interpretations of the properties of the dataset may be derived and published, provided it is not possible to reconstruct the information from these summaries.    

## Publication: 
Please cite this paper if you use our dataset: 
```
@inproceedings{hung-etal-2026-vigoemotions,
    title = "{V}i{G}o{E}motions: A Benchmark Dataset For Fine-grained Emotion Detection on {V}ietnamese Texts",
    author = "Hung, Tran Quang  and
      Nam, Pham Tien  and
      Luu, Son T.  and
      Nguyen, Kiet Van",
    editor = "Demberg, Vera  and
      Inui, Kentaro  and
      Marquez, Llu{\'i}s",
    booktitle = "Proceedings of the 19th Conference of the {E}uropean Chapter of the {A}ssociation for {C}omputational {L}inguistics (Volume 1: Long Papers)",
    month = mar,
    year = "2026",
    address = "Rabat, Morocco",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2026.eacl-long.129/",
    doi = "10.18653/v1/2026.eacl-long.129",
    pages = "2805--2831",
    ISBN = "979-8-89176-380-7",
    abstract = "Emotion classification plays a significant role in emotion prediction and harmful content detection. Recent advancements in NLP, particularly through large language models (LLMs), have greatly improved outcomes in this field. This study introduces ViGoEmotions - a Vietnamese emotion corpus comprising 20,664 social media comments in which each comment is classified into 27 fine-grained distinct emotions. To evaluate the quality of the dataset and its impact on emotion classification, eight pre-trained Transformer-based models were evaluated under three preprocessing strategies: preserving original emojis with rule-based normalization, converting emojis into textual descriptions, and applying ViSoLex, a model-based lexical normalization system. Results show that converting emojis into text often improves the performance of several BERT-based baselines, while preserving emojis yields the best results for ViSoBERT and CafeBERT. In contrast, removing emojis generally leads to lower performance. ViSoBERT achieved the highest Macro F1-score of 61.50{\%} and Weighted F1-score of 63.26{\%}. Strong performance was also observed from CafeBERT and PhoBERT. These findings highlight that while the proposed corpus can support diverse architectures effectively, preprocessing strategies and annotation quality remain key factors influencing downstream performance."
}
``` 

