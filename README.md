# Table-Detection
# 百度网盘AI大赛——表格检测

基于TableNet得到表格的四个拐角坐标，本项目附带一个可以直接提交的样例。
先用TableNet分析出各像素点属于表格内或外的概率，然后用resnet101回归得到四个角点的坐标。
