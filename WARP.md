# Warp AI 优化配置

## 项目简介
这是一个课程资料相关的资源仓库，主要包含各类课程内容、学习资料和教学资源分享。

## 常用命令
```bash
# 查看最近更新的文档
ls -lt *.md | head -5

# 搜索特定内容
grep -r "关键词" *.md

# 统计文档数量
ls *.md | wc -l

# 查看文档结构
find . -name "*.md" -exec basename {} \; | sort
```

## Git 工作流
```bash
# 添加新文档
git add 202508.md
git commit -m "Add 202508 curriculum resources"
git push origin main

# 更新现有文档
git add .
git commit -m "Update curriculum documentation"
git push
```

## 文档约定
- 文档命名格式：YYYYMM.md
- 内容包含课程资料、学习资源、教学工具
- 每月更新相关内容

## 项目结构
```
curriculum/
├── README.md          # 项目介绍
├── 202505.md         # 2025年5月内容
├── 202506.md         # 2025年6月内容
├── 202507.md         # 2025年7月内容
├── 202508.md         # 2025年8月内容
└── WARP.md           # 本配置文件
```
