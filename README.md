# ZiqiangStudio GitHub defaults

本仓库提供组织级默认协作文件：Pull Request 模板、Issue 表单、贡献约定和安全问题报告说明。

所有未自定义这些文件的组织仓库会优先使用这里的默认版本。仓库已有同名文件时，以仓库自己的文件为准。

安全扫描工作流位于 `workflow-templates/security-scan.yml`。它调用组织统一的可复用工作流，使用固定 commit 的 Gitleaks 和 Trivy 扫描提交中的密钥、依赖和常见配置问题。GitHub 不会自动把工作流复制到已有仓库；新仓库或现有仓库需要从 Actions 的工作流模板添加一次。

组织仓库默认分支为 `main`，变更通过 Pull Request 合并，并使用 squash merge。
