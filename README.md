# VanceF's Agents Adventures

Welcome to my collection of AI agents! In this repository, you’ll find various agents that I have built to enhance my skills and tackle different challenges. Each agent serves a unique purpose, and I hope you find them useful—or at least entertaining. Who knows, one of these might even start thinking for itself and attempt to conquer the world… (Just kidding 👀)

**Note**: While building these agents, I’ve tried to avoid using third-party frameworks (like LangChain and LangGraph) as much as possible, embracing the power of pure Python from scratch. However, for some of the more complex agentic systems, I did resort to using frameworks (😑). In the future, I may add some pure Python implementations to those, so stay tuned!

## Table of Contents

- [Agent 1: Self-Improving Agent](./self_improving_agent.ipynb) - This agent *tries* to improve itself. It might get better, or it might just become really good at overthinking. You decide.
- [Agent 2: Memory-Enhanced Conversational Agent](./memory_enhanced_conversational_agent.ipynb) - Because sometimes, it’s nice to not be forgotten after an intense 2-minute conversation.
- [Agent 3: Self-Healing Codebase Agentic Workflow](./self_healing_code.ipynb) - Code that heals itself. No more crying over broken builds. 🎉
- [Agent 4: Taskifier - Intelligent Task Allocation & Management](./taskifier.ipynb) - Ever wish you could delegate your tasks to a robot? Well, now you can, but only if the robot feels like it. 😜
- [Agent 5: GenAI Career Assistant Agent](./agent_hackathon_genAI_career_assistant.ipynb) - Get career advice from a machine! Spoiler: It probably knows more than you do. 😆
- [Agent 6: AInsight: AI/ML Weekly News Reporter](./ainsight_langgraph.ipynb) - Keeping you updated on AI/ML news, because who has time to read the full articles? You’re busy, after all!
- [Agent 7: History and Data Analysis Collaboration System](./multi_agent_collaboration_system.ipynb) - For when your agents just can’t stop debating the meaning of history.
- [Agent 8: News TL;DR using Langgraph (Too Long Didn't Read)](./news_tldr_langgraph.ipynb) - The agent who cuts through the noise. Because, let’s be honest, who reads the whole article anyway? 😅
- [Agent 9: PaperMind: Intelligent paper search assistant](./scientific_paper_agent.ipynb) - Because parsing through a hundred research papers should feel like a superpower, not a punishment. 🔍📚
- [Agent 10: Systematic Review Agent](./systematic_review_of_scientific_articles.ipynb) - Automates the process of creating systematic reviews of academic papers. From searching for papers to generating a final draft, this agent makes literature reviews feel less like a chore and more like magic. ✨
- More soon... (I’m still waiting for them to get their act together.)

## Environment Variables

Before running any of the agents, make sure to set up the necessary environment variables.  
Copy the `.env.example` file and rename it to `.env`:

```bash
# OpenAI API Key (required) and Base URL (optional)
OPENAI_API_KEY=
OPENAI_BASE_URL=

# DeepSeek API Key (required) and Base URL (optional)
DEEPSEEK_API_KEY=
DEEPSEEK_BASE_URL=

# Anthropic API Key (required) and Base URL (optional)
ANTHROPIC_API_KEY=
ANTHROPIC_BASE_URL=

# Google API Key (required) and Base URL (optional)
GOOGLE_API_KEY=
GOOGLE_BASE_URL=

# Tavily API Key (required)
TAVILY_API_KEY=

# News API Key (required)
NEWS_API_KEY=

# CORE API Key (required)
CORE_API_KEY=
```

Make sure you have the required API keys to access external services. Without these, some agents may not function as expected.

## Contributing

Feel free to fork this repository and submit issues or pull requests. I'm always open to suggestions for improvements, so don’t hesitate to contribute if you see something that could be enhanced. If you have a better idea for an agent that can bring me snacks, even better. 🍕


