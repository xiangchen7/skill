# Skill 快速索引

此索引由当前目录下 4 个仓库的 `SKILL.md` 自动扫描并按同名 skill 去重生成。每个说明尽量压成几个词，方便快速挑选；具体流程仍以对应 `SKILL.md` 为准。

## 已拉取仓库

| 仓库 | 分支 | 当前提交 |
|---|---:|---:|
| AI-Research-SKILLs | main | 28f2d29 |
| Auto-claude-code-research-in-sleep | main | 6c1a095 |
| oh-my-codex | main | e0465fdc |
| nature-skills | main | 5f4932b |

## 先选入口

| 你要做什么 | 优先看这些 skill |
|---|---|
| 从方向找 idea | `idea-discovery`, `idea-creator`, `novelty-check`, `research-review` |
| 查论文/做综述 | `research-lit`, `arxiv`, `semantic-scholar`, `alphaxiv`, `deepxiv` |
| 设计并跑实验 | `experiment-plan`, `experiment-bridge`, `run-experiment`, `experiment-queue`, `training-check` |
| 结果转论文主张 | `result-to-claim`, `ablation-planner`, `experiment-audit`, `paper-claim-audit` |
| 写论文/幻灯片 | `paper-writing`, `paper-write`, `paper-figure`, `paper-slides`, `rebuttal` |
| Nature/CNS 风格 | `nature-writing`, `nature-figure`, `nature-citation`, `nature-response` |
| 训练/部署模型 | `axolotl`, `deepspeed`, `vllm`, `sglang`, `tensorrt-llm`, `ray-train` |
| Codex/OMX 工作流 | `plan`, `ralplan`, `ralph`, `team`, `ultraqa`, `code-review` |

## 完整去重索引

> `来源数` 大于 1 通常表示仓库里存在镜像副本、插件副本或不同后端变体；`入口路径` 指向优先阅读的那份。

### 科研流程

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| ablation-planner | 消融实验规划 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/ablation-planner/SKILL.md](Auto-claude-code-research-in-sleep/skills/ablation-planner/SKILL.md) |
| analyze-results | 实验结果分析 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/analyze-results/SKILL.md](Auto-claude-code-research-in-sleep/skills/analyze-results/SKILL.md) |
| auto-review-loop | 自动审稿迭代 | Auto-claude-code-research-in-sleep | 4 | [Auto-claude-code-research-in-sleep/skills/auto-review-loop/SKILL.md](Auto-claude-code-research-in-sleep/skills/auto-review-loop/SKILL.md) |
| auto-review-loop-llm | 通用 LLM 审稿 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/auto-review-loop-llm/SKILL.md](Auto-claude-code-research-in-sleep/skills/auto-review-loop-llm/SKILL.md) |
| auto-review-loop-minimax | MiniMax 审稿迭代 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/auto-review-loop-minimax/SKILL.md](Auto-claude-code-research-in-sleep/skills/auto-review-loop-minimax/SKILL.md) |
| experiment-audit | 实验诚信审查 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/experiment-audit/SKILL.md](Auto-claude-code-research-in-sleep/skills/experiment-audit/SKILL.md) |
| experiment-bridge | 计划到实验执行 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/experiment-bridge/SKILL.md](Auto-claude-code-research-in-sleep/skills/experiment-bridge/SKILL.md) |
| experiment-plan | 实验路线设计 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/experiment-plan/SKILL.md](Auto-claude-code-research-in-sleep/skills/experiment-plan/SKILL.md) |
| experiment-queue | 实验队列调度 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/experiment-queue/SKILL.md](Auto-claude-code-research-in-sleep/skills/experiment-queue/SKILL.md) |
| formula-derivation | 公式推导 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/formula-derivation/SKILL.md](Auto-claude-code-research-in-sleep/skills/formula-derivation/SKILL.md) |
| idea-creator | 研究 idea 生成 | Auto-claude-code-research-in-sleep | 3 | [Auto-claude-code-research-in-sleep/skills/idea-creator/SKILL.md](Auto-claude-code-research-in-sleep/skills/idea-creator/SKILL.md) |
| idea-discovery | idea 发现流程 | Auto-claude-code-research-in-sleep | 3 | [Auto-claude-code-research-in-sleep/skills/idea-discovery/SKILL.md](Auto-claude-code-research-in-sleep/skills/idea-discovery/SKILL.md) |
| idea-discovery-robot | 机器人 idea 发现 | Auto-claude-code-research-in-sleep | 3 | [Auto-claude-code-research-in-sleep/skills/idea-discovery-robot/SKILL.md](Auto-claude-code-research-in-sleep/skills/idea-discovery-robot/SKILL.md) |
| kill-argument | 反驳杀伤测试 | Auto-claude-code-research-in-sleep | 1 | [Auto-claude-code-research-in-sleep/skills/kill-argument/SKILL.md](Auto-claude-code-research-in-sleep/skills/kill-argument/SKILL.md) |
| monitor-experiment | 实验监控 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/monitor-experiment/SKILL.md](Auto-claude-code-research-in-sleep/skills/monitor-experiment/SKILL.md) |
| novelty-check | 新颖性检查 | Auto-claude-code-research-in-sleep | 4 | [Auto-claude-code-research-in-sleep/skills/novelty-check/SKILL.md](Auto-claude-code-research-in-sleep/skills/novelty-check/SKILL.md) |
| research-lit | 文献综述检索 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/research-lit/SKILL.md](Auto-claude-code-research-in-sleep/skills/research-lit/SKILL.md) |
| research-pipeline | 科研全流程 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/research-pipeline/SKILL.md](Auto-claude-code-research-in-sleep/skills/research-pipeline/SKILL.md) |
| research-refine | 研究方案打磨 | Auto-claude-code-research-in-sleep | 4 | [Auto-claude-code-research-in-sleep/skills/research-refine/SKILL.md](Auto-claude-code-research-in-sleep/skills/research-refine/SKILL.md) |
| research-refine-pipeline | 方案到实验计划 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/research-refine-pipeline/SKILL.md](Auto-claude-code-research-in-sleep/skills/research-refine-pipeline/SKILL.md) |
| research-review | 研究批判审稿 | Auto-claude-code-research-in-sleep | 4 | [Auto-claude-code-research-in-sleep/skills/research-review/SKILL.md](Auto-claude-code-research-in-sleep/skills/research-review/SKILL.md) |
| research-wiki | 研究知识库 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/research-wiki/SKILL.md](Auto-claude-code-research-in-sleep/skills/research-wiki/SKILL.md) |
| run-experiment | 启动实验任务 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/run-experiment/SKILL.md](Auto-claude-code-research-in-sleep/skills/run-experiment/SKILL.md) |

### 检索/文献

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| alphaxiv | 单篇论文速读 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/alphaxiv/SKILL.md](Auto-claude-code-research-in-sleep/skills/alphaxiv/SKILL.md) |
| arxiv | arXiv 检索下载 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/arxiv/SKILL.md](Auto-claude-code-research-in-sleep/skills/arxiv/SKILL.md) |
| comm-lit-review | 通信文献综述 | Auto-claude-code-research-in-sleep | 1 | [Auto-claude-code-research-in-sleep/skills/skills-codex/comm-lit-review/SKILL.md](Auto-claude-code-research-in-sleep/skills/skills-codex/comm-lit-review/SKILL.md) |
| comm-lit-review-claude-single | 通信综述单模型 | Auto-claude-code-research-in-sleep | 1 | [Auto-claude-code-research-in-sleep/skills/comm-lit-review/SKILL.md](Auto-claude-code-research-in-sleep/skills/comm-lit-review/SKILL.md) |
| deepxiv | DeepXiv 读论文 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/deepxiv/SKILL.md](Auto-claude-code-research-in-sleep/skills/deepxiv/SKILL.md) |
| exa-search | Exa 网页检索 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/exa-search/SKILL.md](Auto-claude-code-research-in-sleep/skills/exa-search/SKILL.md) |
| gemini-search | Gemini 联网检索 | Auto-claude-code-research-in-sleep | 1 | [Auto-claude-code-research-in-sleep/skills/gemini-search/SKILL.md](Auto-claude-code-research-in-sleep/skills/gemini-search/SKILL.md) |
| openalex | OpenAlex 检索 | Auto-claude-code-research-in-sleep | 1 | [Auto-claude-code-research-in-sleep/skills/openalex/SKILL.md](Auto-claude-code-research-in-sleep/skills/openalex/SKILL.md) |
| semantic-scholar | Semantic Scholar | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/semantic-scholar/SKILL.md](Auto-claude-code-research-in-sleep/skills/semantic-scholar/SKILL.md) |

### 论文/投稿产物

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| auto-paper-improvement-loop | 论文自动改进 | Auto-claude-code-research-in-sleep | 4 | [Auto-claude-code-research-in-sleep/skills/auto-paper-improvement-loop/SKILL.md](Auto-claude-code-research-in-sleep/skills/auto-paper-improvement-loop/SKILL.md) |
| citation-audit | 引文真实性核验 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/citation-audit/SKILL.md](Auto-claude-code-research-in-sleep/skills/citation-audit/SKILL.md) |
| figure-description | 图形文字说明 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/figure-description/SKILL.md](Auto-claude-code-research-in-sleep/skills/figure-description/SKILL.md) |
| figure-spec | 图形规格设计 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/figure-spec/SKILL.md](Auto-claude-code-research-in-sleep/skills/figure-spec/SKILL.md) |
| grant-proposal | 基金申请书 | Auto-claude-code-research-in-sleep | 3 | [Auto-claude-code-research-in-sleep/skills/grant-proposal/SKILL.md](Auto-claude-code-research-in-sleep/skills/grant-proposal/SKILL.md) |
| overleaf-sync | Overleaf 同步 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/overleaf-sync/SKILL.md](Auto-claude-code-research-in-sleep/skills/overleaf-sync/SKILL.md) |
| paper-claim-audit | 论文主张审计 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/paper-claim-audit/SKILL.md](Auto-claude-code-research-in-sleep/skills/paper-claim-audit/SKILL.md) |
| paper-compile | LaTeX 编译修复 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/paper-compile/SKILL.md](Auto-claude-code-research-in-sleep/skills/paper-compile/SKILL.md) |
| paper-figure | 论文图表制作 | Auto-claude-code-research-in-sleep | 4 | [Auto-claude-code-research-in-sleep/skills/paper-figure/SKILL.md](Auto-claude-code-research-in-sleep/skills/paper-figure/SKILL.md) |
| paper-illustration | 论文插图生成 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/paper-illustration/SKILL.md](Auto-claude-code-research-in-sleep/skills/paper-illustration/SKILL.md) |
| paper-illustration-image2 | Image2 插图 | Auto-claude-code-research-in-sleep | 1 | [Auto-claude-code-research-in-sleep/skills/paper-illustration-image2/SKILL.md](Auto-claude-code-research-in-sleep/skills/paper-illustration-image2/SKILL.md) |
| paper-plan | 论文大纲规划 | Auto-claude-code-research-in-sleep | 4 | [Auto-claude-code-research-in-sleep/skills/paper-plan/SKILL.md](Auto-claude-code-research-in-sleep/skills/paper-plan/SKILL.md) |
| paper-poster | 会议海报生成 | Auto-claude-code-research-in-sleep | 3 | [Auto-claude-code-research-in-sleep/skills/paper-poster/SKILL.md](Auto-claude-code-research-in-sleep/skills/paper-poster/SKILL.md) |
| paper-slides | 论文报告幻灯片 | Auto-claude-code-research-in-sleep | 3 | [Auto-claude-code-research-in-sleep/skills/paper-slides/SKILL.md](Auto-claude-code-research-in-sleep/skills/paper-slides/SKILL.md) |
| paper-talk | 会议报告稿 | Auto-claude-code-research-in-sleep | 1 | [Auto-claude-code-research-in-sleep/skills/paper-talk/SKILL.md](Auto-claude-code-research-in-sleep/skills/paper-talk/SKILL.md) |
| paper-write | 论文分节写作 | Auto-claude-code-research-in-sleep | 4 | [Auto-claude-code-research-in-sleep/skills/paper-write/SKILL.md](Auto-claude-code-research-in-sleep/skills/paper-write/SKILL.md) |
| paper-writing | 论文写作流水线 | Auto-claude-code-research-in-sleep | 3 | [Auto-claude-code-research-in-sleep/skills/paper-writing/SKILL.md](Auto-claude-code-research-in-sleep/skills/paper-writing/SKILL.md) |
| proof-checker | 证明检查 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/proof-checker/SKILL.md](Auto-claude-code-research-in-sleep/skills/proof-checker/SKILL.md) |
| proof-writer | 数学证明撰写 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/proof-writer/SKILL.md](Auto-claude-code-research-in-sleep/skills/proof-writer/SKILL.md) |
| rebuttal | 审稿 rebuttal | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/rebuttal/SKILL.md](Auto-claude-code-research-in-sleep/skills/rebuttal/SKILL.md) |
| render-html | 报告转 HTML | Auto-claude-code-research-in-sleep | 1 | [Auto-claude-code-research-in-sleep/skills/render-html/SKILL.md](Auto-claude-code-research-in-sleep/skills/render-html/SKILL.md) |
| resubmit-pipeline | 论文重投流程 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/resubmit-pipeline/SKILL.md](Auto-claude-code-research-in-sleep/skills/resubmit-pipeline/SKILL.md) |
| result-to-claim | 结果到主张 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/result-to-claim/SKILL.md](Auto-claude-code-research-in-sleep/skills/result-to-claim/SKILL.md) |
| slides-polish | 幻灯片精修 | Auto-claude-code-research-in-sleep | 1 | [Auto-claude-code-research-in-sleep/skills/slides-polish/SKILL.md](Auto-claude-code-research-in-sleep/skills/slides-polish/SKILL.md) |
| writing-systems-papers | 系统论文蓝图 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/writing-systems-papers/SKILL.md](Auto-claude-code-research-in-sleep/skills/writing-systems-papers/SKILL.md) |

### Nature/CNS 写作

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| nature-academic-search | Nature 文献检索 | nature-skills | 1 | [nature-skills/skills/nature-academic-search/SKILL.md](nature-skills/skills/nature-academic-search/SKILL.md) |
| nature-citation | Nature 引文规范 | nature-skills | 1 | [nature-skills/skills/nature-citation/SKILL.md](nature-skills/skills/nature-citation/SKILL.md) |
| nature-data | Nature 数据声明 | nature-skills | 1 | [nature-skills/skills/nature-data/SKILL.md](nature-skills/skills/nature-data/SKILL.md) |
| nature-figure | Nature 图表规范 | nature-skills | 1 | [nature-skills/skills/nature-figure/SKILL.md](nature-skills/skills/nature-figure/SKILL.md) |
| nature-paper2ppt | 论文转 PPT | nature-skills | 1 | [nature-skills/skills/nature-paper2ppt/SKILL.md](nature-skills/skills/nature-paper2ppt/SKILL.md) |
| nature-polishing | Nature 语言润色 | nature-skills | 1 | [nature-skills/skills/nature-polishing/SKILL.md](nature-skills/skills/nature-polishing/SKILL.md) |
| nature-reader | 论文中英精读 | nature-skills | 1 | [nature-skills/skills/nature-reader/SKILL.md](nature-skills/skills/nature-reader/SKILL.md) |
| nature-response | 审稿回复 | nature-skills | 1 | [nature-skills/skills/nature-response/SKILL.md](nature-skills/skills/nature-response/SKILL.md) |
| nature-writing | Nature 风格写作 | nature-skills | 1 | [nature-skills/skills/nature-writing/SKILL.md](nature-skills/skills/nature-writing/SKILL.md) |

### 专利

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| claims-drafting | 专利权利要求 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/claims-drafting/SKILL.md](Auto-claude-code-research-in-sleep/skills/claims-drafting/SKILL.md) |
| embodiment-description | 专利实施例 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/embodiment-description/SKILL.md](Auto-claude-code-research-in-sleep/skills/embodiment-description/SKILL.md) |
| invention-structuring | 发明结构化 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/invention-structuring/SKILL.md](Auto-claude-code-research-in-sleep/skills/invention-structuring/SKILL.md) |
| jurisdiction-format | 法域格式适配 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/jurisdiction-format/SKILL.md](Auto-claude-code-research-in-sleep/skills/jurisdiction-format/SKILL.md) |
| patent-novelty-check | 专利新颖性 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/patent-novelty-check/SKILL.md](Auto-claude-code-research-in-sleep/skills/patent-novelty-check/SKILL.md) |
| patent-pipeline | 专利全流程 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/patent-pipeline/SKILL.md](Auto-claude-code-research-in-sleep/skills/patent-pipeline/SKILL.md) |
| patent-review | 专利审查 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/patent-review/SKILL.md](Auto-claude-code-research-in-sleep/skills/patent-review/SKILL.md) |
| prior-art-search | 现有技术检索 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/prior-art-search/SKILL.md](Auto-claude-code-research-in-sleep/skills/prior-art-search/SKILL.md) |
| specification-writing | 专利说明书 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/specification-writing/SKILL.md](Auto-claude-code-research-in-sleep/skills/specification-writing/SKILL.md) |

### 实验/GPU 运维

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| serverless-modal | Modal 无服务器 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/serverless-modal/SKILL.md](Auto-claude-code-research-in-sleep/skills/serverless-modal/SKILL.md) |
| system-profile | 系统性能剖析 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/system-profile/SKILL.md](Auto-claude-code-research-in-sleep/skills/system-profile/SKILL.md) |
| training-check | 训练健康检查 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/training-check/SKILL.md](Auto-claude-code-research-in-sleep/skills/training-check/SKILL.md) |
| vast-gpu | vast.ai 租 GPU | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/vast-gpu/SKILL.md](Auto-claude-code-research-in-sleep/skills/vast-gpu/SKILL.md) |

### 模型架构

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| distributed-llm-pretraining-torchtitan | TorchTitan 预训练 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/01-model-architecture/torchtitan/SKILL.md](AI-Research-SKILLs/01-model-architecture/torchtitan/SKILL.md) |
| implementing-llms-litgpt | LitGPT 实现训练 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/01-model-architecture/litgpt/SKILL.md](AI-Research-SKILLs/01-model-architecture/litgpt/SKILL.md) |
| mamba-architecture | Mamba 架构 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/01-model-architecture/mamba/SKILL.md](AI-Research-SKILLs/01-model-architecture/mamba/SKILL.md) |
| nanogpt | nanoGPT 教学 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/01-model-architecture/nanogpt/SKILL.md](AI-Research-SKILLs/01-model-architecture/nanogpt/SKILL.md) |
| rwkv-architecture | RWKV 架构 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/01-model-architecture/rwkv/SKILL.md](AI-Research-SKILLs/01-model-architecture/rwkv/SKILL.md) |

### 分词器

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| huggingface-tokenizers | HF 高速分词 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/02-tokenization/huggingface-tokenizers/SKILL.md](AI-Research-SKILLs/02-tokenization/huggingface-tokenizers/SKILL.md) |
| sentencepiece | SentencePiece 分词 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/02-tokenization/sentencepiece/SKILL.md](AI-Research-SKILLs/02-tokenization/sentencepiece/SKILL.md) |

### 微调

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| axolotl | Axolotl 微调 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/03-fine-tuning/axolotl/SKILL.md](AI-Research-SKILLs/03-fine-tuning/axolotl/SKILL.md) |
| llama-factory | LLaMA Factory 微调 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/03-fine-tuning/llama-factory/SKILL.md](AI-Research-SKILLs/03-fine-tuning/llama-factory/SKILL.md) |
| peft-fine-tuning | PEFT/LoRA 微调 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/03-fine-tuning/peft/SKILL.md](AI-Research-SKILLs/03-fine-tuning/peft/SKILL.md) |
| unsloth | Unsloth 快速微调 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/03-fine-tuning/unsloth/SKILL.md](AI-Research-SKILLs/03-fine-tuning/unsloth/SKILL.md) |

### 后训练/RL

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| fine-tuning-with-trl | TRL 微调 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/06-post-training/trl-fine-tuning/SKILL.md](AI-Research-SKILLs/06-post-training/trl-fine-tuning/SKILL.md) |
| grpo-rl-training | GRPO 强化学习 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/06-post-training/grpo-rl-training/SKILL.md](AI-Research-SKILLs/06-post-training/grpo-rl-training/SKILL.md) |
| miles-rl-training | MILES RL 训练 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/06-post-training/miles/SKILL.md](AI-Research-SKILLs/06-post-training/miles/SKILL.md) |
| openrlhf-training | OpenRLHF 训练 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/06-post-training/openrlhf/SKILL.md](AI-Research-SKILLs/06-post-training/openrlhf/SKILL.md) |
| simpo-training | SimPO 对齐 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/06-post-training/simpo/SKILL.md](AI-Research-SKILLs/06-post-training/simpo/SKILL.md) |
| slime-rl-training | slime RL 训练 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/06-post-training/slime/SKILL.md](AI-Research-SKILLs/06-post-training/slime/SKILL.md) |
| torchforge-rl-training | TorchForge RL | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/06-post-training/torchforge/SKILL.md](AI-Research-SKILLs/06-post-training/torchforge/SKILL.md) |
| verl-rl-training | verl RL 训练 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/06-post-training/verl/SKILL.md](AI-Research-SKILLs/06-post-training/verl/SKILL.md) |

### 分布式训练

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| deepspeed | DeepSpeed 训练 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/08-distributed-training/deepspeed/SKILL.md](AI-Research-SKILLs/08-distributed-training/deepspeed/SKILL.md) |
| huggingface-accelerate | Accelerate 分布式 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/08-distributed-training/accelerate/SKILL.md](AI-Research-SKILLs/08-distributed-training/accelerate/SKILL.md) |
| pytorch-fsdp2 | PyTorch FSDP2 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/08-distributed-training/pytorch-fsdp2/SKILL.md](AI-Research-SKILLs/08-distributed-training/pytorch-fsdp2/SKILL.md) |
| pytorch-lightning | Lightning 训练 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/08-distributed-training/pytorch-lightning/SKILL.md](AI-Research-SKILLs/08-distributed-training/pytorch-lightning/SKILL.md) |
| ray-train | Ray 分布式训练 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/08-distributed-training/ray-train/SKILL.md](AI-Research-SKILLs/08-distributed-training/ray-train/SKILL.md) |
| training-llms-megatron | Megatron 训练 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/08-distributed-training/megatron-core/SKILL.md](AI-Research-SKILLs/08-distributed-training/megatron-core/SKILL.md) |

### 数据处理

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| nemo-curator | NeMo 数据清洗 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/05-data-processing/nemo-curator/SKILL.md](AI-Research-SKILLs/05-data-processing/nemo-curator/SKILL.md) |
| ray-data | Ray 数据处理 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/05-data-processing/ray-data/SKILL.md](AI-Research-SKILLs/05-data-processing/ray-data/SKILL.md) |

### 优化与量化

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| awq-quantization | AWQ 量化 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/10-optimization/awq/SKILL.md](AI-Research-SKILLs/10-optimization/awq/SKILL.md) |
| gguf-quantization | GGUF/llama.cpp | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/10-optimization/gguf/SKILL.md](AI-Research-SKILLs/10-optimization/gguf/SKILL.md) |
| gptq | GPTQ 量化 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/10-optimization/gptq/SKILL.md](AI-Research-SKILLs/10-optimization/gptq/SKILL.md) |
| hqq-quantization | HQQ 量化 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/10-optimization/hqq/SKILL.md](AI-Research-SKILLs/10-optimization/hqq/SKILL.md) |
| ml-training-recipes | 训练配方 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/10-optimization/ml-training-recipes/SKILL.md](AI-Research-SKILLs/10-optimization/ml-training-recipes/SKILL.md) |
| optimizing-attention-flash | FlashAttention 优化 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/10-optimization/flash-attention/SKILL.md](AI-Research-SKILLs/10-optimization/flash-attention/SKILL.md) |
| quantizing-models-bitsandbytes | bitsandbytes 量化 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/10-optimization/bitsandbytes/SKILL.md](AI-Research-SKILLs/10-optimization/bitsandbytes/SKILL.md) |

### 推理服务

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| llama-cpp | llama.cpp 推理 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/12-inference-serving/llama-cpp/SKILL.md](AI-Research-SKILLs/12-inference-serving/llama-cpp/SKILL.md) |
| serving-llms-vllm | vLLM 推理服务 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/12-inference-serving/vllm/SKILL.md](AI-Research-SKILLs/12-inference-serving/vllm/SKILL.md) |
| sglang | SGLang 服务 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/12-inference-serving/sglang/SKILL.md](AI-Research-SKILLs/12-inference-serving/sglang/SKILL.md) |
| tensorrt-llm | TensorRT-LLM | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/12-inference-serving/tensorrt-llm/SKILL.md](AI-Research-SKILLs/12-inference-serving/tensorrt-llm/SKILL.md) |

### 评测

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| evaluating-code-models | 代码模型评测 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/11-evaluation/bigcode-evaluation-harness/SKILL.md](AI-Research-SKILLs/11-evaluation/bigcode-evaluation-harness/SKILL.md) |
| evaluating-llms-harness | LLM 基准评测 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/11-evaluation/lm-evaluation-harness/SKILL.md](AI-Research-SKILLs/11-evaluation/lm-evaluation-harness/SKILL.md) |
| nemo-evaluator-sdk | NeMo 评测 SDK | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/11-evaluation/nemo-evaluator/SKILL.md](AI-Research-SKILLs/11-evaluation/nemo-evaluator/SKILL.md) |

### MLOps

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| experiment-tracking-swanlab | SwanLab 跟踪 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/13-mlops/swanlab/SKILL.md](AI-Research-SKILLs/13-mlops/swanlab/SKILL.md) |
| mlflow | MLflow 实验管理 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/13-mlops/mlflow/SKILL.md](AI-Research-SKILLs/13-mlops/mlflow/SKILL.md) |
| tensorboard | TensorBoard 可视化 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/13-mlops/tensorboard/SKILL.md](AI-Research-SKILLs/13-mlops/tensorboard/SKILL.md) |
| weights-and-biases | W&B 实验跟踪 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/13-mlops/weights-and-biases/SKILL.md](AI-Research-SKILLs/13-mlops/weights-and-biases/SKILL.md) |

### 云/GPU 基础设施

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| lambda-labs-gpu-cloud | Lambda GPU 云 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/09-infrastructure/lambda-labs/SKILL.md](AI-Research-SKILLs/09-infrastructure/lambda-labs/SKILL.md) |
| modal-serverless-gpu | Modal GPU 云 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/09-infrastructure/modal/SKILL.md](AI-Research-SKILLs/09-infrastructure/modal/SKILL.md) |
| skypilot-multi-cloud-orchestration | SkyPilot 多云 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/09-infrastructure/skypilot/SKILL.md](AI-Research-SKILLs/09-infrastructure/skypilot/SKILL.md) |

### Agent 框架

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| autogpt-agents | AutoGPT Agent | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/14-agents/autogpt/SKILL.md](AI-Research-SKILLs/14-agents/autogpt/SKILL.md) |
| crewai-multi-agent | CrewAI 多智能体 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/14-agents/crewai/SKILL.md](AI-Research-SKILLs/14-agents/crewai/SKILL.md) |
| evolving-ai-agents | Agent 自动进化 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/14-agents/a-evolve/SKILL.md](AI-Research-SKILLs/14-agents/a-evolve/SKILL.md) |
| langchain | LangChain 应用 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/14-agents/langchain/SKILL.md](AI-Research-SKILLs/14-agents/langchain/SKILL.md) |
| llamaindex | LlamaIndex RAG | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/14-agents/llamaindex/SKILL.md](AI-Research-SKILLs/14-agents/llamaindex/SKILL.md) |

### RAG/向量检索

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| chroma | Chroma 向量库 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/15-rag/chroma/SKILL.md](AI-Research-SKILLs/15-rag/chroma/SKILL.md) |
| faiss | FAISS 向量检索 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/15-rag/faiss/SKILL.md](AI-Research-SKILLs/15-rag/faiss/SKILL.md) |
| pinecone | Pinecone 向量库 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/15-rag/pinecone/SKILL.md](AI-Research-SKILLs/15-rag/pinecone/SKILL.md) |
| qdrant-vector-search | Qdrant 向量库 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/15-rag/qdrant/SKILL.md](AI-Research-SKILLs/15-rag/qdrant/SKILL.md) |
| sentence-transformers | 句向量嵌入 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/15-rag/sentence-transformers/SKILL.md](AI-Research-SKILLs/15-rag/sentence-transformers/SKILL.md) |

### 提示/结构化输出

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| dspy | DSPy 编程 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/16-prompt-engineering/dspy/SKILL.md](AI-Research-SKILLs/16-prompt-engineering/dspy/SKILL.md) |
| guidance | Guidance 约束生成 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/16-prompt-engineering/guidance/SKILL.md](AI-Research-SKILLs/16-prompt-engineering/guidance/SKILL.md) |
| instructor | 结构化抽取 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/16-prompt-engineering/instructor/SKILL.md](AI-Research-SKILLs/16-prompt-engineering/instructor/SKILL.md) |
| outlines | Outlines 结构生成 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/16-prompt-engineering/outlines/SKILL.md](AI-Research-SKILLs/16-prompt-engineering/outlines/SKILL.md) |

### 观测追踪

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| langsmith-observability | LangSmith 观测 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/17-observability/langsmith/SKILL.md](AI-Research-SKILLs/17-observability/langsmith/SKILL.md) |
| phoenix-observability | Phoenix 观测 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/17-observability/phoenix/SKILL.md](AI-Research-SKILLs/17-observability/phoenix/SKILL.md) |

### 安全与对齐

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| constitutional-ai | 宪法式对齐 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/07-safety-alignment/constitutional-ai/SKILL.md](AI-Research-SKILLs/07-safety-alignment/constitutional-ai/SKILL.md) |
| llamaguard | LlamaGuard 安全 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/07-safety-alignment/llamaguard/SKILL.md](AI-Research-SKILLs/07-safety-alignment/llamaguard/SKILL.md) |
| nemo-guardrails | NeMo 安全护栏 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/07-safety-alignment/nemo-guardrails/SKILL.md](AI-Research-SKILLs/07-safety-alignment/nemo-guardrails/SKILL.md) |
| prompt-guard | 提示注入防护 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/07-safety-alignment/prompt-guard/SKILL.md](AI-Research-SKILLs/07-safety-alignment/prompt-guard/SKILL.md) |

### 可解释性

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| nnsight-remote-interpretability | nnsight 可解释性 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/04-mechanistic-interpretability/nnsight/SKILL.md](AI-Research-SKILLs/04-mechanistic-interpretability/nnsight/SKILL.md) |
| pyvene-interventions | Pyvene 干预 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/04-mechanistic-interpretability/pyvene/SKILL.md](AI-Research-SKILLs/04-mechanistic-interpretability/pyvene/SKILL.md) |
| sparse-autoencoder-training | SAE 可解释性 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/04-mechanistic-interpretability/saelens/SKILL.md](AI-Research-SKILLs/04-mechanistic-interpretability/saelens/SKILL.md) |
| transformer-lens-interpretability | TransformerLens 解释 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/04-mechanistic-interpretability/transformer-lens/SKILL.md](AI-Research-SKILLs/04-mechanistic-interpretability/transformer-lens/SKILL.md) |

### 多模态

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| audiocraft-audio-generation | 文本生成音频 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/18-multimodal/audiocraft/SKILL.md](AI-Research-SKILLs/18-multimodal/audiocraft/SKILL.md) |
| blip-2-vision-language | BLIP-2 多模态 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/18-multimodal/blip-2/SKILL.md](AI-Research-SKILLs/18-multimodal/blip-2/SKILL.md) |
| clip | CLIP 图文匹配 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/18-multimodal/clip/SKILL.md](AI-Research-SKILLs/18-multimodal/clip/SKILL.md) |
| evaluating-cosmos-policy | 机器人策略评测 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/18-multimodal/cosmos-policy/SKILL.md](AI-Research-SKILLs/18-multimodal/cosmos-policy/SKILL.md) |
| fine-tuning-openvla-oft | OpenVLA 微调 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/18-multimodal/openvla-oft/SKILL.md](AI-Research-SKILLs/18-multimodal/openvla-oft/SKILL.md) |
| fine-tuning-serving-openpi | OpenPI 微调服务 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/18-multimodal/openpi/SKILL.md](AI-Research-SKILLs/18-multimodal/openpi/SKILL.md) |
| llava | LLaVA 视觉语言 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/18-multimodal/llava/SKILL.md](AI-Research-SKILLs/18-multimodal/llava/SKILL.md) |
| segment-anything-model | SAM 图像分割 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/18-multimodal/segment-anything/SKILL.md](AI-Research-SKILLs/18-multimodal/segment-anything/SKILL.md) |
| stable-diffusion-image-generation | Stable Diffusion | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/18-multimodal/stable-diffusion/SKILL.md](AI-Research-SKILLs/18-multimodal/stable-diffusion/SKILL.md) |
| whisper | 语音识别 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/18-multimodal/whisper/SKILL.md](AI-Research-SKILLs/18-multimodal/whisper/SKILL.md) |

### 新兴技术

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| knowledge-distillation | 知识蒸馏 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/19-emerging-techniques/knowledge-distillation/SKILL.md](AI-Research-SKILLs/19-emerging-techniques/knowledge-distillation/SKILL.md) |
| long-context | 长上下文扩展 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/19-emerging-techniques/long-context/SKILL.md](AI-Research-SKILLs/19-emerging-techniques/long-context/SKILL.md) |
| model-merging | 模型合并 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/19-emerging-techniques/model-merging/SKILL.md](AI-Research-SKILLs/19-emerging-techniques/model-merging/SKILL.md) |
| model-pruning | 模型剪枝 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/19-emerging-techniques/model-pruning/SKILL.md](AI-Research-SKILLs/19-emerging-techniques/model-pruning/SKILL.md) |
| moe-training | MoE 训练 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/19-emerging-techniques/moe-training/SKILL.md](AI-Research-SKILLs/19-emerging-techniques/moe-training/SKILL.md) |
| speculative-decoding | 投机解码加速 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/19-emerging-techniques/speculative-decoding/SKILL.md](AI-Research-SKILLs/19-emerging-techniques/speculative-decoding/SKILL.md) |

### 研究创意

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| brainstorming-research-ideas | 研究脑暴 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/21-research-ideation/brainstorming-research-ideas/SKILL.md](AI-Research-SKILLs/21-research-ideation/brainstorming-research-ideas/SKILL.md) |
| creative-thinking-for-research | 创造性选题 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/21-research-ideation/creative-thinking-for-research/SKILL.md](AI-Research-SKILLs/21-research-ideation/creative-thinking-for-research/SKILL.md) |

### ARA 研究工件

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| ara-compiler | ARA 工件编译 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/22-agent-native-research-artifact/compiler/SKILL.md](AI-Research-SKILLs/22-agent-native-research-artifact/compiler/SKILL.md) |
| ara-research-manager | 研究过程归档 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/22-agent-native-research-artifact/research-manager/SKILL.md](AI-Research-SKILLs/22-agent-native-research-artifact/research-manager/SKILL.md) |
| ara-rigor-reviewer | ARA 严谨性审查 | AI-Research-SKILLs | 1 | [AI-Research-SKILLs/22-agent-native-research-artifact/rigor-reviewer/SKILL.md](AI-Research-SKILLs/22-agent-native-research-artifact/rigor-reviewer/SKILL.md) |

### OMX/Codex 编排

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| ai-slop-cleaner | 代码清理降噪 | oh-my-codex | 2 | [oh-my-codex/skills/ai-slop-cleaner/SKILL.md](oh-my-codex/skills/ai-slop-cleaner/SKILL.md) |
| analyze | 代码库深度分析 | oh-my-codex | 2 | [oh-my-codex/skills/analyze/SKILL.md](oh-my-codex/skills/analyze/SKILL.md) |
| ask | 外部模型咨询 | oh-my-codex | 2 | [oh-my-codex/skills/ask/SKILL.md](oh-my-codex/skills/ask/SKILL.md) |
| ask-claude | Claude 兼容入口 | oh-my-codex | 1 | [oh-my-codex/skills/ask-claude/SKILL.md](oh-my-codex/skills/ask-claude/SKILL.md) |
| ask-gemini | Gemini 兼容入口 | oh-my-codex | 1 | [oh-my-codex/skills/ask-gemini/SKILL.md](oh-my-codex/skills/ask-gemini/SKILL.md) |
| autopilot | 全自动执行链 | oh-my-codex | 2 | [oh-my-codex/skills/autopilot/SKILL.md](oh-my-codex/skills/autopilot/SKILL.md) |
| autoresearch | 自动科研循环 | AI-Research-SKILLs, oh-my-codex | 3 | [oh-my-codex/skills/autoresearch/SKILL.md](oh-my-codex/skills/autoresearch/SKILL.md) |
| autoresearch-goal | 目标式自动科研 | oh-my-codex | 2 | [oh-my-codex/skills/autoresearch-goal/SKILL.md](oh-my-codex/skills/autoresearch-goal/SKILL.md) |
| best-practice-research | 最佳实践调研 | oh-my-codex | 2 | [oh-my-codex/skills/best-practice-research/SKILL.md](oh-my-codex/skills/best-practice-research/SKILL.md) |
| build-fix | 构建修复兼容 | oh-my-codex | 1 | [oh-my-codex/skills/build-fix/SKILL.md](oh-my-codex/skills/build-fix/SKILL.md) |
| cancel | 取消工作流 | oh-my-codex | 2 | [oh-my-codex/skills/cancel/SKILL.md](oh-my-codex/skills/cancel/SKILL.md) |
| code-review | 代码审查 | oh-my-codex | 2 | [oh-my-codex/skills/code-review/SKILL.md](oh-my-codex/skills/code-review/SKILL.md) |
| configure-notifications | 通知配置 | oh-my-codex | 2 | [oh-my-codex/skills/configure-notifications/SKILL.md](oh-my-codex/skills/configure-notifications/SKILL.md) |
| deep-interview | 深度访谈澄清 | oh-my-codex | 2 | [oh-my-codex/skills/deep-interview/SKILL.md](oh-my-codex/skills/deep-interview/SKILL.md) |
| deepsearch | 深搜兼容入口 | oh-my-codex | 1 | [oh-my-codex/skills/deepsearch/SKILL.md](oh-my-codex/skills/deepsearch/SKILL.md) |
| design | 产品设计真源 | oh-my-codex | 2 | [oh-my-codex/skills/design/SKILL.md](oh-my-codex/skills/design/SKILL.md) |
| doctor | OMX 诊断修复 | oh-my-codex | 2 | [oh-my-codex/skills/doctor/SKILL.md](oh-my-codex/skills/doctor/SKILL.md) |
| ecomode | 省资源兼容 | oh-my-codex | 1 | [oh-my-codex/skills/ecomode/SKILL.md](oh-my-codex/skills/ecomode/SKILL.md) |
| frontend-ui-ux | 前端体验设计 | oh-my-codex | 1 | [oh-my-codex/skills/frontend-ui-ux/SKILL.md](oh-my-codex/skills/frontend-ui-ux/SKILL.md) |
| git-master | Git 历史管理 | oh-my-codex | 1 | [oh-my-codex/skills/git-master/SKILL.md](oh-my-codex/skills/git-master/SKILL.md) |
| help | OMX 帮助 | oh-my-codex | 1 | [oh-my-codex/skills/help/SKILL.md](oh-my-codex/skills/help/SKILL.md) |
| hud | OMX 状态面板 | oh-my-codex | 2 | [oh-my-codex/skills/hud/SKILL.md](oh-my-codex/skills/hud/SKILL.md) |
| note | 会话笔记 | oh-my-codex | 1 | [oh-my-codex/skills/note/SKILL.md](oh-my-codex/skills/note/SKILL.md) |
| omx-setup | OMX 安装配置 | oh-my-codex | 2 | [oh-my-codex/skills/omx-setup/SKILL.md](oh-my-codex/skills/omx-setup/SKILL.md) |
| performance-goal | 性能目标执行 | oh-my-codex | 2 | [oh-my-codex/skills/performance-goal/SKILL.md](oh-my-codex/skills/performance-goal/SKILL.md) |
| pipeline | OMX 流水线 | oh-my-codex | 2 | [oh-my-codex/skills/pipeline/SKILL.md](oh-my-codex/skills/pipeline/SKILL.md) |
| plan | 执行计划 | oh-my-codex | 2 | [oh-my-codex/skills/plan/SKILL.md](oh-my-codex/skills/plan/SKILL.md) |
| prometheus-strict | 严格执行约束 | oh-my-codex | 2 | [oh-my-codex/skills/prometheus-strict/SKILL.md](oh-my-codex/skills/prometheus-strict/SKILL.md) |
| ralph | 持续完成循环 | oh-my-codex | 2 | [oh-my-codex/skills/ralph/SKILL.md](oh-my-codex/skills/ralph/SKILL.md) |
| ralph-init | Ralph 初始化 | oh-my-codex | 1 | [oh-my-codex/skills/ralph-init/SKILL.md](oh-my-codex/skills/ralph-init/SKILL.md) |
| ralplan | 共识计划 | oh-my-codex | 2 | [oh-my-codex/skills/ralplan/SKILL.md](oh-my-codex/skills/ralplan/SKILL.md) |
| review | 审查兼容入口 | oh-my-codex | 1 | [oh-my-codex/skills/review/SKILL.md](oh-my-codex/skills/review/SKILL.md) |
| security-review | 安全审查兼容 | oh-my-codex | 1 | [oh-my-codex/skills/security-review/SKILL.md](oh-my-codex/skills/security-review/SKILL.md) |
| skill | 技能管理 | oh-my-codex | 2 | [oh-my-codex/skills/skill/SKILL.md](oh-my-codex/skills/skill/SKILL.md) |
| swarm | 团队兼容入口 | oh-my-codex | 1 | [oh-my-codex/skills/swarm/SKILL.md](oh-my-codex/skills/swarm/SKILL.md) |
| tdd | TDD 兼容入口 | oh-my-codex | 1 | [oh-my-codex/skills/tdd/SKILL.md](oh-my-codex/skills/tdd/SKILL.md) |
| team | 多智能体团队 | oh-my-codex | 2 | [oh-my-codex/skills/team/SKILL.md](oh-my-codex/skills/team/SKILL.md) |
| trace | 流程追踪 | oh-my-codex | 1 | [oh-my-codex/skills/trace/SKILL.md](oh-my-codex/skills/trace/SKILL.md) |
| ultragoal | 多目标执行 | oh-my-codex | 2 | [oh-my-codex/skills/ultragoal/SKILL.md](oh-my-codex/skills/ultragoal/SKILL.md) |
| ultraqa | 对抗式 QA | oh-my-codex | 2 | [oh-my-codex/skills/ultraqa/SKILL.md](oh-my-codex/skills/ultraqa/SKILL.md) |
| ultrawork | 并行执行引擎 | oh-my-codex | 2 | [oh-my-codex/skills/ultrawork/SKILL.md](oh-my-codex/skills/ultrawork/SKILL.md) |
| visual-ralph | 视觉还原循环 | oh-my-codex | 2 | [oh-my-codex/skills/visual-ralph/SKILL.md](oh-my-codex/skills/visual-ralph/SKILL.md) |
| visual-verdict | 视觉评估兼容 | oh-my-codex | 1 | [oh-my-codex/skills/visual-verdict/SKILL.md](oh-my-codex/skills/visual-verdict/SKILL.md) |
| web-clone | 网页克隆兼容 | oh-my-codex | 1 | [oh-my-codex/skills/web-clone/SKILL.md](oh-my-codex/skills/web-clone/SKILL.md) |
| wiki | 项目知识库 | oh-my-codex | 2 | [oh-my-codex/skills/wiki/SKILL.md](oh-my-codex/skills/wiki/SKILL.md) |
| worker | 团队 worker 协议 | oh-my-codex | 2 | [oh-my-codex/skills/worker/SKILL.md](oh-my-codex/skills/worker/SKILL.md) |

### 可视化/辅助产物

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| mermaid-diagram | Mermaid 图表 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/mermaid-diagram/SKILL.md](Auto-claude-code-research-in-sleep/skills/mermaid-diagram/SKILL.md) |
| pixel-art | 像素风插图 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/pixel-art/SKILL.md](Auto-claude-code-research-in-sleep/skills/pixel-art/SKILL.md) |

### 其他研究辅助

| Skill | 几词说明 | 来源 | 来源数 | 入口路径 |
|---|---|---|---:|---|
| dse-loop | 设计空间搜索 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/dse-loop/SKILL.md](Auto-claude-code-research-in-sleep/skills/dse-loop/SKILL.md) |
| feishu-notify | 飞书通知 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/feishu-notify/SKILL.md](Auto-claude-code-research-in-sleep/skills/feishu-notify/SKILL.md) |
| interview-cheatsheet | 访谈速查卡 | Auto-claude-code-research-in-sleep | 1 | [Auto-claude-code-research-in-sleep/skills/interview-cheatsheet/SKILL.md](Auto-claude-code-research-in-sleep/skills/interview-cheatsheet/SKILL.md) |
| meta-optimize | 元优化循环 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/meta-optimize/SKILL.md](Auto-claude-code-research-in-sleep/skills/meta-optimize/SKILL.md) |
| qzcli | QZ CLI 工具 | Auto-claude-code-research-in-sleep | 2 | [Auto-claude-code-research-in-sleep/skills/qzcli/SKILL.md](Auto-claude-code-research-in-sleep/skills/qzcli/SKILL.md) |

## 统计

- 扫描到 349 个 SKILL.md。
- 去重后 229 个 skill 名称。
- 去重规则：同名保留一个入口；优先选择非插件镜像、非 `skills-codex*` 镜像、仓库顶层 `skills/<name>/SKILL.md`。