# Figma 组件库搭建

`figma-component-library` 是一个可复用的 Codex Skill。它从当前项目的 Figma 定稿或既有组件库提取规范，搭建或补齐原生组件，再用真实场景验证实例、属性与变体。仓库只保存方法；颜色、字体、圆角等具体设计值由当前项目提供。

- [Skill 入口](.agents/skills/figma-component-library/SKILL.md)
- [搭建与自验手册](.agents/skills/figma-component-library/references/build-workflow.md)：七个阶段的 Figma 操作、产出和通过条件。
- [资产准入与复用验收](.agents/skills/figma-component-library/references/asset-contract.md)：原生组件、属性绑定与实例复用的验收要求。
- [企业后台变体与场景](.agents/skills/figma-component-library/references/b2b-variants.md)：基础规范、变体覆盖、场景延展与分批验收。
- [排障手册](.agents/skills/figma-component-library/references/troubleshooting.md)：常见问题的定位、修复、复验和预防。

在 Codex 中打开此仓库，提供目标 Figma 定稿链接和允许写入的组件页，然后调用：

> 用 `$figma-component-library` 按这个 Figma 定稿搭建组件库，优先复用已有资产，完成自验和修复后一次交付。
