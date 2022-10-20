## Open Questions
You can prepare in advance, search or consult others, but we will ask some details in the formal interview

# 文本数据处理
- 如何统计出 Nginx 日志里某时间段内请求量最大的 `ip` 和被访问最多的 `url`？
- 一个 500G 的文本文件，每一行是一个 `json` 字符串，如何把它快速的导入到 MySQL 中？
- 一个 500 G 的 csv.gz 压缩文件，如何快速导入到`MySQL`中，如何查看导入的进度？
- 如何从一封邮件中提取出所有的签名中的姓名、头衔、电话和邮箱(签名见下图所示)？如果有几百万封邮件，你会如何设计这个系统。<img width="739" alt="image" src="https://user-images.githubusercontent.com/2787748/196858026-253c2e59-0fe0-4406-b338-c7a5ac7bdea6.png">

    
# SQL
- 一个表里有年龄列(age)，如何统计各个年龄范围内人的数量？
- 在不同数据库实例上的两个表，如何计算某一列相同的数量有多少？
- 如何在不影响正常业务的情况下给一个 6 亿数据的大表在线加索引和加列？
- 如何在一个 6 亿数据的大表里统计出 location 相同的 Top 1000 locations？
    
# Elasticsearch
- Elasticsearch 如何处理同义词和搜索建议？
- 如何让某个 popularity 字段做为 Elasticsearch 搜索结果排序的一个因子？
- Elasticsearch 的搜索速度突然变慢，如何定位和解决问题？
- 如何加快 Elasticsearch 的索引写入速度？
