# PetTI · 宠物行为人格鉴定实验室

> 给你家小祖宗建一份精神档案。

PetTI 是一个纯前端、零依赖的宠物行为人格测试。主人根据日常观察回答场景题，系统从多个行为维度计算画像，生成一份可以保存和分享的宠物人格档案。

## 实际能做什么

- 支持 CatTI（猫格）、DogTI（狗格）和兔人格实验内容。
- 猫和狗各有 24 道场景题，覆盖 6 个观察维度。
- 猫的维度包括亲近需求、边界感、活动能量、探索破坏、食物驱动和环境敏感。
- 狗的维度包括社交外向、服从响应、能量水平、警戒守护、食物驱动和分离依恋。
- 通过余弦相似度匹配人格向量，而不是随机抽签。
- 猫和狗各有 12 型典型人格，共 36 种人格档案内容。
- 结果页提供主人格、副人格、六维评分、行为画像、相处建议和分享卡。
- 支持复制分享文案，并可在本机保存结果档案。

## 60 秒演示

1. 打开 [PetTI 在线体验](https://daizhetang-create.github.io/petti/)。
2. 选择猫格或狗格，输入宠物名字。
3. 根据真实行为回答 24 道场景题，不要按“理想宠物”作答。
4. 查看人格代号、六维雷达、行为画像和主人相处建议。
5. 复制结果分享文案，或把结果存入档案室。

## 在线体验与本地运行

- 在线体验：[daizhetang-create.github.io/petti](https://daizhetang-create.github.io/petti/)
- 仓库预览：[index.html](index.html)

本项目不需要安装依赖、后端或 API key。直接双击 `index.html`，或运行：

```bash
python -m http.server 5500
```

然后打开 `http://localhost:5500`。

## 方法说明

PetTI 是娱乐和观察工具，不是兽医诊断、心理诊断或行为治疗。它不会预测宠物寿命，也不会替代专业训练和医疗建议。结果是基于主人观察输入的行为画像，应该当作一种有趣的记录方式。

## 项目状态

当前版本适合公开体验。后续可继续补充结果分享图导出、更多物种、题目版本记录和无障碍键盘流程。

## 许可

[MIT License](LICENSE) © 2026 TANG DAIZHE (Jay)

## 项目链接

- 仓库：[daizhetang-create/petti](https://github.com/daizhetang-create/petti)
- 在线体验：[PetTI](https://daizhetang-create.github.io/petti/)