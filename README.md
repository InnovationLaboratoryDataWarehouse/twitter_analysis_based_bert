# twitter_analysis_based_bert

bert, multilabed-classification, twitter, visualization

基于108万公开标注数据集（清洗后保留下来40万），利用Bert训练了7分类的情感分类模型（neural,angry,disgust,fear,sad,joy,surprise）。模型的基本情况如下：



之后利用模型对100万条与'CCP'有关的推特推文进行预测，标注情感后，根据他们的互动情况绘制社会网络图。

已经将训练模型的代码公开。100万条推特推文，因为数据不归本人所有，属于团队所有，故只能将图片公开。

下图为其中某一月份的推特互动图，绿色为joy,黄色为fear，红色为angry,蓝色为sad,粉色为disgust（surprise,和neural已经被剔除）。
