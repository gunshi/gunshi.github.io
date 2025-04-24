---
title: "Memo: Training Memory-Efficient Embodied Agents with Reinforcement Learning"
authors:
- admin
- Karmesh Yadav
- Zsolt Kira
- Yarin Gal
- Rahaf Aljundi


date: "2025-04-01T00:00:00Z"
publishDate: "2025-04-01T00:00:00Z"

# doi: ""

# # Schedule page publish date (NOT publication's date).
# publishDate: "2020-10-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# featured: tfalserue

# Publication name and optional abbreviated publication name.
publication: Under Review
# publication_short: Accepted *NeurIPS 2024 spotlight*

abstract: To enable embodied agents to assist and operate effectively over extended timeframes, it is crucial to develop models capable of forming and accessing memories to remain contextualized in an environment. In the current paradigm of training transformer-based policies for embodied sequential decision-making tasks, visual inputs often overwhelm the context limits of transformers, while humans can maintain and utilize a lifetime of experience compressed as memories.Significant compression of raw experience is possible in principle, as large portions of information are irrelevant and can be abstracted and compressed. However, existing approaches predominantly focus on either recurrent models with fixed-size memory or transformers with full-context reliance. In this work, we propose Memo, a transformer-based architecture and training recipe for reinforcement learning on memory-intensive, long-horizon tasks. Memo incorporates the creation and retrieval of memory by interleaving periodic summarization tokens with the input-output of a model during training. We demonstrate Memo's effectiveness on a grid-world meta-reinforcement learning benchmark and a multi-object navigation task in photo-realistic indoor settings. Memo outperforms naive long-context transformer baselines while being more compute - and storage - efficient.  Additionally, Memo generalizes better to longer contexts at inference time and remains robust in streaming settings, where historical context must be truncated to fit inference constraints.


tags:
- Transformers
- RL
- Mmeory

---
