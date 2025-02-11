<h1 align="center">
  <b>ChineseLlama2<b>
</h1>
<!-- <p align="center" width="100%"> -->


<p align="center" width="100%">
<img src="assets/llama.png" alt="Llama" style="width: 20%; display: block; margin: auto;"></a>
</p>
<p align="center">
<font face="黑体" color=orange size=8"> 最好的中文Llama大模型 </font>
</p>



## 社区介绍：Llama2中文社区
欢迎来到Llama2中文社区！我们是一个专注于Llama2模型在中文方面的优化和上层建设的高级技术社区。

我们热忱欢迎对大模型LLM充满热情的开发者和研究者加入我们的行列。

### 为什么选择Llama2中文社区？
🚀 **高级工程师团队支持**：社区有一批专注为大家服务的NLP高级工程师，我们有着强大的技术支持和丰富的经验，为您提供专业的指导和帮助。

🎯 **中文优化**：我们致力于在Llama2模型的中文处理方面进行优化，探索适用于中文的最佳实践，以提升其性能和适应性。

💡 **创新交流**：我们拥有一支富有创造力和经验的社区成员团队，定期组织线上活动、技术研讨和经验分享，促进成员间的创新交流。

🌐 **全球联结**：我们欢迎来自世界各地的开发者加入社区，构建一个开放、多元化的学习和交流平台。

🤝 **开放共享**：我们鼓励社区成员开源分享代码和模型，推动合作共赢，共同促进中文NLP技术的发展。

### 社区活动
🗓️ **线上讲座**：邀请行业内专家进行线上讲座，分享Llama2在中文NLP领域的最新技术和应用，探讨前沿研究成果。

💻 **项目展示**：成员可展示自己在Llama2中文优化方面的项目成果，获得反馈和建议，促进项目协作。

📚 **学习资源**：社区维护丰富的学习资料库，包括教程、文档和论文解读，为成员提供全面的学习支持。

📝 **论文解读**：社区成员共同解读与Llama2相关的最新研究论文，深入理解前沿算法和方法。

🎉 **主题活动**：定期举办各类主题活动，包括挑战赛、黑客马拉松和技术沙龙，让社区成员在轻松愉快的氛围中交流和学习。

🌟 **奖励计划**：我们设立奖励计划，对社区中积极参与、贡献优秀的成员给予荣誉和奖励，激励更多优秀人才的加入。

📈 **技术咨询**：我们提供技术咨询服务，解答您在Llama2开发和优化过程中遇到的问题，助您快速攻克难关。

🚀 **项目合作**：鼓励成员间的项目合作，共同探索Llama2在实际应用中的潜力，打造创新解决方案。


### 立即加入我们
📚 **愿景**：无论您是对Llama2已有研究和应用经验的专业开发者，还是对Llama2中文优化感兴趣并希望深入探索的新手，我们都热切期待您的加入。在Llama2中文社区，您将有机会与行业内顶尖人才共同交流，携手推动中文NLP技术的进步，开创更加美好的技术未来！

🔗 **温馨提示**：本社区为专业技术交流平台，我们热切期望志同道合的开发者和研究者加入。请遵守社区准则，共同维护积极向上的学习氛围，任何与Llama2无关的内容和广告将被清理。感谢您的理解和支持！



## 内容导引

| 章节                    | 描述                     |
| ----------------------- | ------------------------ |
| [🔥社区公告](#🔥社区公告) | 我们的最新动态           |
| [📝数据来源](#📝数据来源) | 介绍模型的训练数据来源 |
| [⏬模型体验](#⏬模型下载) | 模型huggingface🤗下载地址 |
| [🎉致谢](#🎉致谢) | 表达了我们由衷的敬意            |
| [🤔问题反馈](#🤔问题反馈) | 问题的反馈               |


## 🔥社区公告

#### 2023年7月19日：Llama2国内下载地址正在启动，敬请期待！

#### 2023年7月19日：开启Llama2中文社区，欢迎大家加入！


## 📝数据来源

我们计划通过以下数据来优化Llama2的中文能力:

| 类型                                                       | 描述                                                         |
| ---------------------------------------------------------- | ------------------------------------------------------------ |
| 网络数据                                                   | 互联网上公开的网络数据，挑选出去重后的高质量中文数据，涉及到百科，书籍，博客，新闻，公告，小说，公众号等高质量长文本数据。这部分数据还在清洗更多逐步加入到模型中。 |
| [Wikipedia](https://github.com/goldsmith/Wikipedia)        | 中文Wikipedia的数据                                          |
| [悟道](https://github.com/BAAI-WuDao/Model)                | 中文悟道开源的200G数据                                       |
| [Clue](https://github.com/CLUEbenchmark/CLUEDatasetSearch) | Clue开放的中文预训练数据，进行清洗后的高质量中文长文本数据   |
| 竞赛数据集                                                 | 近年来中文自然语言处理多任务竞赛数据集，约150个              |
| [MNBVC](https://github.com/esbatmop/MNBVC)                 | MNBVC 中清洗出来的部分数据集                                 |

**希望大家如果有较高质量的数据集能够提供给我们，不胜感激!💕💕**



## ⏬模型体验

Meta在🤗Huggingface上提供了所有模型的下载链接：https://huggingface.co/meta-llama


### 预训练模型

Llama2预训练模型包含7B、13B和70B三个版本

| 模型名称   | 🤗模型加载名称             | 下载地址                                                     |
| ---------- | ------------------------- | ------------------------------------------------------------ |
| Llama2-7B  | meta-llama/Llama-2-7b-hf  | [模型下载](https://huggingface.co/meta-llama/Llama-2-7b-hf)  |
| Llama2-13B | meta-llama/Llama-2-13b-hf | [模型下载](https://huggingface.co/meta-llama/Llama-2-13b-hf) |
| Llama2-70B | meta-llama/Llama-2-70b-hf | [模型下载](https://huggingface.co/meta-llama/Llama-2-70b-hf) |

### Chat模型

Llama2-Chat模型基于预训练模型进行了监督微调，具备更强的对话能力

| 模型名称        | 🤗模型加载名称                  | 下载地址                                                     |
| --------------- | ------------------------------ | ------------------------------------------------------------ |
| Llama2-7B-Chat  | meta-llama/Llama-2-7b-chat-hf  | [模型下载](https://huggingface.co/meta-llama/Llama-2-7b-chat-hf) |
| Llama2-13B-Chat | meta-llama/Llama-2-13b-chat-hf | [模型下载](https://huggingface.co/meta-llama/Llama-2-13b-chat-hf) |
| Llama2-70B-Chat | meta-llama/Llama-2-70b-chat-hf | [模型下载](https://huggingface.co/meta-llama/Llama-2-70b-chat-hf) |


### 模型调用代码示例

```
from transformers import AutoTokenizer, AutoModelForCausalLM
model = AutoModelForCausalLM.from_pretrained('meta-llama/Llama-2-7b-chat-hf',device_map='auto',torch_dtype=torch.float16,load_in_8bit=True)
model =model.eval()
tokenizer = AutoTokenizer.from_pretrained('meta-llama/Llama-2-7b-chat-hf',use_fast=False)
input_ids = tokenizer(['<s>Human: 介绍一下中国\n</s><s>Assistant: '], return_tensors="pt",add_special_tokens=False).input_ids.to('cuda')        
generate_input = {
    "input_ids":input_ids,
    "max_new_tokens":512,
    "do_sample":True,
    "top_k":50,
    "top_p":0.95,
    "temperature":0.3,
    "repetition_penalty":1.3,
    "eos_token_id":tokenizer.eos_token_id,
    "bos_token_id":tokenizer.bos_token_id,
    "pad_token_id":tokenizer.pad_token_id
}
generate_ids  = model.generate(**generate_input)
text = tokenizer.decode(generate_ids[0])
print(text)
```

## 🎉致谢

感谢原子回声[AtomEcho](https://github.com/AtomEcho)团队的技术和资源支持


## 🤔问题反馈

如有问题，请在GitHub Issue中提交。

在提交问题之前，请先查阅以往的issue是否能解决你的问题。

礼貌地提出问题，构建和谐的讨论社区。

加入微信群讨论😍😍

<img src="./assets/wechat.jpg" alt="Wechat" style="width: 60%; display: block; margin: auto;">
