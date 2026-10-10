# 能力与资源入口

帮助形成检索方向，不是完整资料库或固定推荐。未列领域自行检索，不要求命中特定项目。下列链接于 2026-10-10 通过一手文档或仓库核对；未在用户工程实测，选型时复核能力、许可与运行条件。

## 视觉反馈交给代码 Agent
检索词：visual feedback for coding agents、element to source mapping、annotation context、object picking。
- [Agentation](https://github.com/benjitaylor/agentation)：页面元素/区域反馈、位置与选择器、结构化输出和 MCP。看 README 的输出与接入方式；React/DOM 不直接等于离线视频对象识别。仓库标注 PolyForm Shield，不默认为宽松许可复制。
- [React Grab](https://github.com/aidenybai/react-grab)：元素选择与源码上下文，查看 primitives 接口示例。可参考拾取与源码关联；网页/React 能力不直接适配 Python 渲染图像。
先检查工程对象、图层、组件或源码位置，再决定是否需要视觉算法。

## 代码动画、时间与编辑对象
检索词：code animation scene graph inspector、timeline visual editing source code、render object id picking。
- [Motion Canvas](https://github.com/motion-canvas/motion-canvas)：代码动画与预览；[2D 编辑器入口](https://github.com/motion-canvas/motion-canvas/blob/main/packages/2d/src/editor/index.ts) 展示节点检查、场景图与覆盖层。参考对象结构，不据此要求迁移。
- [Remotion Studio 交互文档](https://github.com/remotion-dev/remotion/blob/main/packages/docs/docs/studio/interactivity.mdx)：视觉操作与代码同步、序列及关键帧。核对可编辑条件，不当作用户渲染器已有能力。

## 只有图像或视频像素时
检索词：text grounded object detection、promptable video segmentation、video annotation export。
- [Grounding DINO](https://github.com/IDEA-Research/GroundingDINO)：文本关联对象检测，提供定位候选，不负责编辑意图或审美。
- [SAM 2](https://github.com/facebookresearch/sam2)：图像/视频分割，研究区域与跨帧定位，需验证素材和成本。
- [Label Studio](https://github.com/HumanSignal/label-studio)：标注与导出，可先研究现成表达方式；不等于自动编辑器。

## 设计资料与技能组织
- [UI/UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)：数据、检索脚本、宿主模板分离；参考按需检索结构，UI 风格不直接变成视频审美标准。
- [OpenAI cloudflare-deploy](https://github.com/openai/skills/blob/main/skills/.curated/cloudflare-deploy/SKILL.md)：决策入口选择参考资料；借鉴导航，不复制与宿主冲突的执行指令。

## 其他领域与维护
按“整项任务的工具 → 相邻能力的库与实现 → 官方文档、示例、关键接口”继续检索。把当前证据记在项目中，不要求每轮更新本页。未来维护共享索引时，保留能力、用途、局限、阅读入口和核对日期；不自动加入私有项目或未经验证的推荐。
