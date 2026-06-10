# Daniel Quillan Roxas

Master's student in Applied Data Science at [TED University](https://www.tedu.edu.tr/), Ankara, working in biomedical NLP and speech technology for under-resourced languages. I build the systems, datasets, and benchmarks this research needs, and I try to evaluate them honestly: pre-registered where it counts, with proper uncertainty and limitations stated plainly. Native Filipino speaker.

**Focus areas**
- Biomedical retrieval and knowledge graphs: RAG, evidence, and claim reliability
- Speech for under-resourced languages: Turkish and Filipino TTS, emotion, and clinical safety
- Open datasets, libraries, and benchmarks for languages mainstream models underserve

---

### Projects

- [**Etymograph**](https://github.com/danielquillanroxas/etymograph): Etymology knowledge graph explorer over **22.7M relations across 6.6M words in 5,529 languages**, unified from five open datasets into a single queryable graph. Trace a word's origins, compare cognates side by side, and follow ancestor/descendant chains. Python/FastAPI with React/Cytoscape.js. [Dataset on HuggingFace](https://huggingface.co/datasets/danielquillanroxas/etymograph-unified).

- [**Wikinnections**](https://github.com/danielquillanroxas/wikinnections): Finds and visualizes the shortest paths between any two Wikidata entities via bidirectional BFS, with popularity-based filtering and clickable edges and nodes to block shortcuts and force creative paths. Python/FastAPI with React/Cytoscape.js. [Live demo](https://wikinnections.onrender.com/).

- [**faker-ph**](https://github.com/danielquillanroxas/faker-ph): Open-source Python library for **Philippine-specific synthetic PII** (`pip install faker-ph`). Generates PhilSys (PSN/PCN), TIN, SSS, PhilHealth, PRC, passport and bank numbers, PSGC-backed addresses across 42,036 barangays, and origin-stratified Filipino names. Ships document templates that render to text with character-offset gold PII spans for NLP evaluation. Apache-2.0.

- [**Token by Token**](https://github.com/danielquillanroxas/token-by-token): Collaborative blog breaking down ML, NLP, and AI concepts, one token at a time. Built with Astro. [token-by-token.com](https://token-by-token.com/).

- [**arxiv-sectionizer**](https://github.com/danielquillanroxas/arxiv-sectionizer): Zero-dependency Python tool that extracts semantic sections (limitations, future work, conclusion) from arXiv LaTeX sources.

---

### Publications

- [**Comparative Analysis of Medical-Domain and General-Purpose Large Language Models**](https://dergipark.org.tr/tr/pub/politeknik/article/1719005), *Journal of Polytechnic*. Evaluated 8 LLMs across 11,000 medical Q&A pairs; general-purpose models outperformed domain-specific ones on every metric.

- [**Dissecting Medical RAG: Why Reranking Matters More Than Complexity in Question Answering**](https://dergipark.org.tr/en/pub/bsengineering/article/1849342), *Black Sea Journal of Engineering*. Ablation across 7 RAG configurations on 476 medical questions; reranking proved essential while added complexity hurt performance.

---

### In progress

- **PubMed-GraphRAG** (Master's thesis): Hybrid FAISS and Neo4j retrieval over **12.5M PubMed papers** (20M nodes, 266M relationships). [Dataset](https://huggingface.co/datasets/danielquillanroxas/pubmed-graphrag-data), [thesis site](https://thesis-lime-delta.vercel.app).
- **Clinical TTS safety benchmark**: A floor-calibrated benchmark measuring whether text-to-speech systems render drug names closer to their dangerous look-alike/sound-alike (LASA) confusion partners than to the intended drug. Targeting Interspeech / BioNLP.
- **Pre-registered biomedical evidence audit**: A pre-registered robustness audit of claim-level retraction-proneness in a biomedical knowledge graph, validated against independent retraction and medical-reversal gold.
- **EmTR-TTS**: Emotion-controllable Turkish TTS by fine-tuning F5-TTS with emotion-tag tokens. [Survey site](https://danielquillanroxas.github.io/turkish-tts-survey).
- **FilPII**: A Filipino PII-detection benchmark for privacy-preserving clinical NLP, built on `faker-ph`.

---

### Teaching

- Built the course materials for [**ADS525: Generative AI Engineering with LLMs**](https://github.com/hemekci/ADS525) as a graduate teaching assistant.

---

### Elsewhere

- HuggingFace: [@danielquillanroxas](https://huggingface.co/danielquillanroxas)
- Thesis: [project site](https://thesis-lime-delta.vercel.app)
- Blog: [token-by-token.com](https://token-by-token.com/)
- Email: danielquillanr@gmail.com
