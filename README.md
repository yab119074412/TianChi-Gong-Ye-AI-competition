# TianChi-Gong-Ye-AI-competition
队伍名称：北郡牧师

初赛：13/2529

复赛：47/2529

个人真正意义上第一次认真做的比赛，赛题情况如下：https://tianchi.aliyun.com/competition/introduction.htm?spm=5176.100150.711.10.744a200924aGPC&raceId=231633

这个比赛跟以往不同的是它所有的特征都是匿名的，只是以相应的代号表示，而且特征维度特别多，数据量又比较少，造成在比赛前期，有人用小号试答案。

我们的做法大概如下：首先删除缺失值大于70%的特征，删除方差接近于0的特征，再根据皮尔逊相关系数筛选特征，对缺失值进行众数或者中位数的填充。

模型方面试了下lassoCV、贝叶斯岭回归、线性回归、GBDT等等。

成绩在a榜上面始终不好，中途一度想放弃，没想到换b榜后一下子冲到了第4(最后一天又掉到了13)，这给了我们很大的信心，在复赛数据量增加后，可能队伍想的方案不够周全，因此最终排到了47。后面希望多参加比赛，提高自己！
