Gemini 3 pro 开发  
作者 推特 @0xsakura666 欢迎私信交流

## 环境配置（安全敏感）
- 在 `.env.local` 配置以下变量，不要在仓库中提交真实密钥：
  - `VITE_GEMINI_API_KEY=你的模型密钥`
  - `VITE_GEMINI_API_BASE_URL=模型接口基础地址（例如 https://api.openai.com/v1 或自建网关）`
- 未配置密钥或基础域名时，前端会阻止请求并提示缺失配置。
