# k-Hessian 外域问题的数值与几何研究

本项目是博士研究的一部分，专注于外域 k-Hessian 方程的径向 ODE 数值求解、
几何曲率计算以及科学机器学习方法的探索。

## 目录结构
- `notebooks/`: 每日实验的 Jupyter Notebook（含详细注释）
- ## 主要结果
- Day 3-5: 外域 k-Hessian 径向 ODE 的 BDF 求解，验证了渐近行为 v(r)~r^{1/3}
- Day 9: Open3D 点云曲率可视化（PCA从散点云到离散平均曲率场的完整管线 + Poisson 重建）
- Day 12: 抛物面曲率的有限差分计算，收敛阶 ~2.0
- Day 13: PINN 求解 Poisson 方程，与有限差分解对比
- `src/`: 可复用的 Python 模块
- `data/`: 数值解数据
- `figures/`: 生成的图表

## 依赖
见 `requirements.txt`。主要依赖：
- Python 3.10+
- NumPy, SciPy
- Matplotlib
- Open3D (>=0.18)
- PyTorch (>=2.0)
