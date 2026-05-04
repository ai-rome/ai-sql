# ai-sql
让 AI 充当一个既懂业务、又懂代码、还具备严谨逻辑的“中间人”

Intent Analysis (意图分析): AI 解析用户自然语言。Schema Retrieval (元数据召回): SchemaManager 提取相关的表结构描述。SQL Generation (生成): 结合 Prompt 和 Schema 生成 SQL。Self-Correction Loop (自愈循环):执行 SQL。若捕获 SQLException -> 将报错信息发送回 AI -> AI 修正 -> 再次执行。
