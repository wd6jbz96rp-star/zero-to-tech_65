# 贡献指南

## 提交流程

1. 从 `main` 切一个功能分支：`git switch -c feature/功能名`
2. 小步提交，提交信息用「类型: 说明」，类型取 `feat` / `fix` / `docs` / `chore`
3. 推分支并发起 Pull Request，说明改了什么、怎么验证
4. 至少一位同学 review 后再合并到 `main`

## 代码约定

- 前端组件放在 `components/`，页面放在 `app/`
- 后端接口放在 `backend/`，配置一律走 `.env`，不要提交密钥
- 新增依赖请同步更新 `package.json` 或 `requirements.txt`

## 提 Issue

- 报问题请附复现步骤、期望结果、实际结果
- 提需求请说明使用场景，不要只写「加个功能」
