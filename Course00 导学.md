## git操作

#### create a new repository on the command line

echo "# GeekAlgorithm" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:WRuiyan/GeekAlgorithm.git
git push -u origin main

#### push an existing repository from the command line

git remote add origin git@github.com:WRuiyan/GeekAlgorithm.git
git branch -M main
git push -u origin main

## 关于刷题：

1、刷题的两个极端的误区：完全边看题解边刷题/坚决不看题解完全死抠——》将计划的刷题时间分配为相等时长的三部分：自己想+看优质题解+自己实现

2、分类刷题：初学的时候不要去刷综合题，要分类刷；后期再综合刷——》**三刷五步训练法**

3、死背程序本身是无用的——》解题靠**模型**驱动

