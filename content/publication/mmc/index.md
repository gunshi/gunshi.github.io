---
title: "Recurrent Attention-based Token Selection for Efficient Streaming Video-LLMs"
authors:
- Vaggelis Dorovatas
- Soroush Seifi
- admin
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

abstract: Video Large Language Models (Video-LLMs) excel at understanding videos in-context, assuming full access to the video when answering queries. However, these models face challenges in streaming scenarios where hour-long videos must be processed online, and questions need timely responses. In this work, we propose a training-free approach compatible with standard Video-LLMs, leveraging three key concepts- 1) LLM-informed selection of visual tokens to identify those that the LLM has attended to and contributed to its understanding of each short clip. Our attention-based selection allows us to discard up to ~95% of unimportant visual tokens with minimal performance loss; 2) Hierarchical selection of tokens combined with natural language understanding of each processed clip; 3) Caption-based question answering for lightweight and accurate responses. Our method achieves state-of-the-art performance on streaming video benchmarks, striking a balance between efficiency and effectiveness.


tags:
- Video QA
- VLM
- Memory

---
