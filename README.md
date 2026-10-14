# Alphaworld-SWE

面向软件工程、工程文档与技术协作的 Pi skill。它依据任务要求和实际材料推进工作，让问题理解、代码实现与文档结构在生成和检验中成形，完成适合任务的交付。

SWE 专门化限定的是任务范围，不改变 Alphaworld 的思想来路。原有的写作原则与表达取向，同样用于工程内容和本 skill 自身的创作与修订。

这是仍需实际任务检验的设计版本，不宣称已经证明优于其他写法或无 skill 的运行。

## 使用

```powershell
gh repo clone mapleluvr/alphaworld-swe
cd alphaworld-swe
pi install .
```

重新启动 Pi 或执行 `/reload`，通过 `/skill:alphaworld-swe` 显式调用。包清单只暴露 `skills/alphaworld-swe/`。

若工具只支持 Agent Skills，复制完整的 `skills/alphaworld-swe/` 并保留其 `references/` 即可。

## 内容

- [主文件](skills/alphaworld-swe/SKILL.md)：生成、检验与交付的工作指导。
- [写作、文档与 SWE 示例](skills/alphaworld-swe/references/examples.md)：保留文学、论述、凭证轮换与 CSV 导出案例，按当前工作选读。
- [文档工作情境](skills/alphaworld-swe/references/document-work-cases.md)：七个情境，涵盖用途、反馈、偏好和历史约束效力。
- [思想来路与具体化](skills/alphaworld-swe/references/philosophy-and-design.md)：承接 Alphaworld 的思想与写作取向，理解或修订本 skill 时选读。

主文保留足以开展工作的指导，附件用于需要进一步辨认的情境，不要求每个任务读完所有材料。

## 来源与验证范围

本包由 Alphaworld 的 SWE 候选整理而来，候选稿、评议记录和运行审计留在来源仓库，不随本仓库发布；运行本 skill 不依赖那些记录。

其中实际计划改写在本包中使用功能性称谓概述，而不是原文逐字引述。原始对照与审计只支持发生过该项文本变化，不证明后续执行收益。示例及七个文档情境的证据状态在各附件中说明，不把设定内的反馈当成真实运行结果。

本仓库没有运行时依赖、脚本、凭证或会话日志。对照运行时，应固定任务输入与实际模型参数，记录主文、附件读取情况、生成文件和使用结果。不要默认同时加载两个版本；同名任务在不同上下文中的差异，不能单独归因于某一句提示词。
