
# DeepClima-R1：专业的中文语境气候文本分类工具

## 📖 项目简介
**DeepClima-R1** 是专门针对中文气候语境深度定制的文本判别模型。它不仅具备强大的大语言模型底座，更融合了高标准的行业知识与严谨的官方语境，是目前气候变化领域文本自动化处理的高效解决方案。

---

## 🌟 核心优势

### 1. 卓越的底座能力：基于 DeepSeek-R1 的逻辑推理优势
DeepClima-R1 以 **DeepSeek-R1-0528-Qwen3-8B** 为基准模型。相比普通模型，R1 系列具备极强的链式推理能力，能够处理长文本中的复杂逻辑。
- **核心逻辑**：模型不只是识别“气候”关键词，而是在“理解”文本背后的逻辑关系。例如，它能有效区分“由于天气晴朗而郊游”与“由于极端天气导致经济损失”之间的本质差异。

### 2. 权威的数据基因：植根于官方主流媒体语境
模型使用 **10,000 条《人民日报》** 精选语料进行微调，确保了模型掌握中国最高标准的气候话语体系。
- **适用场景**：其语料来源权威、词汇规范。模型能够精准识别“碳达峰、碳中和、生态治理、能源结构转型”等具有中国特色气候语境的文本，非常适合政府、学术及严肃媒体的数据处理任务。

### 3. 专家级标注精度：跨学科团队构建的知识护城河
训练数据的标注由 **气候金融专业** 与 **计算机专业** 研究生组成的跨学科团队协作完成，并经过多轮严格的核实校对。
- **专业深度**：不同于普通的众包标注，DeepClima-R1 具备极高的专业知识含量。它能捕捉到普通模型容易忽略的“隐含气候相关性”（如绿色信贷、光伏产能、减污降碳等），极大降低了语义误差。

### 4. 突出的分类性能：性能的质变飞跃
在 880 条独立的“按文章组切分”测试集上，DeepClima-R1 展现出了卓越的可靠性。

| 评估指标 | 表现数值 | 说明 |
| :--- | :--- | :--- |
| **准确率 (Accuracy)** | **88.64%** | 远超基础模型，达到工业级应用标准 |
| **召回率 (Recall)** | **91.67%** | 极低漏判率，确保海量筛选中不遗漏关键信息 |
| **F1 分数** | **0.9083** | 在“抓得准”和“找得全”之间取得完美平衡 |

---

## 🚀 性能对比 (vs Base Model)

经过 LoRA 精准微调后，模型在气候语境下的识别能力发生了质变：

* **漏判率骤降**：正类漏判数量（FN）从 270 降低至 45。
* **语义感知力增强**：微调有效地引导模型学习到了气候变化语境相关的关键语义特征，验证了参数高效微调在垂直领域任务中的有效性。

---

## 🛠️ 技术规格
- **基础模型**: `DeepSeek-R1-0528-Qwen3-8B`
- **微调方法**: `LoRA (Parameter-Efficient Fine-Tuning)`
- **训练平台**: `OpenBayes`
- **应用领域**: `文本分类` / `气候语境识别` / `大数据筛选`

---

> **总结**：DeepClima-R1 是一个将前沿推理模型与权威官方语料深度融合的专家级工具，旨在为中文气候文本的精准解析提供可靠的技术支撑。


## Model Details

### Model Description

<!-- Provide a longer summary of what this model is. -->



- **Developed by:** [More Information Needed]
- **Funded by [optional]:** [More Information Needed]
- **Shared by [optional]:** [More Information Needed]
- **Model type:** [More Information Needed]
- **Language(s) (NLP):** [More Information Needed]
- **License:** [More Information Needed]
- **Finetuned from model [optional]:** [More Information Needed]

### Model Sources [optional]

<!-- Provide the basic links for the model. -->

- **Repository:** [More Information Needed]
- **Paper [optional]:** [More Information Needed]
- **Demo [optional]:** [More Information Needed]

## Uses

<!-- Address questions around how the model is intended to be used, including the foreseeable users of the model and those affected by the model. -->

### Direct Use

<!-- This section is for the model use without fine-tuning or plugging into a larger ecosystem/app. -->

[More Information Needed]

### Downstream Use [optional]

<!-- This section is for the model use when fine-tuned for a task, or when plugged into a larger ecosystem/app -->

[More Information Needed]

### Out-of-Scope Use

<!-- This section addresses misuse, malicious use, and uses that the model will not work well for. -->

[More Information Needed]

## Bias, Risks, and Limitations

<!-- This section is meant to convey both technical and sociotechnical limitations. -->

[More Information Needed]

### Recommendations

<!-- This section is meant to convey recommendations with respect to the bias, risk, and technical limitations. -->

Users (both direct and downstream) should be made aware of the risks, biases and limitations of the model. More information needed for further recommendations.

## How to Get Started with the Model

Use the code below to get started with the model.

[More Information Needed]

## Training Details

### Training Data

<!-- This should link to a Dataset Card, perhaps with a short stub of information on what the training data is all about as well as documentation related to data pre-processing or additional filtering. -->

[More Information Needed]

### Training Procedure

<!-- This relates heavily to the Technical Specifications. Content here should link to that section when it is relevant to the training procedure. -->

#### Preprocessing [optional]

[More Information Needed]


#### Training Hyperparameters

- **Training regime:** [More Information Needed] <!--fp32, fp16 mixed precision, bf16 mixed precision, bf16 non-mixed precision, fp16 non-mixed precision, fp8 mixed precision -->

#### Speeds, Sizes, Times [optional]

<!-- This section provides information about throughput, start/end time, checkpoint size if relevant, etc. -->

[More Information Needed]

## Evaluation

<!-- This section describes the evaluation protocols and provides the results. -->

### Testing Data, Factors & Metrics

#### Testing Data

<!-- This should link to a Dataset Card if possible. -->

[More Information Needed]

#### Factors

<!-- These are the things the evaluation is disaggregating by, e.g., subpopulations or domains. -->

[More Information Needed]

#### Metrics

<!-- These are the evaluation metrics being used, ideally with a description of why. -->

[More Information Needed]

### Results

[More Information Needed]

#### Summary



## Model Examination [optional]

<!-- Relevant interpretability work for the model goes here -->

[More Information Needed]

## Environmental Impact

<!-- Total emissions (in grams of CO2eq) and additional considerations, such as electricity usage, go here. Edit the suggested text below accordingly -->

Carbon emissions can be estimated using the [Machine Learning Impact calculator](https://mlco2.github.io/impact#compute) presented in [Lacoste et al. (2019)](https://arxiv.org/abs/1910.09700).

- **Hardware Type:** [More Information Needed]
- **Hours used:** [More Information Needed]
- **Cloud Provider:** [More Information Needed]
- **Compute Region:** [More Information Needed]
- **Carbon Emitted:** [More Information Needed]

## Technical Specifications [optional]

### Model Architecture and Objective

[More Information Needed]

### Compute Infrastructure

[More Information Needed]

#### Hardware

[More Information Needed]

#### Software

[More Information Needed]

## Citation [optional]

<!-- If there is a paper or blog post introducing the model, the APA and Bibtex information for that should go in this section. -->

**BibTeX:**

[More Information Needed]

**APA:**

[More Information Needed]

## Glossary [optional]

<!-- If relevant, include terms and calculations in this section that can help readers understand the model or model card. -->

[More Information Needed]

## More Information [optional]

[More Information Needed]

## Model Card Authors [optional]

[More Information Needed]

## Model Card Contact

[More Information Needed]
### Framework versions

- PEFT 0.18.1
