<h1>如何使用Github上传笔记</h1>

1. 建立本机与github的连接（SSH）
2. 创建Github仓库
3. 建立本地仓库，并与云端仓库相连接
4. 本地仓库操作完推送至云端仓库进行更新



<h5>操作步骤:</h5>

- git pull origin main ——每次上传前先把远端仓库拉到本地做校对

- git status ——查看仓库状态，哪些文件没有添加到缓存区，哪些文件修改删除了
- git add 文件 ——添加文件到缓存区等待上传到本地仓库
- git commit -m "更新了啥" ——从缓存区上传文件到本地仓库
- git push origin main ——更新云端仓库