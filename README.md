# boss_job_analysis项目说明

code以及**分析步骤**以及**结论**见"job_analysis.ipynb"

原始data在“boss.csv”

## 项目目录
 - 导包与数据
- 数据清洗
  - 取数
  - 将薪水转化为数值
  - 根据“岗位详情”，修正“技能标签”列
  - 处理冗杂的“行业领域”列
- 数据分析
  - 关于岗位需求量
  - 关于薪资
    - 不同学历的薪资分析
    - 不同城市的薪资分析
    - 不同行业领域的薪资分析
      - 不同行业领域不同工作经验要求下的薪资分析
    - 不同公司的薪资分析
  - 关于技能要求
    - 不同的公司规模对技能的要求比例分析
    - 实习与全职的技能要求
    
## 项目介绍
本项目旨在对BOSS直聘平台上“数据分析”岗位进行全方位分析，为数据分析工作者提供一份求职指南。具体步骤如下：
1. 从原始数据集中提取出数据分析的非实习岗位，对薪资，行业领域，技能标签列的数据进行清洗；
2. 分析出不同城市、不同行业领域的数据分析岗位需求量的差异；
3. 在学历、城市、行业领域等五个维度及其交叉维度下对薪资水平进行分析，并通过柱形图、箱线图、热力图对薪资水平的可视化展现；
4. 分析了不同规模企业对数据分析各项技能的要求比例，以及实习与全职工作的技能要求差异

  
