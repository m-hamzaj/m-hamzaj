# Muhammad Hamza Javaid

AI automation developer based in Lahore, Pakistan. I build RAG pipelines, tool-calling agents, and n8n automation — and I measure them against a real eval set instead of eyeballing whether they work.

## Currently building

**[rag](https://github.com/m-hamzaj/rag)** — question answering over a scraped article corpus, evaluated end-to-end against a hand-written question set. Chunk → embed → retrieve → cite, then a LangChain tool-calling agent for questions one retrieval pass can't answer.

- 18/20 (90%) answer-correct baseline, reached by sweeping chunk size and retrieval mode against the same eval set and picking the winner with evidence
- Agent measured head-to-head against plain RAG: wins on multi-hop questions plain RAG fails outright, loses on the easy set at several times the cost and latency — the tradeoff is written down, not assumed

## Other projects

- **[saas-sales-bot](https://github.com/m-hamzaj/saas-sales-bot)** — RAG-powered sales support chatbot
- **[ai-lead-qualification-system](https://github.com/m-hamzaj/ai-lead-qualification-system)** — automated lead scoring
- **[ai-cv-screener](https://github.com/m-hamzaj/ai-cv-screener)** — CV/resume screening agent
- **[AgriSage](https://github.com/m-hamzaj/AgriSage-)** — crop disease detection with a CNN

## Also

- [Portfolio site](https://portfolio-mu-lovat-9ptcmwjghw.vercel.app) — Next.js, Tailwind

## Stack

`Python` `JavaScript` `LangChain` `n8n` `ChromaDB` `OpenAI` `Groq` `Flask` `Streamlit`

## Reach me

[Email](mailto:mhamzajavaid370@gmail.com) · [LinkedIn](https://www.linkedin.com/in/m-hamzaj70) · [GitHub](https://github.com/m-hamzaj)
