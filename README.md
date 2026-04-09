# Minrun Package

这是当前可直接验证的小跑版本地包。

## 入口

- `api.json`
- `jar/custom_spider.jar`

## 当前保留站点

- `csp_Jianpian`
- `csp_Bili`
- `csp_BiliPGC`
- `csp_Kanqiu`
- `csp_YHDM`
- `csp_Push`
- `csp_Local`
- `csp_Market`

其中 `Bili` 相关条目在 `api.json` 中展开成多个栏目，共 17 个站点配置项。

## 资源

已随包复制的配置文件：

- `config/bilibili.json`
- `config/blts.json`
- `config/blxp.json`
- `config/blxq.json`
- `config/blxs.json`
- `config/blych.json`
- `config/blys.json`
- `config/czkt.json`
- `config/gzkt.json`
- `config/jianpian.json`
- `config/market.json`
- `config/sejy.json`
- `config/xxkt.json`

## 说明

这是“源码可编译、可装进壳里先验证”的第一阶段产物。

后续 richer 站点会继续按批次接入：

1. 先替换反编译失真的 `api/merge` 层阻塞类
2. 再逐步把 richer Spider 接回源码直编译工程
