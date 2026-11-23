# Figma 组件库搭建

`figma-component-library` 是一个可复用的 Codex Skill。它按目标 Figma 设计稿提取规范、复用或搭建组件库、配置属性和变体，再用真实业务实例做布局和渲染验收。流程包含自行修复与复测，普通验收无需交回使用者。

- [Skill 入口](.agents/skills/figma-component-library/SKILL.md)
- [搭建与自验手册](.agents/skills/figma-component-library/references/build-workflow.md)：七个阶段的 Figma 操作、产出和通过条件。
- [排障手册](.agents/skills/figma-component-library/references/troubleshooting.md)：常见问题的定位、修复、复验和预防。

在 Codex 中打开此仓库，提供目标 Figma 定稿链接和允许写入的组件页，然后调用：

> 用 `$figma-component-library` 按这个 Figma 定稿搭建组件库，优先复用已有资产，完成自验和修复后一次交付。
