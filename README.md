<div align="center">

# Ethan-39

### 🏅 AI Certifications
<p align="center">
  <img src="./agent.png" width="30%" />
  <img src="./prompt.png" width="30%" />
  <img src="./finetune.png" width="30%" />
</p>

---

### 💻 Tech Stack
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/LLM-Application-blueviolet?style=for-the-badge" />
</p>

**AI for Green · Energy Forecasting · Carbon Management**

正在学习 Python 和机器学习，并尝试把它们用于可持续发展问题。
该项目为试探性的学习和模拟原型

[旗舰项目：MedEnergy](https://github.com/Ethan-39/medenergy) · [支撑项目](#supporting-projects)

<a href="https://github.com/Ethan-39/medenergy"><img src="https://raw.githubusercontent.com/Ethan-39/medenergy/main/assets/dashboard-overview.png" alt="MedEnergy interactive dashboard preview" width="760"></a>

</div>

## 当前方向

关注能源预测怎样与碳核算和实际运行约束结合。与一位生物科学专业队友探索实验室/医疗场景下的绿色能源管理。当前作品以教学仿真为主，重点是把数据来源、比较基线、约束和结果边界交代清楚。

## Projects

### MedEnergy · 旗舰项目

能源预测与碳感知排程教学原型。包含交互看板、时间顺序测试集、朴素预测基线、模拟批任务约束和费用/碳排回放。

**仓库默认参数的复现结果：**在固定仿真种子和 24/6 天训练测试切分下，线性回归 MAE 为 4.22 kW，昨天同一时刻基线 MAE 为 12.61 kW；可移动排程相较固定排程的仿真购电碳排低 0.81%，总设备用电量保持相同。以上均为教学仿真结果，不代表真实减排。

→ [查看 MedEnergy 仓库](https://github.com/Ethan-39/medenergy)

## Supporting Projects

### Grid Carbon Signal

可复现的合成电网碳强度条件预测练习：按时间切分训练与测试，和星期-小时均值基线比较，并列出次日低碳强度候选时间窗。固定种子仿真 MAE 为 8.60，对照基线为 19.28 gCO2e/kWh；未来风光与负荷输入由仿真器预先给定，结果不来自真实电网数据，也不代表减排。

→ [查看仓库](https://github.com/Ethan-39/grid-carbon-signal)

### BioLab Cold-Chain Watch

冷链遥测教学回放，覆盖缺失数据、温度越界和异常用电，并只提示人工核查。固定仿真测试场景的点级 precision/recall 均为 1.00；阈值只是占位，原型不连接、不控制实验室设备，也不代表实验室适用性。

→ [查看仓库](https://github.com/Ethan-39/biolab-cold-chain-watch)

### Energy Carbon Scenarios

纯 Python 的小型情景计算器，练习从活动用电量和排放因子计算碳排与情景差异。当前示例因子只是占位输入，README 明确提示需替换为有出处的地区/年份数据。

→ [查看仓库](https://github.com/Ethan-39/energy-carbon-scenarios)

### Parking Lot Charging Environment

Gymnasium 环境入门练习，把车辆到达、充电桩、队列与电网负荷表达为状态、动作和奖励。

→ [查看仓库](https://github.com/Ethan-39/parking-lot-charging-env)

<details>
<summary>其他能源与碳管理演示项目</summary>

- [Building Energy Benchmark](https://github.com/Ethan-39/building-energy-benchmark)：仿真建筑能耗强度与简化天气归一化比较。
- [Solar Self-Consumption Sim](https://github.com/Ethan-39/solar-self-consumption-sim)：比较光伏自用与可移负荷情景。
- [Campus Carbon Budget](https://github.com/Ethan-39/campus-carbon-budget)：用占位因子展示校园碳预算进度。
- [Demand Response Evaluator](https://github.com/Ethan-39/demand-response-evaluator)：评估合成需求响应事件并报告基线误差。
- [Battery Dispatch Sim](https://github.com/Ethan-39/battery-dispatch-sim)：带功率、效率和 SoC 约束的储能削峰模拟。
- [Scope 2 Emissions Ledger](https://github.com/Ethan-39/scope2-emissions-ledger)：演示 Scope 2 两种记账口径，非合规盘查。
- [Energy Data Quality Audit](https://github.com/Ethan-39/energy-data-quality-audit)：检查能源时序的缺失、重复、间隔异常和极端值。
- [Green Lab Energy Audit](https://github.com/Ethan-39/green-lab-energy-audit)：根据虚构设备清单估算实验室能耗与排放。
- [Occupancy Energy Anomaly Detector](https://github.com/Ethan-39/occupancy-energy-anomaly-detector)：用占用量校正合成能耗基线并筛查残差异常。
- [Carbon Cost Pareto](https://github.com/Ethan-39/carbon-cost-pareto)：展示费用、碳排和舒适度之间的情景权衡。

以上为合成或示例数据的教学原型，不代表实测减排、真实设施验证或可直接用于运行决策。

</details>

## 工作方式

- 先建立可解释的基线，再比较更复杂的模型。
- 训练/测试按时间或场景分开，报告模型误差和约束检查。
- 标注仿真数据、假设与不确定性，不把模型估算当成真实减排。
- 对医疗、实验室和生物安全相关任务，坚持人工复核，不让教学原型自动控制设备。

这些原型在 AI 编程辅助下搭建。我正在逐步复现和理解关键代码，并会把真实完成的修改与验证记录在仓库中。

## Team

两人团队：我的分工是数据、模型和技术原型；队友从生物科学角度提供场景约束、绿色价值和现场演示。项目仍在构建中，尚未取得实测数据验证。

## Contact

GitHub: [@Ethan-39](https://github.com/Ethan-39)


