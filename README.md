# One-Bit-Value-Comparator-Integrated-Circuit-Design
## （本库为本人课程设计备份）
# 设计要求
1. 对电路进行仿真验证；
2. 根据所用的工艺，选取合理的模型库；
3. 选用以lambda为单位的设计规则
4. 全手工、层次化设计版图；
5. 达到指导书提出的设计指标要求；
6. 用Multisim进行电路的前期功能设计与仿真。
7. 用CMOS设计出合理且切实可行的一位数值比较器
8. 使用L-Edit进行版图绘制，并进行检测。
## 一位数值比较器的真值表
<img src="https://github.com/LINliulin/One-Bit-Value-Comparator-Integrated-Circuit-Design/blob/main/%E5%9B%BE%E7%89%87%E9%A2%84%E8%A7%88/%E4%B8%80%E4%BD%8D%E6%95%B0%E5%80%BC%E6%AF%94%E8%BE%83%E5%99%A8%E7%9C%9F%E5%80%BC%E8%A1%A8.png" height="50%" width="50%">
### 本次实现的一位数值比较器是Y（A=B）

# 一位数值比较器的仿真电路图设计
本设计使用Multisim（版本为14.0）进行电路仿真。
<img src="https://github.com/LINliulin/One-Bit-Value-Comparator-Integrated-Circuit-Design/blob/main/%E5%9B%BE%E7%89%87%E9%A2%84%E8%A7%88/%E4%B8%80%E4%BD%8D%E6%95%B0%E5%80%BC%E6%AF%94%E8%BE%83%E5%99%A8%E9%80%BB%E8%BE%91%E7%94%B5%E8%B7%AF%E5%9B%BE.png" height="70%" width="70%">
# L-edit版图设计
本设计使用L-edit进行版图绘制，包括NMOS、PMOS、二输入与非门、二输入或非门、非门，直至一位数值比较器。
<img src="https://github.com/LINliulin/One-Bit-Value-Comparator-Integrated-Circuit-Design/blob/main/%E5%9B%BE%E7%89%87%E9%A2%84%E8%A7%88/%E4%B8%80%E4%BD%8D%E6%95%B0%E5%80%BC%E6%AF%94%E8%BE%83%E5%99%A8%E7%89%88%E5%9B%BE.png" height="70%" width="70%">
