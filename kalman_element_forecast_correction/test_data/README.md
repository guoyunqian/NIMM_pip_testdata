# test_data

原始 `nimm_kalman` 目录没有独立测试数据目录。

当前测试主要覆盖 `utils/grid_utils.py` 的纯数值和网格工具逻辑；完整 Kalman 业务流程依赖外部生产路径中的预报、实况和历史误差场文件。

正式补充到算法仓库前，建议准备最小 NetCDF 样例：

- 一个预报场 `fcst_new.nc`
- 一个实况场 `obs_new.nc`
- 一个历史误差场 `me_before.nc`
- 一个期望订正结果或误差场对照文件

