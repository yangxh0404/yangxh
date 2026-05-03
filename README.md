# yangxh
读书实践
##一、学习资料
学习视频：https://www.bilibili.com/video/BV1hS4y1S7wL/?spm_id_from=333.337.search-card.all.click&vd_source=3693c8eb3a0bfeff7aa137bc1dfd40aa
##二、三次提交
```bash
# 进入仓库目录
cd yangxh
# 创建代码文件
 calculator.py README.md
 第1次提交：Initial commit
建立项目骨架，README 说明项目用途。

第2次提交：Add addition and subtraction functions
增加具体功能，提交信息清晰说明做了什么。

第3次提交：Add multiplication and user input
增加乘法和交互功能

##四、遇到的问题及解决方法
问题1：git push 报错 403 或 Authentication failed
解决：GitHub Settings → Developer settings → Personal access tokens → Tokens (classic)
Generate new token，勾选 repo 权限
复制 token，推送时用户名填 GitHub 用户名，密码填 token
问题2:git push 时报错 failed to push some refs to remote
解决：拉取远程内容并合并（推荐）

##五、学习心得
1. 提交信息很重要：清晰规范的提交说明帮助自己和他人理解修改意图，是良好协作的基础。
2. 冲突不可怕：Git 的冲突标记很清晰，只要冷静分析、手动选择，就能顺利解决。
