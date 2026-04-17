# Daniel Quillan Roxas

Master's student in Applied Data Science at [TED University](https://www.tedu.edu.tr/), doing research in biomedical AI. I work on retrieval-augmented generation, large language models, and knowledge graphs for healthcare.

---

### Projects

- [**Etymograph**](https://github.com/danielquillanroxas/etymograph) - Etymology knowledge graph explorer built on 22.7M relations across 6.6M words in 5,529 languages. Trace any word's origins, find connections between words across languages, compare cognates side by side, and explore ancestor/descendant chains. Unified from 5 open etymology datasets into a single queryable graph. Python/FastAPI + React/Cytoscape.js. | [Dataset on HuggingFace](https://huggingface.co/datasets/danielquillanroxas/etymograph-unified)

- [**Wikinnections**](https://github.com/danielquillanroxas/wikinnections) - Knowledge graph explorer that finds and visualizes connections between any two entities using Wikidata. Bidirectional BFS pathfinding, interactive graph visualization, popularity-based filtering, and clickable edges/nodes to block shortcuts and force creative paths. Python/FastAPI + React/Cytoscape.js. [wikinnections.onrender.com](https://wikinnections.onrender.com/)

- [**Token by Token**](https://github.com/danielquillanroxas/token-by-token) - Collaborative blog breaking down ML, NLP, and AI concepts. Built with Astro. [token-by-token.com](https://token-by-token.com/)

### Publications

- [**Comparative Analysis of Medical-Domain and General-Purpose Large Language Models**](https://dergipark.org.tr/tr/pub/politeknik/article/1719005) - *Journal of Polytechnic*
  Evaluated 8 LLMs across 11,000 medical Q&A pairs. General-purpose models outperformed domain-specific ones across all metrics.

- [**Dissecting Medical RAG: Why Reranking Matters More Than Complexity in Question Answering**](https://dergipark.org.tr/en/pub/bsengineering/article/1849342) - *Black Sea Journal of Engineering*
  Ablation study across 7 RAG configurations on 476 medical questions. Reranking turned out to be essential while added complexity hurt performance.

### Current Research

- **PubMed-GraphRAG** (Master's Thesis) - Hybrid FAISS + Neo4j retrieval over 12.5M PubMed papers (20M nodes, 266M relationships) | [Dataset](https://huggingface.co/datasets/danielquillanroxas/pubmed-graphrag-data) | [Project Website](https://thesis-lime-delta.vercel.app)
- **EmTR-TTS** - Emotion-controllable Turkish TTS via fine-tuning F5-TTS with emotion tag tokens on curated Turkish emotional speech data. Paper website: [danielquillanroxas.github.io/turkish-tts-survey](https://danielquillanroxas.github.io/turkish-tts-survey)

### Teaching

- Built the course materials for [ADS525: Generative AI Engineering with LLMs](https://github.com/hemekci/ADS525) as a graduate TA
