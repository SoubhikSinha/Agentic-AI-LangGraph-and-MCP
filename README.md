# Human-in-the-Loop AI @ `LangGraph`

This repo demonstrates the implementation of conversational AI systems using **LangGraph** with a focus on both basic chatbot orchestration and **human-in-the-loop (HITL)** agent workflows. The `1-basicChatBot.ipynb` notebook introduces a foundational chatbot pipeline built using `langgraph`, `langchain`, and Groq-powered LLM integrations, showcasing stateful conversational flow management and modular graph execution. The `humanInTheLoop.ipynb` notebook extends this into interactive agentic workflows where human intervention can pause, guide, validate, or modify execution paths during runtime, enabling safer and more controllable AI systems. The project also integrates external tooling through `langchain_tavily` for web-enhanced responses and uses `langsmith` for tracing, debugging, and observability of graph executions. Overall, the implementation highlights graph-based conversational orchestration, runtime control mechanisms, human oversight in agentic systems, and scalable workflow design patterns for production-oriented AI applications.

<br>
<br>

## References
[Krish Naik](https://github.com/krishnaik06)<br>
[LangGraph](https://github.com/langchain-ai/langgraph)<br>
[LangChain](https://github.com/langchain-ai/langchain)<br>
[LangSmith](https://github.com/langchain-ai/langsmith-sdk)<br>
[Tavily Search](https://github.com/tavily-ai/tavily-python)
