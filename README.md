# claude skills for Earth-Science

面向地质学/地层/沉积、地球物理/地震、遥感/地貌、GIS/空间分析的精选 Claude 科学技能集。

## 快速安装

将本仓库的 `.claude/skills` 复制到你的项目根目录下即可：

```
<your-project>/.claude/skills/
```

## 技能清单

地学相关
- geopandas
- pymatgen
- astropy

通用科研工具
- openalex-database
- literature-review
- scientific-writing
- citation-management
- markitdown
- scientific-slides
- document-skills
- matplotlib
- seaborn
- plotly
- statsmodels
- scikit-learn
- sympy
- networkx
- dask

## 使用方式

在提问中明确点名技能目录名，并给出目标、数据与输出格式即可。

示例：
“使用 `geopandas` 读取 `D:\data\faults.shp`，投影到 EPSG:32649，计算断层长度并输出 CSV。”

## 许可

本仓库内容源自 K-Dense-AI/claude-scientific-skills，遵循其原始许可证。
