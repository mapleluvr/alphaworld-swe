# Alphaworld-SWE

面向软件工程、工程文档与技术协作的 Skill。它依据任务要求和实际材料推进工作，让问题理解、代码实现与文档结构在生成和检验中成形，完成适合任务的交付。

few shot 所涉及的内容主要关于 SWE，因而称alphaworld-swe.

无意证明其优于某些工作流。

## 使用

```powershell
gh repo clone mapleluvr/alphaworld-swe
cd alphaworld-swe
pi install .
```

也可以直接按 Git 源安装，无需先克隆：

```powershell
pi install git:github.com/mapleluvr/alphaworld-swe
```

重新启动 Pi 或执行 `/reload`，通过 `/skill:alphaworld-swe` 显式调用。包清单只暴露 `skills/alphaworld-swe/`。

若工具只支持 Agent Skills，复制完整的 `skills/alphaworld-swe/` 并保留其 `references/` 即可。

## 内容

- [主文件](skills/alphaworld-swe/SKILL.md)：生成、检验与交付的工作指导。
- [写作、文档与 SWE 示例](skills/alphaworld-swe/references/examples.md)：保留文学、论述、凭证轮换与 CSV 导出案例，按当前工作选读。
- [文档工作情境](skills/alphaworld-swe/references/document-work-cases.md)：七个情境，涵盖用途、反馈、偏好和历史约束效力。
- [思想来路与具体化](skills/alphaworld-swe/references/philosophy-and-design.md)：承接 Alphaworld 的思想与写作取向，理解或修订本 skill 时选读。

主文保留足以开展工作的指导，附件用于需要进一步辨认的情境。
