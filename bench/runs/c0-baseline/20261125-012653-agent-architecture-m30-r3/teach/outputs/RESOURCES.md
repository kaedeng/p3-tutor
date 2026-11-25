# Agent architecture Resources

## Knowledge

- [Article: "Effective context engineering for AI agents" (Anthropic)](https://anthropic.com/engineering/effective-context-engineering-for-ai-agents)
  Context rot, compaction, note-taking, just-in-time retrieval, sub-agents. Primary source for context and memory (O3).
- [Docs: Context windows (Claude Platform)](https://platform.claude.com/docs/en/build-with-claude/context-windows)
  What counts toward the window, growth across turns, overflow. Use for: context size questions. Provider-specific figures change.
- [Docs: Working with messages (Claude Platform)](https://platform.claude.com/docs/en/build-with-claude/working-with-messages)
  Stateless API and resending history. Use for: first model calls from code.
- [Help article: What are tokens and how to count them (OpenAI)](https://help.openai.com/en/articles/4936856-what-are-tokens-and-how-to-count-them)
  Token definition, English rules of thumb, token categories in pricing. The ratios are one provider's estimates.
- [Docs: Memory overview (LangChain)](https://docs.langchain.com/oss/python/concepts/memory)
  Short-term and long-term memory; semantic, episodic, procedural; when to write memories.
- [Article: "Contextual Retrieval" (Anthropic, 2024)](https://anthropic.com/news/contextual-retrieval)
  Chunking, BM25 and embeddings, when to put everything in the prompt. Use for: manual search design.
- [Paper: "Lost in the Middle" by Liu et al.](https://arxiv.org/abs/2307.03172)
  Position effects in long contexts (2023 models; only the abstract was read).

## Wisdom (Communities)

- [Hugging Face Agents Course Discord](https://huggingface.co/learn/agents-course/en/unit0/discord101)
  Channels for questions and showing agents. Use for: design feedback.
