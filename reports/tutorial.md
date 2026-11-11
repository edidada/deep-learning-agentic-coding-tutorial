# MIT 6.7960 Agentic Coding Tutorial：公开补充教程

官方Fall2026课程页 https://deeplearning6-7960.github.io/ 的Agentic Coding Tutorial
链接指向anakhag07/deep-learning-agentic-coding-tutorial。原始提交
cf265ff49c5df9506a48e0795745d6a5dcead580；原experiment.py与原测试完全保留。
本次仅fork/clone、增加独立edidada/tutorial分支及tutorial.yml验证、中文报告。
不把已提供的实现说成新实现，不把教程当作正式pset starter；pset仍受课程平台限制。

按仓库launch-experiment/visualize-experiment技能流程：原unittest后CPU实验，
Agg PNG保留坐标/并排边界/held-out点与准确率；环境固定并保存pip freeze。
用户要求本地不运行实验，因此全部执行在Actions，不使用本地训练或ORCD资源。
512合成样本、384训练/128测试、默认200步；仅说明该合成数据任务中的非线性效果。
无外部数据下载、CUDA或大模型训练；以最终SHA运行结果和图像检查为准。
