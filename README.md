# gitlearn

abc d

1. 切换分支时,未追踪的文件是否受影响: 不受影响

```bash
git checkout -b dev
# 创建并切换到dev分支

git branch
# 查看分支

git branch dev
# 创建dev分支但不切换
```
# 添加一些新东西

2. 分支合并

```bash
# 在dev分支进行开发,开发完成后,合并入主分支
git checkout main
# 切换到主分支

git merge dev

```

main分支进行了更改,但是未提交,此时创建dev分支并切换过去,mian分支不变,修改归于dev分支