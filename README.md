[toc]

# reading_list

## 数据可视化

*Information Visualization and Visual Data Mining*

可视化的优点。

哪些数据和哪些技术手段。

 [Information_visualization_and_visual_data_mining.pdf](Information_visualization_and_visual_data_mining.pdf) 

## x‑index

*x‑index: Identifying core competency and thematic research strengths of institutions using an NLP and network based ranking framework*

> 确定机构的核心能力，通过基于网络的排名框架

主要是科研机构的评级 来确定其核心能力和研究主题



## 中文论文

*基于语言模型的预训练技术研究综述*
Word2vec、GloVe对神经网络语言模型进行简化，实现符号空间到向量空间的映射，标志着静态词嵌入（word embedding）的诞生。
预训练的**核心思想**是：放弃模型的随机初始化，先用大语料库对模型进行预训练，得到蕴含上下文信息的通用语言表示，然后对相应的下游任务进行微调fine-tuning。
2013年 谷歌提出 word2vec 模型
【任务一】使用 word2vec 做一个小demo

2017年，Facebook提出FastText模型，解决 word2vec 无法解决的OOV问题
*Enriching Word Vectors with Subword Information*
2014 GloVe *Global Vectors for Word Representation*

**基于静态词嵌入预训练技术的缺点**：与上下文无关，无法有效表示更高级的特征

Transformer出现：
![image-20211231175723523](C:/Users/Lee/AppData/Roaming/Typora/typora-user-images/image-20211231175723523.png)

## word2vec

 [word2vec.pdf](word2vec.pdf) 



## attention机制

 [注意力机制-机器翻译.pdf](注意力机制-机器翻译.pdf) 



## transformer

*attention is all you need*

 [attention is all you need.pdf](attention is all you need.pdf) 



word2vec->glove->elmo 

## ELMO 





## BERT 

 [bert.pdf](bert.pdf) 

ELMO + GPT

illustrated bert

### Mask LM

### next sentense prediction

核心：Transformers+预训练任务



## roberta



## pegasus 摘要任务
rouge1 -评价指标
rouge2
rougeL
