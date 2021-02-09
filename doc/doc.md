### git 操作

---

1. **切换远程分支**

   ​	`git checkout -b 本地分支名 origin/远程分支名`

2.  **合并远程分支**

   ​	`git merge origin/远程分支名`

3.  **取消上次的merge**

   ​	`git reset --hard`
   
4. **合并某一次提交记录**

   `git cherry-pick ${commitLog}`

5. **提交本地分支至远程分支**

   `git push origin ${本地分支}:${远程分支}`

