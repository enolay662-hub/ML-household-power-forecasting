# 家庭电力消耗多变量时间序列预测课程项目

本项目为机器学习课程期末实验项目，旨在利用历史用电和天气数据进行中长期的多变量电力负荷预测。

## 1. 文件结构
* `code.ipynb`：完整可运行的代码（包含数据预处理、模型定义、训练、绘图与指标统计）。
* `household_power_consumption.txt`：原始分钟级家庭电力数据。
* `climate_75_PARIS-MONTSOURIS_2006-2010_required_columns.csv`：Paris-Montsouris 气象观测数据。

## 2. 快速开始
1. 安装所需依赖库：
   ```bash
   pip install torch pandas numpy matplotlib scikit-learn jupyter
   ```
2. 启动 Jupyter 并运行 `python_optimized.ipynb` 中的所有单元格即可。
