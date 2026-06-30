# 测试数据说明

原始目录未提供独立的 `test_data/` 测试数据目录。

当前 `test/` 中仅包含 `linear_blending_forecast` 的最小单元测试，不依赖真实 NetCDF 或 MICAPS 业务数据。完整时间拆分、SCD 融合和结果补齐流程需要补充小体量的 `unet_qpf`、`mait_st`、实况和配对融合样例数据后再进行集成测试。
