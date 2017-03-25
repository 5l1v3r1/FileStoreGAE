# File Store on GAE

### 用途

* 将GAE用作私图床
* 存储小体积的文件

### 特性

* 使用DataStore存储文件
    * 使用memcache进行优化，免费配额下数据库不在瓶颈，可跑满每日流量。
