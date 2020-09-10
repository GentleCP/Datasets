# Datasets
记录我学习过程中用到的数据集，较小的数据集直接存储（提供压缩文件用于远程直接下载单独使用），较大的数据集提供下载链接。

# NLP

自然语言处理数据集，包括命名实体识别(NER)，文本分类(TextClassification)，唐诗数据

## 命名实体识别

- [MSRA](https://gentlecp.github.io/Datasets/NLP/NER/MSRA.zip)
- [人民日报](https://gentlecp.github.io/Datasets/NLP/NER/RMRB.zip)

## 文本分类

- 电影评论情感分类
  - [train.txt](https://gentlecp.github.io/Datasets/NLP/TextClassification/FilmComment/train.txt)：包含2W条左右中文电影评论，其中正负向评论各1W条左右
  - [validation.txt](https://gentlecp.github.io/Datasets/NLP/TextClassification/FilmComment/validation.txt)：包含6K条左右中文电影评论，其中正负向评论各3K条左右
  - [test.txt](https://gentlecp.github.io/Datasets/NLP/TextClassification/FilmComment/test.txt)：包含360条左右中文电影评论，其中正负向评论各180条左右

## 唐诗数据

在自动写诗任务中用到的唐诗数据。

- [tang.npz](https://gentlecp.github.io/Datasets/NLP/Poetry/tang.npz)：已经预处理完成的数据文件，包含57580首唐诗，用`numpy`读取,`word2ix`,`ix2word`,`data`

## wiki语料

`wiki`上用于训练词向量的语料库，包含英文(16.5GB)和中文(1.2GB)，数据量过大，提供国内外两种下载线路。

- [wiki-中文语料库](http://bj.bcebos.com/v1/ai-studio-online/99c28dbf20884136b26a92e2ba67f06a28b2dd8db0b747efb9cebf80d5913608?responseContentDisposition=attachment%3B%20filename%3Dwiki.zh.zip&authorization=bce-auth-v1%2F0ef6765c1e494918bc0d4c3ca3e5c6d1%2F2020-06-16T09%3A59%3A00Z%2F-1%2F%2F0f5223b2505a5e05a578d0b17167ed096d5fd6dd46f9708ea49d58cf00b107c2)：关于该语料库的介绍可参考[一次gensim的Word2Vec体验之旅](https://www.gentlecp.com/articles/882.html)，包含对数据的处理和词向量训练。

- [wiki-英文语料库](http://bj.bcebos.com/v1/ai-studio-online/a2f1552fe67d40078ef20b5cdd08d0c449fda1a8803446f783315d938c2265b9?responseContentDisposition=attachment%3B%20filename%3Dwiki.en.zip&authorization=bce-auth-v1%2F0ef6765c1e494918bc0d4c3ca3e5c6d1%2F2020-09-10T09%3A40%3A20Z%2F-1%2F%2F686807a905d2b2a762cf3bc4bcb3556f6597540436700171281839ecb5ab0c58)：与中文语料库相对应。

# 数据分析

数据分析相关数据集

## Kaggle

- [Titanic](https://gentlecp.github.io/Datasets/data-analysis/titanic.zip)：`Kaggle`的`Titanic`数据集，具体可以参考[Kaggle](https://www.kaggle.com/c/titanic/data)。





