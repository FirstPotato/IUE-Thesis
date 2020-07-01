# 2020 中科院城市环境研究所学位论文 Latex 模板

## 模板下载

* 页面右边点击：**Clone or download -> Download Zip**


## 模板简介
 
 参考[ucasthesis](https://github.com/mohuangrui/ucasthesis) 国科大学位论文 LaTeX 模板修改而成。
 
### 已调整格式：

- 英文封面中的“By”改为小写“by”
- 图目录 / 表目录名称修改
- 添加目录部分图表标题前的“图”字与“表”字
- 增加了经费支持页面及使用说明

- 删去了参考文献中作者名字之间的空格



### 可手动调整格式：

标题默认分级从1开始，让小标题从(1)开始：

在\begin{enumerate}下方加入一行 `\renewcommand{\labelenumi}{(\theenumi)}`：

原标题使用：(标题从1, 2, 3开始)

```
\begin{enumerate}
	\item your text
\end{enumerate}
```

修改标题后：(标题从(1)，(2)，(3)开始)

```
\begin{enumerate}
	\renewcommand{\labelenumi}{(\theenumi)}%- 给标题添加括号
	\item your text
\end{enumerate}
```
