# 008 · 手机坠落九连拍

[返回分类索引](../README.md) · [返回首页](../../README.md)

> 从滑落手机的后置镜头视角，用九宫格表现一次意外的旋转、失焦与触地。

## 基本信息

| 字段 | 内容 |
| --- | --- |
| 主分类 | 人物摄影 |
| 风格 / 主题标签 | 手机POV / 连续动作 / 九宫格 / 广角 / 运动模糊 / 校园日常 |
| 提示词作者 | **DeepBlue深蓝（@DeepBlueX0）**，X 作者，署名由整理者提供 |
| 作者主页 | [x.com/DeepBlueX0](https://x.com/DeepBlueX0)（按所提供账号整理，未独立核验） |
| 原帖链接 | 待补充；收录文本未与原帖逐字核对 |
| 本次主体 | 中国女高中生，由整理者替换主题 |
| 工具 / 模型 | Codex 内置图像生成工具；具体底层模型未确认 |
| 收录日期 | 2026-10-12 |
| 测试过程 | 空姐版本生成 → 中国高中生版本新生成 → 参考上一张修改为女高中生 |
| 保存图片 | 最新女高中生版本，以及该次编辑所用的高中生参考图 |
| 画幅 | 整张9:16，3列×3行九宫格 |
| 图片性质 | AI生成的连拍效果模拟，非真实手机连拍 |

## 收录提示词与主题替换

原先由整理者提供的文本：

```text
【空姐】 × 手机后置镜头主观视角意外脱手坠落 × 同次坠落连续九连拍 × iPhone失败多连拍 × 9:16竖版九宫格 × 夸张广角透视 × 随机旋转机位、失焦、运动模糊与画面角度
```

本次最终主题版本，仅替换主体：

```text
【中国女高中生】 × 手机后置镜头主观视角意外脱手坠落 × 同次坠落连续九连拍 × iPhone失败多连拍 × 9:16竖版九宫格 × 夸张广角透视 × 随机旋转机位、失焦、运动模糊与画面角度
```

作者署名来自整理者确认。主题替换与下面的补充条件属于本项目，不声称全部为作者原帖内容。

## 最终效果图

![中国女高中生教室手机坠落九宫格，镜头翻转并逐渐接近地板](images/result-girl.png)

最新图由[高中生版本参考图](images/reference-student.png)编辑而来，保留原九宫格、教室和主要镜头顺序。不是最终短提示词从零生成的直接测试。

## 实际生成方式

先具体化了教室、蓝白长袖校服与长裤、桌椅和地砖，并按阅读顺序规定镜头：滑落时的人物 → 伸手 → 桌角 → 教室天花板 → 椅腿与地面 → 模糊翻转 → 触地 → 倒置人物 → 捡起。

新增约束包括：同一人物和环境、手机本身不入镜、自然后置镜头POV、普通校园事件，以及部分格只拍到环境，不要求九格都看到完整人脸。

### 最终编辑的完整提交文本

```text
Edit the provided nine-panel classroom falling-phone contact sheet. Replace the primary male student consistently in every panel with the SAME Chinese female high school student around age 17, naturally tied-back dark ponytail, ordinary youthful face, no glamorous makeup, wearing loose long-sleeved blue-and-white school tracksuit jacket zipped normally and matching full-length loose track pants, ordinary white sneakers. Preserve vertical 9:16 canvas, exact 3x3 grid, thin black gutters, same ordinary classroom, wood desks, metal chairs, tile floor, daylight and the original coherent rear-camera phone-fall sequence. Row-major sequence still goes from surprised face/reaching fingers, through turning view and ceiling, near-floor chair legs, sideways motion blur, floor impact, upside-down student leaning down, finally student crouching in track pants reaching to pick it up with an amused embarrassed smile. Same girl's face, ponytail and uniform across all visible panels. Maintain accidental iPhone failed-burst feeling, strong ultrawide foreshortening, rotations, focus mistakes and motion blur. Camera phone never visible, no captions, no watermark. Fully clothed everyday classroom event, focus on expression, hands and surroundings; no skirts, no revealing clothing, no sexual framing.
```

## 实际体验与不足

以下来自本项目输出观察，不是对原作者效果的评价。

| 项目 | 观察与不足 | 可补充的条件 |
| --- | --- | --- |
| 九格布局 | 3×3边界和竖版排版清楚 | 明确整张比例、格数与从左到右、从上到下的顺序 |
| 人物连续性 | 蓝白校服和女学生面貌大体一致，侧脸与倒置帧难以精确核验 | 固定发型、服装、环境；重要时提供角色参考图 |
| 坠落轨迹 | 视觉上能读出翻转与接近地面，但部分机位跳变，不能认定物理轨迹准确 | 用分阶段动作替代完全随机角度，限制相邻帧的变化 |
| 后置POV | 手机未入镜；人物伸手符合镜头被捡起的设定 | 明确相机随手机运动，不是旁观者拍摄手机 |
| 失败感 | 中间帧模糊明显，但首尾人脸偏清楚、构图较整齐 | 允许部分裁切、偏斜与遮挡，避免每格都成为清晰肖像 |
| 手部 | 近景广角手指形态和连接不易判断，值得放大复核 | 只在少数帧出现伸手，减少多帧极近手掌特写 |
| 连拍时间 | 图中包含触地、翻滚和人物蹲下拾取，可能超过单次短坠落的时间窗 | 明确是纯坠落九帧，还是坠落后继续拍摄的事件序列 |

我认为原文最值得补充的是**时间范围和轨迹**。“同次坠落”与“完全随机旋转”若不作约束，容易成为九张同场景照片的拼图；指定连续阶段更有助于表达同一事件。

本次实际包含拾取阶段，更准确的描述是“滑落到拾取的九帧序列”。若目标是严格同次坠落，就应删去人物已经蹲下拾取的帧，让最后一格止于触地或短暂滚动。

## 可复用补充模板

以下是本项目补充的待验证版本，不覆盖原文。

```text
【人物】 × 手机后置镜头坠落POV × 同一事件九帧 × 9:16竖版3×3九宫格。
场景：[明确地点]；人物服装与外貌：[固定特征]。
时间范围：[仅滑落至触地 / 滑落后继续拍摄直到被捡起，择一]。
按从左到右、从上到下的顺序排列，同一人物、同一光线、同一环境。
镜头随手机下坠和旋转，手机本体不出现在画面里。
前段：滑落与伸手反应；中段：视线经过身体边缘、家具与天花板；末段：地面逼近、触地或滚动。
选择包含拾取时，明确它是触地后的额外时间，而非仍在空中的坠落瞬间。
相邻镜头的高度、位置和旋转应衔接；随机变化必须服从同一次事件。
自然手机曝光，部分格失焦、裁切或有运动模糊，不要求每格都出现清晰完整人脸。
保留空间线索，让观者能辨认环境；无编号、无额外文字。
```

如果追求像真实失败连拍，建议减弱人像修饰、减少过度整齐的构图；如果追求叙事趣味，则可保留拾取时的表情，但明确它是更长的事件序列。两个目标应分别测试，当前没有新增验证图。
