# go-database-material
该项目是一个收集Go语言相关存储引擎资料的仓库。在现代应用程序中，数据存储和管理至关重要。因此，选择正确的存储引擎对应用程序的性能和稳定性具有重要影响。这个仓库汇总了各种与Go语言相关的存储引擎、数据库和缓存技术的链接，资料包括但不限于文档、文章、演示、教程等等。通过这个仓库，开发者可以更加高效地探索和学习不同的存储方案，以及选择最适合他们项目需求的解决方案。如果您也有一些值得分享的存储引擎资料，欢迎提交 PR 贡献到这个仓库中来。

## Database
1. [pingcap数据库学习资料](https://github.com/pingcap/awesome-database-learning)
2. [CMU 数据库系统课程](https://www.bilibili.com/video/BV1b44y1o7YH/?share_source=copy_web&vd_source=c4c33172b0b63f4ed3d6a29bfd461101)

## 磁盘和存储引擎综述
1. [磁盘IO那些事](https://tech.meituan.com/2017/05/19/about-desk-io.html)
2. [数据存储与检索(详解b+树存储引擎(innodb、boltdb、buntdb等)、lsm树存储引擎(bitcask、moss、pebble、leveldb等)]( https://www.bilibili.com/video/BV1Zv411G7ty/?share_source=copy_web&vd_source=c4c33172b0b63f4ed3d6a29bfd461101)

## 1. Hash
1. [Bitcask paper](https://riak.com/assets/bitcask-intro.pdf) 
2. [nutsdb](https://github.com/nutsdb/nutsdb) 
3. [rosedb](https://github.com/flower-corp/rosedb) 
4. [tiny-bitcask](https://github.com/elliotchenzichang/tiny-bitcask) 
5. [nutsdb设计与实现 Go夜读分享](https://www.bilibili.com/video/BV1T34y1x7AS/?spm_id_from=333.337.search-card.all.click&vd_source=0989a2ca09448a0642a2e4a13bec56f6) 
6. [rosedb 设计与实现Go夜读分享](https://www.bilibili.com/video/BV1ih411h7yC/?spm_id_from=333.337.search-card.all.click&vd_source=0989a2ca09448a0642a2e4a13bec56f6)
7. [如何实现一个简单基于Bitcask的kv存储引擎](https://blog.csdn.net/LuciferMS/article/details/127947587?spm=1001.2014.3001.5502)

## 2. B+Tree
1. [Boltdb](https://github.com/boltdb/bolt) 
2. [自底向上分析 BoltDB 源码](https://www.bookstack.cn/books/jaydenwen123-boltdb_book) 
3. [Google B-Tree实现](https://wingsxdu.com/posts/data-structure/btree/) 

## 3. LSM-Tree
1. [LSM paper](https://www.cs.umb.edu/~poneil/lsmtree.pdf) 
2. [Wisckey paper](https://www.usenix.org/system/files/conference/fast16/fast16-papers-lu.pdf) 
3. [goleveldb](https://github.com/syndtr/goleveldb) 
4. [badgerdb](https://github.com/dgraph-io/badger) 
5. [leveldb hand-book](https://leveldb-handbook.readthedocs.io/zh/latest/basic.html) 
6. [LSM-Tree 论文翻译](https://github.com/tangwz/LSM-Tree-CN)
7. [关于WicsKey的对话，知乎专栏](https://www.zhihu.com/column/c_1603024468401676288)
8. [pebbledb](https://github.com/cockroachdb/pebble)
