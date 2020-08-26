# git-learning
## 创建git新仓库
```
# 初始化git新仓库
git init
# 创建一个README文件
echo "# git-learning" > README.md
# 添加README到缓存区
git add README
# 提交改动到HEAD
git commit -m "first git commit"
# 本地仓库连接到远程服务器
git remote add origin https://github.com/Fei-Liu/git-learning.git
# 将变更提交到远程分支
git push origin master
```
## 检出git仓库的某个分支
```
# 从服务器检出分支默认是master分支
git clone https://github.com/Fei-Liu/git-learning.git
# 检出develop分支代码
git clone -b develop https://github.com/Fei-Liu/git-learning.git
```