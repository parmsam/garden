# How Claude handles memory via tool calls

I recently stumbled upon a [blog post](https://simonwillison.net/2025/Sep/12/claude-memory/) by Simon Willison discussing how Claude has implemented memory. It turns out they use two tool calls to search previous conversations (`conversation_search`) and get recent conversations (`recent_chats`). The blog post is a great read, so I recommend checking it out. Knowing how Claude handles memory is useful, especially if you like Simon prefer a "clean state" approach to conversations. 

## Comparison with OpenAI

Claude has a simpler approach than how OpenAI does it. OpenAI uses AI-generated summaries (which they call "memories") of past conversations in combination with recent chats. They even let you manage the saved memories in the [personalization section](https://chatgpt.com/#settings/Personalization) of their settings. It seems like Claude might also be moving toward this approach in the future.

## How memory works in privacy modes

It's good to see that OpenAI and Claude both have incognito/temporary chat modes which don't save that chat to your history or memory.

> "This chat won't appear in history, use or update ChatGPT's memory, or be used to train our models. For safety purposes, we may keep a copy of this chat for up to 30 days." 
- OpenAI

> "Incognito chats aren’t saved to history or used to train models. [Learn more](https://privacy.claude.com/en/articles 10023580-is-my-data-used-for-model-training) about how your data is used."
- Claude

## Official documentation

This led me the the [doc page](https://support.claude.com/en/articles/11817273-using-claude-s-chat-search-and-memory-to-build-on-previous-context) from Claude and [doc page](https://help.openai.com/en/articles/8590148-memory-faq) from OpenAI on this topic just to confirm.

## Takeaway

This post was great to show me how different LLM providers are approaching memory. I'll be interested to see how this evolves over time. I'd also love to implement my own version of this in a small chatbot app.

## References

- [Simon Willison's blog post on Claude memory](https://simonwillison.net/2025/Sep/12/claude-memory/)
- [Claude's doc on chat search and memory](https://support.claude.com/en
/articles/11817273-using-claude-s-chat-search-and-memory-to-build-on-previous-context)
- [OpenAI's doc on memory FAQ](https://help.openai.com/en/articles/
8590148-memory-faq)