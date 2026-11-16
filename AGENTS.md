# 独立部署仓库约定

- 这里是 GameX 监考模拟器写实版的发布镜像；权威源码在 https://github.com/LeP-Ton/gamex-proctor-simulator/tree/codex/realistic 。
- 不直接修改游戏实现；在原仓库的对应版本分支开发、验证并更新需求记录，再同步固定提交。
- 本仓库仅部署自己的版本，不请求原仓库 main，不组合或覆盖另一版本。
- 来源追溯见 public/deployment.json；部署专用工作流与 README 属于镜像适配。
- npm ci 安装，npm test 核心测试，npm run build 生产构建；.github/workflows/pages.yml 完成本仓库独立 Pages 发布。
- 沟通、文档和新增注释使用中文。
