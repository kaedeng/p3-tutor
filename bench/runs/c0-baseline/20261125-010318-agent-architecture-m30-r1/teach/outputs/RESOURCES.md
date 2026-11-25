# Agent architecture Resources

## Knowledge

- [Article: "Effective context engineering for AI agents" (Anthropic Engineering, 2025)](https://anthropic.com/engineering/effective-context-engineering-for-ai-agents)
  Practitioner advice from one model provider. Use for: limited context, context rot, just-in-time retrieval, compaction, note-taking.
- [Docs: Context windows](https://platform.claude.com/docs/en/build-with-claude/context-windows)
  One provider's reference. Use for: what counts toward the window, what happens at the limit.
- [Docs: Glossary](https://platform.claude.com/docs/en/about-claude/glossary)
  Use for: definitions of token, context window and RAG.
- [Docs: Working with messages](https://platform.claude.com/docs/en/build-with-claude/working-with-messages)
  Use for: statelessness and resending history; first real model calls from code.
- [Docs: Pricing](https://platform.claude.com/docs/en/about-claude/pricing)
  Use for: how input, output, tool and cached tokens are charged. Prices change, so reread before budgeting.
- [Docs: Conversation state (OpenAI)](https://developers.openai.com/api/docs/guides/conversation-state)
  Seen in search results only, not opened in full. Use for: server-stored history and how it is billed.
- [Docs: Memory overview (LangChain)](https://docs.langchain.com/oss/python/concepts/memory)
  Use for: short-term and long-term memory, kinds of memory, when to write memories.
- [Article: "Contextual Retrieval" (Anthropic Engineering, 2024)](https://www.anthropic.com/engineering/contextual-retrieval)
  Use for: chunking, keyword and embedding search, chunks that lose context, when to skip retrieval.

## Wisdom (Communities)

- [LangChain community forum](https://forum.langchain.com/latest?page=1)
  Tied to one framework; seen in search results, moderation quality not checked. Use for: feedback on memory designs.
