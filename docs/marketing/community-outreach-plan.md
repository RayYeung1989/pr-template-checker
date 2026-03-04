# GitHub Actions 工具与 AI Text Processor 社区推广计划

## 目标产品

- **AI Text Processor v2.2**：16 功能的文本处理工具
- **GitHub Actions 工具链**（5 个）：pr-size-labeler、pr-stale-detector、pr-auto-merge、pr-description-enforcer、pr-review-assignor

## 目标社区

### 1. Reddit

**相关子版块**

- r/opensource（40 万会员）：开源项目推广
- r/programming（560 万会员）：程序员社区
- r/webdev（170 万会员）：Web 开发
- r/github（5 万会员）：GitHub 专门社区
- r/SideProject（25.3 万会员）：侧项目分享
- r/productivity（110 万会员）：生产力工具

**发布时机**

- 美国东部时间上午 9 点至下午 5 点
- 建议先积累一定 karma 再发布

### 2. Indie Hackers

**适合原因**

- 开发者社区，庆祝发布和里程碑
- 重视透明度和学习
- 通常会互相支持

**发布时机**

- 周二至周四上午
- 先参与其他发布帖建立关系

### 3. Hacker News

**适合性评估**

- **高度适合**：GitHub Actions 工具面向开发者
- 技术性产品，符合 HN 口味
- 需要准备技术细节

**发布时机**

- 美国东部时间早上 7-10 点
- 使用 Show HN 格式

### 4. 其他平台

- Dev.to：开发者博客平台
- Hashnode：开发者社区
- r/Artificial（140 万会员）：AI 产品

## 发布计划

### 第一阶段：预热（1-2 周）

- [ ] 在 r/github、r/programming 评论区参与讨论
- [ ] 在 Indie Hackers 关注其他发布帖
- [ ] 积累 Reddit karma（至少 50+）

### 第二阶段：发布日

| 时间 | 平台 | 社区/子版块 |
|------|------|-------------|
| 14:00 UTC | Reddit | r/github |
| 16:00 UTC | Reddit | r/opensource |
| 18:00 UTC | Indie Hackers | 主论坛 |
| 20:00 UTC | Hacker News | Show HN |

## 发布草稿

### Reddit r/github

```
标题：开源了 5 个 GitHub Actions 自动化工具，帮你搞定 PR 管理

大家好！

我开源了一套 GitHub Actions 工具链，专门解决 PR 管理中的繁琐问题：

**解决的问题：**
- 手动给 PR 贴标签浪费时间
- 过期 PR/Issue 无人处理
- 重复分配审阅者
- PR 描述不规范

**5 个工具：**
1. pr-size-labeler - 自动按代码量贴标签
2. pr-stale-detector - 检测过期 PR/Issue
3. pr-auto-merge - 自动合并符合条件的 PR
4. pr-description-enforcer - 强制 PR 描述规范
5. pr-review-assignor - 自动分配审阅者

全部免费开源，已发布 v1.0.0：

GitHub: https://github.com/rayyeung1989

欢迎试用和反馈！
```

### Reddit r/opensource

```
标题：给开发者的一套 PR 自动化工具套装

Hey r/opensource！

我开发了一套 GitHub Actions 工具，帮助团队自动化 PR 管理流程。

**功能包括：**

- 自动标签（按 PR 大小）
- 过期检测（自动提醒/关闭）
- 自动合并（配置条件）
- 描述规范（强制模板）
- 审阅分配（轮询/随机）

**为什么做这个：**
作为开发者，受够了手动管理 PR 的繁琐，自动化后效率提升明显。

**现状：**
- 5 个独立 action，可单独使用
- 全部开源，MIT 许可证
- 已在 GitHub Marketplace 上架

有兴趣的可以看看：
https://github.com/rayyeung1989

欢迎 star、fork、提 issue！
```

### Indie Hackers

```
标题：开源了 5 个 GitHub Actions 工具，自动化你的 PR 管理流程

Hey IH 社区！

今天分享我开发的 GitHub Actions 工具链，帮助团队自动化 PR 管理。

**开发背景：**
作为全职开发者 + AI 创业团队，我需要同时维护多个项目。手动管理 PR 标签、分配审阅者、处理过期 PR 浪费了大量时间。于是有了这套工具。

**5 个工具：**

- pr-size-labeler：按代码量自动贴标签
- pr-stale-detector：检测并处理过期 PR/Issue
- pr-auto-merge：满足条件自动合并
- pr-description-enforcer：强制 PR 描述模板
- pr-review-assignor：自动分配审阅者

**关键数据：**
- 开发时间：3 个月
- 代码量：每个 action 约 200-500 行
- 已发布：v1.0.0
- 平台：GitHub Marketplace

**学到的教训：**
1. 单一职责的 action 更受欢迎
2. 配置越简单越好
3. 文档和 examples 是关键

**下一步：**
- 添加更多触发条件
- 考虑付费高级功能

**寻求反馈：**
- 这些工具对你有用吗？
- 有什么功能缺失？

GitHub: https://github.com/rayyeung1989

欢迎评论交流！
```

### Hacker News Show HN

```
标题：Show HN: 5 个 GitHub Actions 自动化工具

我开发了 5 个 GitHub Actions 工具，帮助团队自动化 PR 管理流程：

- pr-size-labeler：按代码量自动贴标签
- pr-stale-detector：检测过期 PR/Issue
- pr-auto-merge：满足条件自动合并
- pr-description-enforcer：强制 PR 描述模板
- pr-review-assignor：自动分配审阅者

技术细节：
- 每个 action 独立，可单独使用
- 使用 TypeScript + Jest
- 配置通过 action.yml 传递
- 已在 Marketplace 上架

想听听大家的反馈，特别是：
- 还有哪些 PR 管理痛点可以自动化？
- 配置方式是否足够简单？

GitHub: https://github.com/rayyeung1989
```

## 行动清单

### 发布前

- [ ] 在目标子版块积累 karma（至少 20+ 评论）
- [ ] 准备各平台账号
- [ ] 测试所有工具确保正常工作

### 发布当天

- [ ] Reddit r/github 发布（第一优先级）
- [ ] Reddit r/opensource 发布
- [ ] Indie Hackers 发布
- [ ] Hacker News Show HN 发布
- [ ] 监控所有评论并快速回复

### 发布后

- [ ] 一周后发布结果帖
- [ ] 感谢所有反馈
- [ ] 根据反馈迭代产品

## 关键提醒

1. **真实性优先**：不夸大功能，如实描述
2. **快速响应**：30 分钟内回复所有评论
3. **接受批评**：负面反馈是改进机会
4. **持续参与**：发布后继续保持活跃
