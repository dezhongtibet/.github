# Organization issue templates

本仓库维护 dezhongtibet 组织的公共 Issue 模板, 供 Tunmo 等未设置专用模板的仓库使用.

## 模板

| 模板 | 用途 | 内容 |
|---|---|---|
| Feature / Improvement | 新增功能、已有功能改进、用户体验优化 | Goal / Scope / Acceptance / Related |
| Task | 文档、重构、测试、构建及其他工程维护 | Goal / Scope / Acceptance / Related |
| Bug | 实际行为不符合预期的异常 | Actual / Expected / Reproduction / Environment / Evidence / Safety Check |

Feature / Improvement 与 Task 的 Goal、Scope、Acceptance 必填, Related 选填.
Bug 保留现有的复现、环境、证据和敏感数据检查要求.

体验改进使用 Feature / Improvement; 交互异常使用 Bug. Refactor 表示外部行为不变的内部代码结构调整, 使用 Task.
文档和重构任务无需单独的表单, 可按需要使用仓库的 docs、refactor、ux 或 performance 标签.

## 维护方式

公共模板位于 [.github/ISSUE_TEMPLATE](.github/ISSUE_TEMPLATE), 修改本仓库默认分支即可更新继承它们的仓库.

GitHub 要求公共模板仓库保持公开. 公共模板可供同一组织的公开及私有仓库继承.
消费仓库如保留自己的 Issue 模板或 ISSUE_TEMPLATE/config.yml, 会覆盖整套公共模板, 不会与公共模板合并.
仓库中的 workflow 和 PR 模板可以继续独立维护.

具体规则见 [GitHub 默认社区文件说明](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).
