# 你好，我是雷雨天

武汉轻工大学 · 软件工程 · 2027 届

我关注 AI 应用开发，喜欢把模型能力做成能实际使用的功能。这里展示修图智能体、业务 AI 助手和交互原型的成果与运行过程。

**[打开我的作品集 →](https://nigu666.github.io/ai-application-engineer-portfolio/)**

## AI 修图智能体

一个可以装在本机的中文 AI 修图工作台。从上传图片、编辑画布和图层，到确认 AI 计划、预览结果与导出，把一次修图的操作串起来。

[![AI 修图智能体实际运行画面](https://raw.githubusercontent.com/nigu666/ai-picture-editor/main/docs/images/workbench.png)](https://nigu666.github.io/ai-application-engineer-portfolio/?project=picture#picture-editor)

- **功能与实现**：React / Konva 画布、FastAPI 接口、LangGraph 规划、Redis 异步任务、本地图片处理与百炼模型接入。
- **我参与的部分**：需求取舍、模型方案选择、界面反馈、功能验收和开发推进；项目通过 AI 协作实现。
- **可以看到的过程**：读取画布 → 规划工具 → 人工确认 → 执行编辑 → 采用与导出。作品集提供五步运行图解，以及同一次本地翻转的前后画面对比。
- **可下载版本**：v0.1.0，Windows x64 + Docker Desktop 本机版。云端 AI 需要自行配置阿里云百炼密钥。

[项目源码](https://github.com/nigu666/ai-picture-editor) · [下载安装包](https://github.com/nigu666/ai-picture-editor/releases/latest) · [项目与运行图解](https://nigu666.github.io/ai-application-engineer-portfolio/?project=picture#picture-editor)

## 智慧水产 AI 助手

实习中参与的 Dify 工作流实践，围绕养殖知识问答、设备查询和水质分析，接入已有业务接口。

`自然语言 → 意图分类 → 知识检索 / 业务接口 → 结果处理`

我参与资料整理与 RAG 配置、参数提取、设备 ID 映射、JSON 返回处理和异常分支，以及移动端 AI 对话原型与现有 Vue2 页面的迁移适配。

作品集可以逐步查看**知识问答、设备查询、未找到设备、水质分析**四种分支，每种都有节点说明与真实运行截图。页面用于讲解已有实践，不会发起实时业务查询。

[查看处理分支与运行证据](https://nigu666.github.io/ai-application-engineer-portfolio/?project=dify#evidence)

## 业务交互与数据可视化

参与移动端、Web 管理端、数字孪生与数据驾驶舱原型的制作和迭代，呈现设备、生产、报修与监控等业务流程。交付内容包括可操作的页面原型、状态联动与可视化展示。

[Web 交互案例](https://nigu666.github.io/ai-application-engineer-portfolio/?project=web#web-detail) · [数据可视化案例](https://nigu666.github.io/ai-application-engineer-portfolio/?project=twin#twin-detail) · [更多交互原型](https://nigu666.github.io/zhihui-shuichan-jiaohu-yuanxing/)

## 联系我

[3077602965@qq.com](mailto:3077602965@qq.com) · [AI 应用开发作品集](https://nigu666.github.io/ai-application-engineer-portfolio/)
