<div align="center">

# Ethan-39

**AI for Green · Energy Forecasting · Carbon Management**

大一学生，正在学习 Python 和机器学习，并尝试把它们用于可持续发展问题。

[旗舰项目：MedEnergy](https://github.com/Ethan-39/medenergy) · [支撑项目](#supporting-projects)

<a href="https://github.com/Ethan-39/medenergy"><img src="https://raw.githubusercontent.com/Ethan-39/medenergy/main/assets/dashboard-overview.png" alt="MedEnergy interactive dashboard preview" width="760"></a>

</div>

## 当前方向

我关注能源预测怎样与碳核算和实际运行约束结合。最近在准备 AI FOR GREEN 创新比赛，并与一位生物科学专业队友探索实验室/医疗场景下的绿色能源管理。当前作品以教学仿真为主，重点是把数据来源、比较基线、约束和结果边界交代清楚。

## Projects

### MedEnergy · 旗舰项目

能源预测与碳感知排程教学原型。包含交互看板、时间顺序测试集、朴素预测基线、模拟批任务约束和费用/碳排回放。

**仓库默认参数的复现结果：**在固定仿真种子和 24/6 天训练测试切分下，线性回归 MAE 为 4.22 kW，昨天同一时刻基线 MAE 为 12.61 kW；可移动排程相较固定排程的仿真购电碳排低 0.81%，总设备用电量保持相同。以上均为教学仿真结果，不代表真实减排。

→ [查看 MedEnergy 仓库](https://github.com/Ethan-39/medenergy)

## Supporting Projects

### Energy Carbon Scenarios

纯 Python 的小型情景计算器，练习从活动用电量和排放因子计算碳排与情景差异。当前示例因子只是占位输入，README 明确提示需替换为有出处的地区/年份数据。

→ [查看仓库](https://github.com/Ethan-39/energy-carbon-scenarios)

### Parking Lot Charging Environment

Gymnasium 环境入门练习，把车辆到达、充电桩、队列与电网负荷表达为状态、动作和奖励。

→ [查看仓库](https://github.com/Ethan-39/parking-lot-charging-env)

## 工作方式

- 先建立可解释的基线，再比较更复杂的模型。
- 训练/测试按时间或场景分开，报告模型误差和约束检查。
- 标注仿真数据、假设与不确定性，不把模型估算当成真实减排。
- 对医疗、实验室和生物安全相关任务，坚持人工复核，不让教学原型自动控制设备。

这些原型在 AI 编程辅助下搭建。我正在逐步复现和理解关键代码，并会把真实完成的修改与验证记录在仓库中。

## Team

两人团队：我的分工是数据、模型和技术原型；队友从生物科学角度提供场景约束、绿色价值和现场演示。项目仍在构建中，尚未取得学校或医院的实测数据验证。

## Contact

GitHub: [@Ethan-39](https://github.com/Ethan-39)


