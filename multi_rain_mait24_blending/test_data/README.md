# test_data

原始 `mait_24h` 目录没有独立 `test_data/` 目录。

本次中间整理保留原始 `resource/` 中的配置、掩码、站点表、样例 h5 和图片资源；测试脚本目前主要依赖 `resource/` 以及外部 Micaps 业务数据路径。

正式补充到算法仓库前，建议从 `resource/` 与业务数据环境中筛选最小可复现实例，放入 `test_data/`。

