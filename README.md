# NLP-task-review
NLP考试，稍微整理一下NLP的相关任务和使用的方法。 ————一个无情的搬运工！

主要参考[nlp-task](https://github.com/Kyubyong/nlp_tasks)和[nlp-progress](https://nlpprogress.com/)，尽量选中文材料，读起来方便。

### Automatic speech recognition (ASR)
自动语音识别，wiki里写的比较详细。

  * ****`wiki`**** [Speech recognition](https://en.wikipedia.org/wiki/Speech_recognition#Models,_methods,_and_algorithms)
  * ****`wiki`**** [语音识别](https://zh.wikipedia.org/wiki/%E8%AF%AD%E9%9F%B3%E8%AF%86%E5%88%AB)
  * ****`guide`**** [A 2019 Guide for Automatic Speech Recognition](https://heartbeat.fritz.ai/a-2019-guide-for-automatic-speech-recognition-f1e1129a141c)
  * ****`history`**** [语音识别技术简史](https://zhuanlan.zhihu.com/p/82872145)
  * ****`method`**** [语音识别的技术原理是什么？](https://www.zhihu.com/question/20398418)

### Common sense
空

### Coreference resolution
共指消解，选出句子中指代含义相同的词。CS224n里讲的比较细，只做简单了解即可。

  * ****`baike`**** [共指消解](https://baike.baidu.com/item/%E5%85%B1%E6%8C%87%E6%B6%88%E8%A7%A3)
  * ****`slides`**** [cs224n-2019-lecture16-coref](https://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture16-coref.pdf)
  * ****`notes`**** [CS224n-2019 学习笔记](https://looperxx.github.io/CS224n-2019-16-Coreference%20Resolution/)

### Dependency parsing
空

### Dialogue System
对话系统，PJ做的这个，推荐第一篇。

  * ****`guide`**** [认真的聊一聊对话系统](https://zhuanlan.zhihu.com/p/83825070)
  * ****`intuition`**** [5 Radical Ideas for Dialogue Systems](https://www.gamasutra.com/blogs/BobbyLockhart/20171107/309121/5_Radical_Ideas_for_Dialogue_Systems.php)
  * ****`guide`**** [Dialog System 总结](https://blog.csdn.net/abcjennifer/article/details/53428053)

### Domain adaptation
空

### Grammatical Error Correction
自动语法纠错，推荐第一篇。

  * ****`guide`**** [自然语言处理在自动语法纠错中的应用](https://flashgene.com/archives/38517.html)
  * ****`method`**** [Deep Text Corrector](http://atpaino.com/2017/01/03/deep-text-correcter.html)
  * ****`application`**** [Using neural machine translation to correct grammatical faux pas in Google Docs](https://cloud.google.com/blog/products/productivity-collaboration/using-neural-machine-translation-to-correct-grammatical-in-google-docs)
  
### Information extraction
信息抽取，比较大的一个task，其中分为几个小task在之后会单独列出。  
  
  * ****`wiki`**** [Information extraction](https://en.wikipedia.org/wiki/Information_extraction)
  * ****`wiki`**** [信息抽取](https://zh.wikipedia.org/wiki/%E4%BF%A1%E6%81%AF%E6%8A%BD%E5%8F%96)
  * ****`guide`**** [关于信息抽取的整理总结(上)](https://blog.csdn.net/hqc888688/article/details/73558824)
  * ****`guide`**** [关于信息抽取的整理总结(下)](https://blog.csdn.net/hqc888688/article/details/73558979)
  * ****`guide`**** [Information Extraction Note and Summary](https://zhuanlan.zhihu.com/p/62847358)

### Language modeling
语言模型，课上讲的比较多，这里就少放些。

  * ****`wiki`**** [Language model](https://en.wikipedia.org/wiki/Language_model)
  * ****`history`**** [A Review of the Neural History of Natural Language Processing](https://ruder.io/a-review-of-the-recent-history-of-nlp/)

### Machine translation
机器翻译，老生常谈的task，教程也比较多，最后一篇的回答里写的比较好。

  * ****`wiki`**** [Machine translation](https://en.wikipedia.org/wiki/Machine_translation)
  * ****`guide`**** [Machine translation](https://www.andovar.com/machine-translation/)
  * ****`guide`**** [机器翻译的流程（原理）是怎么样的？](https://www.zhihu.com/question/24588198)


### Named entity recognition
命名实体识别，推荐最后一篇。

  * ****`wiki`**** [Named-entity recognition](https://en.wikipedia.org/wiki/Named-entity_recognition)
  * ****`intro`**** [Introduction to Named Entity Recognition](https://medium.com/explore-artificial-intelligence/introduction-to-named-entity-recognition-eda8c97c2db1)
  * ****`guide`**** [NLP实战-中文命名实体识别](https://zhuanlan.zhihu.com/p/61227299)
  * ****`guide`**** [信息抽取(Information Extraction:NER(命名实体识别),关系抽取)](https://zhuanlan.zhihu.com/p/67613067)

### Natural language inference
空

### Part-of-speech tagging
空

### Relationship extraction
关系抽取，第二篇和后两篇介绍的比较详细。

  * ****`wiki`**** [Relationship extraction](https://en.wikipedia.org/wiki/Relationship_extraction)
  * ****`guide`**** [Different ways of doing Relation Extraction from text](https://medium.com/@andreasherman/different-ways-of-doing-relation-extraction-from-text-7362b4c3169e)
  * ****`intro`**** [What is Relationship Extraction?](https://www.netowl.com/2019/06/12/what-is-relationship-extraction)
  * ****`guide`**** [知识抽取-实体及关系抽取](http://www.shuang0420.com/2018/09/15/%E7%9F%A5%E8%AF%86%E6%8A%BD%E5%8F%96-%E5%AE%9E%E4%BD%93%E5%8F%8A%E5%85%B3%E7%B3%BB%E6%8A%BD%E5%8F%96/)
  * ****`guide`**** [关系抽取(关系学习)综述](https://rilzob.com/2019/04/01/%E5%85%B3%E7%B3%BB%E6%8A%BD%E5%8F%96%E7%BB%BC%E8%BF%B0/)

### Sentiment analysis
空

### Simplification
空

### Spelling correction
拼写纠错，与语法纠错相比介绍的文章多一些。

  * ****`guide`**** [计算语言学之拼写纠错](https://blog.csdn.net/qq_35082030/article/details/72981400)
  * ****`guide`**** [从n-gram中文文本纠错，到依存树中文语法纠错以及同义词查找](https://my.oschina.net/keyven/blog/516808)
  * ****`guide`**** [NLP上层应用的关键一环——中文纠错技术简述](https://zhuanlan.zhihu.com/p/82807092)

### Summarization
文本摘要，后两篇都写得不错。

  * ****`wiki`**** [Automatic summarization](https://en.wikipedia.org/wiki/Automatic_summarization)
  * ****`guide`**** [A Quick Introduction to Text Summarization in Machine Learning](https://towardsdatascience.com/a-quick-introduction-to-text-summarization-in-machine-learning-3d27ccf18a9f)
  * ****`guide`**** [文本摘要简述](https://www.jiqizhixin.com/articles/2019-03-25-7)

### Text classification
文本分类，比较经典的task，这里只选取两篇。

  * ****`guide`**** [Text Classification](https://monkeylearn.com/text-classification/)
  * ****`guide`**** [文本分类综述，机器学习/深度学习方法总结](https://zhuanlan.zhihu.com/p/40182925)

### Chinese word segmentation
中文分词，当然大部分介绍都是中文的。

  * ****`guide`**** [中文分词原理及工具](https://cuiqingcai.com/5844.html)
  * ****`guide`**** [中文分词常用方法简述](https://www.jianshu.com/p/6c085bf1086f)
