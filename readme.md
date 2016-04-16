# readme

# 如何创建和合并分支并pull request
- 创建分支dev
 - git checkout -b dev 创建并切换分支
 - git branch 查看当前分支（dev）
 - 修改readme.md
 - 查看是否真的修改 cat readme.md
 - git add readme.md
 - git commit -m "注释"
 - git checkout master切回主分支
 - git merge dev合并分支
 - git branch -d dev删除
 - git push推送
 - 总结：
   - 查看分支：git branch 
   - 创建分支：git branch name
   - 切换分支：git checkout name
   - 创建+切换分支：git checkout –b name
   - 合并某分支到当前分支：git merge name
   - 删除分支：git branch –d name

  ![r](http://www.admin10000.com/UploadFiles/Document/201410/27/20141027155323880647.PNG)
  ![f](http://www.admin10000.com/UploadFiles/Document/201410/27/20141027155323504876.PNG)
## 如何pull request
  - 找到你修改的的项目
  - ![vd](https://help.github.com/assets/images/help/pull_requests/pull-request-review-create.png)
  - 等待管理员合并