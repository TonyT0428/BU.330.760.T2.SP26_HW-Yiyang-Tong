# BU.330.760.T2.SP26 — GAI 作业仓库

本仓库用于存放 **BU.330.760** 课程中与 **生成式 AI（GAI）** 相关的作业与草稿材料（如 `assistant_draft.md`、期末/定稿类 Markdown 等），便于版本管理与提交。

## 使用的 Git 操作

在本地 `GAI` 目录中完成初始化与首次推送时，主要使用了：

- `git init`：在本文件夹创建独立仓库  
- `git branch -M main`：将默认分支命名为 `main`  
- `git add` / `git commit`：暂存并提交文件  
- `git remote add origin …`：添加 GitHub 远程 `TonyT0428/BU.330.760.T2.SP26_HW-Yiyang-Tong`  
- `git push -u origin main`：将 `main` 推送到远程并设置上游跟踪  

之后日常更新还会用到 `git add`、`git commit`、`git push` 等。

## Commit 历史

当前仓库历史较短，完整 `git log` 如下：

```
commit a0e388a76fa5fa452a5519f75b8f4ccf498a924e
Author: Tequila <49821966+TonyT0428@users.noreply.github.com>
Date:   Mon Mar 30 15:24:36 2026 -0400

    Add README with repo purpose and Git notes
    
    Made-with: Cursor

commit 8646cff0f781d9671bc3dc486b7f985c4cbbb7c3
Author: Tequila <49821966+TonyT0428@users.noreply.github.com>
Date:   Mon Mar 30 15:22:53 2026 -0400

    Add GAI homework markdown files
    
    Made-with: Cursor
```

**一行摘要**

- `a0e388a` — **Add README with repo purpose and Git notes**
- `8646cff` — **Add GAI homework markdown files**（初始提交：作业相关 Markdown 与 `.gitignore`）
