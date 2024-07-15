# crawler-test
GYAFC 数据集处理程序
数据来源: https://aclanthology.org/N18-1012/
下载地址: https://huggingface.co/datasets/RUCAIBox/Style-Transfer
所在位置: GYAFC Dataset/code
数据集介绍
这个数据包括两个领域的数据

em: Entertainment & Music
fr: Family & Relationships
其中每个领域包括三类数据集 (train, test, valid), 其中informal在.src，formal中.tgt中, train中两种风格文本一一配对，test和valid中则是一对多配对

使用方法
打开code/main.py
然后配置主函数中的各个参数
再在GYAFC Dataset路径下运行该程序 在其他路径下运行可能会影响输入和输出的位置
