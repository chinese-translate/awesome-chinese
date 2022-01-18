# awesome-chinese [![translate-svg]][translate-list]

[translate-svg]: http://llever.com/translate.svg
[translate-list]: https://github.com/chinese-translate/awesome-chinese

<!-- DOCTOC START -->
<!-- DOCTOC END -->

## TiDB

[TiDB](https://github.com/pingcap/tidb) 是 [PingCAP](https://pingcap.com/zh/) 公司受 Google Spanner / F1 论文启发而设计的开源分布式 HTAP (Hybrid Transactional and Analytical Processing) 数据库，结合了传统的 RDBMS 和 NoSQL 的最佳特性。

[TiKV](https://github.com/tikv/tikv) 是一个分布式事务型的键值数据库，提供了满足 ACID 约束的分布式事务接口，并且通过 Raft 协议保证了多副本数据一致性以及高可用。**TiKV 作为 TiDB 的存储层**，为用户写入 TiDB 的数据提供了持久化以及读写服务，同时还存储了 TiDB 的统计信息数据。

[TiDB 中文文档网址](https://docs.pingcap.com/zh/tidb/stable/) | [Github Repo](https://github.com/pingcap/docs-cn)

## Electron

[Electron](https://www.electronjs.org/zh/docs/latest/) 是一个使用 JavaScript、HTML 和 CSS 构建桌面应用程序的框架。

为什么，我会提起这个框架，完全是因为 [fiddle](https://github.com/electron/fiddle)，
以及 [官方对中文文档的推进](https://www.electronjs.org/zh/docs/latest/)。

当然，80% 是 fiddle 的功劳，因为它解决了新手入门，以及版本变化的痛点，如下：
~~你是否为了失眠多梦~~
1. Electron 的入门，往往从 示例开始着手，下载，安装，启动。打开编辑器，再看源码。
2. Electron 版本间的差异，也就是 API 差异，惨白地浮于表面，每次都要找示例代码，还不能马上看到结果，版本与示例之间没有明确关联。

解：Electron fiddle 启动，就是一个编辑器，源码全在。
- 一键安装（当然，国内下载可人，可用本地版本），不同的 Electron。
- 一键更换版本。
- 二键示例，启动。

> 当然，官方相当，非常，十分明确，**新的 Electron 版本更新后，请随之更新你的软件**
