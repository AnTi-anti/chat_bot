课程来在[七月在线的自动聊天机器人项目班](https://www.julyedu.com/course/getDetail/60)

课程是2017年出来的，现在看除了一些基本的NLP理论知识，对机器人的理解和工业开发上已经有了很大的改变。

如果对NLP和聊天机器人感兴趣的同学可以可以看看本篇笔记，我会在后面加上一些现在比较前言的知识和实战。


### 第一课 聊天机器人的基础模型与综述
* 第一课PPT：[点我](https://github.com/AnTi-anti/chat_bot/blob/master/%E7%AC%AC%E4%B8%80%E8%AF%BE%20%E8%81%8A%E5%A4%A9%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%9A%84%E5%9F%BA%E7%A1%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BB%BC%E8%BF%B0/ppt.pdf)
* 课程代码：[点我](https://github.com/AnTi-anti/chat_bot/blob/master/%E7%AC%AC%E4%B8%80%E8%AF%BE%20%E8%81%8A%E5%A4%A9%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%9A%84%E5%9F%BA%E7%A1%80%E6%A8%A1%E5%9E%8B%E4%B8%8E%E7%BB%BC%E8%BF%B0/1_1.ipynb)

### 第二课 NLP基础及扫盲
* 主要内容：
  * NLTK
    * 语料库--corpus
  * 文本处理流程 
    * 分词
      * 简单分词--word_tokenize
      * 中文分词--jieba
      *  复杂分词，采用[正则表达式](http://www.regexlab.com/zh/regref.htm)预处理
    * 归一化
      * Steamming词干提取：把不影响词性的inflection的小尾巴砍掉
      * 单词词性标注：nltk.pos_tag
      * Lemmatization词形归一：把各种类型的词的变形，都归为一个形式
 
    * 停止词
      * 库：from nltk.corpus import stopwords
      * stopwords列表：http://www.ranks.nl/stopwords
  * NLP经典三个案例
    * 情感分析
      * 简单情感分析
      * 搭配ML的情感分析
    * 文本相似度
      * 余弦定理
      * Frequency词频统计
        * nltk.FreDist
    * 文本分类
      * [TF-IFD](https://blog.csdn.net/weixin_35770067/article/details/108245413)
   * [gensim](https://blog.csdn.net/weixin_35770067/article/details/108252739)
  * 深度学习加持
    * Autoencoder
    * [Word2Vec](https://blog.csdn.net/weixin_35770067/article/details/108257134)
* 第二课PPT：[点我](https://github.com/AnTi-anti/chat_bot/blob/master/%E7%AC%AC%E4%BA%8C%E8%AF%BE%20NLP%E5%9F%BA%E7%A1%80%E5%8F%8A%E6%89%AB%E7%9B%B2/%E7%AC%AC%E4%BA%8C%E8%AF%BE%20NLP%E5%9F%BA%E7%A1%80.pdf)
* 第二课代码和文档：[点我](https://github.com/AnTi-anti/chat_bot/tree/master/%E7%AC%AC%E4%BA%8C%E8%AF%BE%20NLP%E5%9F%BA%E7%A1%80%E5%8F%8A%E6%89%AB%E7%9B%B2)
* 数据集：[点我](https://github.com/AnTi-anti/chat_bot/tree/master/%E7%AC%AC%E4%BA%8C%E8%AF%BE%20NLP%E5%9F%BA%E7%A1%80%E5%8F%8A%E6%89%AB%E7%9B%B2/data)

### 第三课 用基础机器学习方法制作聊天机器人
* 主要内容
  * 关于聊天机器人的思考
    * 1.工程考量
    * 2.机器学习角度考量
   * 预备知识
     * 1.检索与匹配
     * 2.分类与朴素贝叶斯
   * chatterbot
     * 1.架构与使用方法
     * 2.源码分析
     * 3.[用python，Django和Flask构造一个基于网页端的聊天机器人](https://blog.csdn.net/weixin_35770067/article/details/108272583)
* PPT：[点我](https://github.com/AnTi-anti/chat_bot/blob/master/%E7%AC%AC%E4%B8%89%E8%AF%BE%20%E7%94%A8%E5%9F%BA%E7%A1%80%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E6%96%B9%E6%B3%95%E5%88%B6%E4%BD%9C%E8%81%8A%E5%A4%A9%E6%9C%BA%E5%99%A8%E4%BA%BA/%E7%AC%AC3%E8%AF%BE-%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E6%9E%84%E5%BB%BA%E8%81%8A%E5%A4%A9%E6%9C%BA%E5%99%A8%E4%BA%BA.pdf)
* 代码和笔记：[点我](https://github.com/AnTi-anti/chat_bot/blob/master/%E7%AC%AC%E4%B8%89%E8%AF%BE%20%E7%94%A8%E5%9F%BA%E7%A1%80%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E6%96%B9%E6%B3%95%E5%88%B6%E4%BD%9C%E8%81%8A%E5%A4%A9%E6%9C%BA%E5%99%A8%E4%BA%BA/1_3.ipynb)

### 第四课 深度学习基础及扫盲
* 主要内容
  * 循环神经网络
    * 1.场景与多种应用
    * 2.NLP文字序列最爱的RNN
    * 3.BPTT算法
    * 4.[利用Microsoft COCO数据集和pytorch实现看图说话](https://blog.csdn.net/weixin_35770067/article/details/108275797)
   * LSTM
      * 1.长时依赖问题
      * 2.记忆细胞与状态
  * NLP中的应用
    * 1.各式各样的生成模型
      * RNN生成模仿仿照维基百科
      * RNN生成模型写食谱
      * 模仿奥巴马演讲
    * 2.看图说话基础版与高级版
      * [[Attention](训练样本中问题长度的分布，主要接种在0-100之间)
    * 3.序列到序列学习(机器翻译等)
* 代码和文档：[点我](https://github.com/AnTi-anti/chat_bot/blob/master/%E7%AC%AC%E5%9B%9B%E8%AF%BE%20%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E5%9F%BA%E7%A1%80%E5%8F%8A%E6%89%AB%E7%9B%B2/1_4.ipynb)

### 第五课 深度学习聊天机器人原理
* 主要内容
* 更聪明的聊天机器人
  * 1.生成式模型 VS 检索匹配模型
  * 2.Chatterbot的进化：深度学习提高智能度
* 模型构建
  * 1.问题的分析与转化
  * 2.数据集与样本构造方法
  * 3.模型结构的构建
  * 4.模型的评估
  * 5.代码实现与解析
* PPT：[点我](https://github.com/AnTi-anti/chat_bot/blob/master/%E7%AC%AC%E4%BA%94%E8%AF%BE%20%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%81%8A%E5%A4%A9%E6%9C%BA%E5%99%A8%E4%BA%BA%E5%8E%9F%E7%90%86/%E7%AC%AC5%E8%AF%BE-%E5%9F%BA%E4%BA%8E%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E7%9A%84%E6%A3%80%E7%B4%A2%E8%81%8A%E5%A4%A9%E6%9C%BA%E5%99%A8%E4%BA%BA.pdf)
* 代码和笔记：[点我](https://github.com/AnTi-anti/chat_bot/blob/master/%E7%AC%AC%E4%BA%94%E8%AF%BE%20%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E8%81%8A%E5%A4%A9%E6%9C%BA%E5%99%A8%E4%BA%BA%E5%8E%9F%E7%90%86/1_5.ipynb)

### 第六课 用深度学习方法制作聊天机器人
* 代码和笔记：[点我](https://github.com/AnTi-anti/chat_bot/blob/master/%E7%AC%AC%E5%85%AD%E8%AF%BE%20%E7%94%A8%E6%B7%B1%E5%BA%A6%E6%96%B9%E6%B3%95%E5%88%B6%E4%BD%9C%E8%81%8A%E5%A4%A9%E6%9C%BA%E5%99%A8%E4%BA%BA/1_6.ipynb)

### 第七课 看图回答VQA
* 主要内容
  * VQA视觉聊天机器人
* PPT：[点我](https://github.com/AnTi-anti/chat_bot/blob/master/%E7%AC%AC%E4%B8%83%E8%AF%BE%20%E7%9C%8B%E5%9B%BE%E5%9B%9E%E7%AD%94VQA/%E7%AC%AC%E4%B8%83%E8%AF%BE%20VQA.pdf)
* 代码和笔记：[点我](https://github.com/AnTi-anti/chat_bot/blob/master/%E7%AC%AC%E4%B8%83%E8%AF%BE%20%E7%9C%8B%E5%9B%BE%E5%9B%9E%E7%AD%94VQA/1_7.ipynb)

### 第八课 简单易用的俩天机器人开发平台与展望
* PPT：[点我](https://github.com/AnTi-anti/chat_bot/blob/master/%E7%AC%AC%E5%85%AB%E8%AF%BE%20%E7%AE%80%E5%8D%95%E6%98%93%E7%94%A8%E7%9A%84%E8%81%8A%E5%A4%A9%E6%9C%BA%E5%99%A8%E4%BA%BA%E5%BC%80%E5%8F%91%E5%B9%B3%E5%8F%B0%E4%B8%8E%E5%B1%95%E6%9C%9B/%E8%81%8A%E5%A4%A9%E6%9C%BA%E5%99%A8%E4%BA%BA.html)
  



