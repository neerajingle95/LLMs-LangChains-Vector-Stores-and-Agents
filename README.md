# LLMs-LangChains-Vector-Stores-and-Agents

🚀 Building an Agentic AI System using LangChain + Together.ai
Just wrapped up a project (in 1 day!) where I built a fully working Agentic AI system using:
🔗 LangChain for orchestration
 Mistral 7B for priming, creating/using prompt templates
 Document chunking
 Creating embeddings using Hugging Face
 Storing embeddings in Pinecone's vector database
🧠 Together AI’s Mistral 7B model as the reasoning engine
🛠️ Python REPL tool for dynamic code execution

🧩 What does it do?
Given a natural language task like:
"Find the roots of the quadratic function 3x² + 2x - 1"
…the agent automatically decides to write and execute Python code to solve it. No manual coding needed — the LLM takes care of the entire reasoning + computation flow.

⚙️ Tech Behind the Scenes:
✅ LLM via Together.ai (Mistral 7B - Instruct)
✅ Tool calling with LangChain’s PythonREPLTool
✅ Agent built using create_tool_calling_agent()
✅ Custom prompt with agent_scratchpad for tool tracking
✅ Executed inside a Jupyter notebook environment

🧠 GenAI Skills Demonstrated:
Agent-based LLM reasoning
Prompt engineering & tool integration
Together.ai API usage
LangChain’s agentic framework
Real-time execution with external tools

💡 This is a great foundation for more advanced systems like:
RAG (Retrieval-Augmented Generation)
Multi-tool agents (search, DB queries, etc.)
Autonomous task chains using LangGraph
