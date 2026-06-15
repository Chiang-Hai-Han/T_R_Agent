# T_R_Agent (教研综合 Agent)

教研综合 Agent，通过 Coze 工作流 API 调用实现自动化教研任务。

## 使用方法

`Workflow` 文件是调用 Coze 工作流引擎的 Python 脚本模板。

### 环境准备

```bash
pip install cozepy
```

### 配置

编辑 `Workflow` 文件，填入：

1. `coze_api_token` — Coze personal access token
2. `workflow_id` — Coze 工作流 ID（从网页链接末尾获取）

### 运行

```bash
python Workflow
```

## 作者

**海瀚（Chiang-Hai-Han）**

## License

MIT
