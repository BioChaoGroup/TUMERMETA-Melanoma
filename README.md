# TUMERMETA-Melanoma
Effects of Immune checkpoint inhibitor based combination therapies on gut microbiome in advanced melanoma


# 黑色素瘤患者肠道微生物
------
2021/6/18

### **1. sampleinfo**

 - 医生给的最新信息表：`sampleInfo\医生更新的信息+徐礼钦给的信息表\粪便-PD-1抗体治疗前后标本2021-6-15更新.xls`
 - 目前统计的最新表格:`sampleInfo\sample information update 2021-6-15_remo2sam.xlsx`


### **2.最新分析内容**
**更新50个样本五组之间秩和检验差异菌：** p.value < 0.05 & Pct >= 20 & Occ.>0.2
> Result\03.Comparison\S50\bmc.sum.g5g2g.w.p50.sign.xlsx

**更新50个样本ICT与其他四组之间秩和检验所有菌
> Result/03.Comparison/S50/bmc.ict2o.w.p50.RData

对应脚本：
Assay\compare.significance.50.g5.Rmd

**更新50个样本五组之间R:NR秩和检验差异菌：** p.value < 0.05 & Pct >= 20 & Occ.>0.2
> Result\03.Comparison\S50\bmc.sum.g5.BE2.w.diff.P_0.05.50.csv
> Result\03.Comparison\S50\bmc.sum.g5.BE2.w.diff.P_0.01.50.csv

对应脚本：
Assay\compare.significance.50.mgs.Rmd


**更新77个样本五组之间R:NR秩和检验差异菌：** p.value < 0.05 & Pct >= 20 & Occ.>0.2
> Result\03.Comparison\bmc.sum.g5.BE2.w.diff.P_0.05.77.csv
> Result\03.Comparison\bmc.sum.g5.BE2.w.diff.P_0.01.77.csv

对应脚本：
Assay\compare.significance.77.mgs.Rmd

**更新ICT:ICT+ 7个样本之间比较
> 
