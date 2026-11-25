# Agent architecture Resources

## Knowledge

- [Article: "Effective context engineering for AI agents" (Anthropic engineering, Sep 2025)](https://anthropic.com/engineering/effective-context-engineering-for-ai-agents)
  Context rot, compaction, note-taking, just-in-time retrieval, sub-agents. Primary source for O3; use for context design.
- [Docs: Context windows (Claude Platform)](https://platform.claude.com/docs/en/build-with-claude/context-windows)
  What counts toward the window and overflow behavior, for one API. Use for: limits.
- [Docs: Working with messages (Claude Platform)](https://platform.claude.com/docs/en/build-with-claude/working-with-messages)
  Stateless API and resending history. Use for: first calls from code.
- [Docs: Memory tool (Claude Platform)](https://platform.claude.com/docs/en/agents-and-tools/tool-use/memory-tool)
  Client-side memory files and security safeguards. Use for: saving notes between sessions.
- [Docs: Glossary (Claude Platform)](https://platform.claude.com/docs/en/about-claude/glossary)
  Tokens, context window, RAG. Use for: definitions.
- [Docs: Pricing (Claude Platform)](https://platform.claude.com/docs/en/about-claude/pricing)
  Per-million-token input and output rates. Seen in search results only; open it before quoting any price.
- [Docs: Memory overview (LangChain)](https://docs.langchain.com/oss/python/concepts/memory)
  Short-term and long-term memory, writing during or after a task.
- [Article: "Contextual Retrieval" (Anthropic)](https://www.anthropic.com/news/contextual-retrieval)
  Chunking, BM25, embeddings, context lost by chunks. Use for: searching the manuals.
- [Paper: "Lost in the Middle" (Liu et al.)](https://arxiv.org/abs/2307.03172)
  Position effects in long inputs (2023 models). Use for: why not to stuff the context.
- [Paper: "Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks" (Lewis et al., 2020)](https://arxiv.org/abs/2005.11401)
  Origin of the term RAG; research level, optional.

## Wisdom (Communities)

- [Hugging Face Agents Course Discord](https://huggingface.co/learn/agents-course/en/unit0/discord101)
  Course community. Use for: critique of a memory plan or agent design. Riley has not said whether they want to join one.
