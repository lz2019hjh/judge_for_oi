# 比赛配置文件语法

大致和题目配置文件语法一样

### 标题

```
title 标题名称
```
**注意**：标题名称中如有空格或其他奇怪字符时，在标题两边加上双引号

### 题目

```
prob 1 题目名称
prob 2 题目名称
```

### 成绩倒出

```
result 文件类型选项  是否生成单独选手成绩选项 是否生成总成绩选项
```

文件类型选项：`csv`,`html`,`md`

是否生成单独用户成绩选项：`y`是,`n`否

是否生总成绩选项：`y`是,`n`否