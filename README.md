# KiraAI_model_config_query_plugin/模型配置查询助手

[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/znq19/KiraAI_model_config_query_plugin)

会话中查询 KiraAI 配置的默认模型名称，支持命令和白名单权限控制。

> **兼容性**：支持 KiraAI 2.x 与 3.0 全系列（含 v3.0.0-rc.1）。3.0 起模型引用值是内部稳定 ID，本插件（v1.0.1 起）会将其解析为人类可读的上游模型名再展示；解析失败原样回退，命令永远可用。

其实它最大的作用是可以让ai自己真实回答自己后台用的什么模型，但这仅代表KiraAI中配置的模型名称而不是用以验证模型来源真实性。
