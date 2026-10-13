# Readock 离线句子模型下载

本仓库仅提供 Readock 两份固定模型的公开下载，供 Android 在书库未提供模型时按用户操作下载。应用源码在独立私有仓库维护。

| 模型 | 文件字节数 | 原始模型 |
|---|---:|---|
| Qwen3.5-0.8B 轻量版 | 529297408 | https://huggingface.co/Qwen/Qwen3.5-0.8B/tree/2fc06364715b967f1860aea9cf38778875588b17 |
| Qwen3.5-2B 标准版 | 1274396672 | https://huggingface.co/Qwen/Qwen3.5-2B/tree/15852e8c16360a2fea060d615a32b45270f8a8fc |

原作者 Qwen Team，Apache-2.0。Readock 使用固定 llama.cpp b11429/d81235049384534c167caea52b85a694f6103d14 转换为仅文本、无视觉与 MTP 的 Q4_K_M GGUF，未训练或微调。原许可及两份 NOTICE 随附件提供。

模型文件从 models-2026.10.11-v1 Release 下载；SHA256SUMS.txt 给出冻结摘要，Android 完整校验并实际加载自检后才安装。模型文件与原本地量化产物完全相同。

解释质量尚未达到项目目标；ARM64 真机运行、手机性能与其它系统范围尚未验收。公开下载不改变这些结论。
