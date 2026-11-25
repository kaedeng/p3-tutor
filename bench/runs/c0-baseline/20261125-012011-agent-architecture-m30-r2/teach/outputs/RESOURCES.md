# Agent architecture Resources

## Knowledge

- [Effective context engineering for AI agents (Anthropic)](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)
  Practitioner guide to what goes into context: limited attention, just-in-time retrieval, compaction, note-taking, sub-agents. Primary source for lesson 1. Use for: context and memory design.
- [Context windows (Claude Platform Docs)](https://platform.claude.com/docs/en/build-with-claude/context-windows)
  Official provider documentation. Use for: what counts toward the window, overflow behavior, context rot.
- [Using the Messages API (Claude Platform Docs)](https://platform.claude.com/docs/en/build-with-claude/working-with-messages)
  Official documentation. Use for: stateless calls and sending conversation history.
- [Glossary (Claude Platform Docs)](https://platform.claude.com/docs/en/about-claude/glossary)
  Official definitions. Use for: token, context window, RAG.
- [Pricing (Claude Platform Docs)](https://platform.claude.com/en/docs/about-claude/pricing)
  Official per-million-token billing; seen in search results only, not opened. Use for: how cost is metered. Check live figures before quoting any.
- [Memory overview (LangChain docs)](https://docs.langchain.com/oss/python/concepts/memory)
  Framework documentation. Use for: short-term and long-term memory, memory types, when to write memory.
- [Contextual retrieval (Anthropic)](https://www.anthropic.com/engineering/contextual-retrieval)
  Engineering write-up with measurements. Use for: chunking, BM25, embeddings, hybrid search, when to skip retrieval.
- [Lost in the Middle (Liu et al., arXiv 2307.03172)](https://arxiv.org/abs/2307.03172v3)
  Research paper; only the abstract was read. Use for: position effects in long contexts.

## Wisdom (Communities)

- [Hugging Face Agents Course Discord](https://huggingface.co/learn/agents-course/unit0/discord101)
  Course community with questions and showcase channels. Use for: critique of a design, debugging help.
