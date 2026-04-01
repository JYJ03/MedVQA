# MedVQA

本仓库用于汇总与 **Medical Visual Question Answering（MedVQA，医学视觉问答）** 相关的数据集与资源。后续我会持续补充更多数据集主页信息，并在下表中更新。

## 数据集一览

| 数据集 | 模态/图像类型 | 任务形式 | 规模（大致） | 语言 | 许可证 | 链接 | 备注 |
|---|---|---|---:|---|---|---|---|
| VQA-RAD | 放射学影像（Radiology：X-ray/CT/MRI 等）+ 文本问题 | 混合：Open-ended + Close-ended（Yes/No） | 约 2,244 QA / 314 图像 | 英文 | CC0-1.0 | https://huggingface.co/datasets/flaviagiammarino/vqa-rad | 基于 MedPix，问题由临床医生人工生成；常用于训练/评测医学 VQA |

## 图片示例插入通道（模板）

你可以把数据集的样例图（或你自己从数据集中抽取的样例图）放到仓库中，例如：`assets/datasets/vqa-rad/example.jpg`，然后在 README 里用下面的方式插入。

> 提示：如果你还没创建 `assets/` 目录也没关系，后续补上图片文件即可。

```markdown
### VQA-RAD 示例

![VQA-RAD example](assets/datasets/vqa-rad/example.jpg)

- Q: are the lungs normal appearing?
- A: no
```

---

接下来你继续把其它数据集主页链接发我即可；我会按同样格式补充到表格里，并尽量标注：图像类型（如放射学/病理/皮肤/眼底/内镜等）、任务形式（open-ended/多选/判断）、语言与大致规模。