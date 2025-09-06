# AI Agent Development Practice

This repository contains tutorials and practical examples for building AI agents using modern frameworks like SmoLAgents and LangGraph. The project progresses from basic tool concepts to multi-agent workflows, culminating in a practical sales intelligence agent.

## Project Structure

```
├── tools.ipynb # Introduction to AI tools and tool integration
├── first_smolagents.ipynb # SmoLAgents framework tutorial
├── langgraph_agent.ipynb # LangGraph framework tutorial
├── SalesHelper.ipynb # Complete sales intelligence agent
└── README.md # This file
```

## Learning Path

1. **Start with `tools.ipynb`** - Learn the fundamentals of AI tools
2. **Continue with `first_smolagents.ipynb`** - Build your first agent with SmoLAgents
3. **Explore `langgraph_agent.ipynb`** - Understand stateful workflows with LangGraph
4. **Apply knowledge with `SalesHelper.ipynb`** - Build a real-world application

## 🔧 Setup Instructions

### Installation

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd ai-agent-tutorial
   ```

2. **Create a virtual environment**

   ```bash
   python -m venv venv

   # On Windows
   venv\Scripts\activate

   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

### Environment Variables

Create a `.env` file in the project root with your API keys:

```env
# For AWS Bedrock (saleshelper)
AWS_ACCESS_KEY_ID=your_aws_access_key
AWS_SECRET_ACCESS_KEY=your_aws_secret_key

# For Hugging Face
HUGGINGFACE_API_TOKEN=your_hf_token

# For observability (first_smolagents)
LANGFUSE_SECRET_KEY=your_langfuse_secret
LANGFUSE_PUBLIC_KEY=your_langfuse_public
LANGFUSE_HOST= your_langfuse_host
```

## 📚 File Descriptions

### 1. tools.ipynb - AI Tools Foundation

**Purpose**: Introduces the concept of AI tools and how they integrate with language models.

**What you'll learn**:

- Basic tool structure and components
- Using the `@tool` decorator
- Tool schemas and argument validation
- How tools are presented to LLMs

### 2. first_smolagents.ipynb - SmoLAgents Tutorial

**Purpose**: Introduction to the SmoLAgents framework for building simple but effective AI agents.

**What you'll learn**:

- SmoLAgents framework basics
- CodeAgent vs ToolCallingAgent
- Custom tool creation
- Agent prompting strategies
- Observability and monitoring using Langfuse

### 3. langgraph_agent.ipynb - LangGraph Workflows

**Purpose**: Introduction to LangGraph for building complex, stateful agent workflows.

**What you'll learn**:

- State management in agent workflows
- Graph-based agent design
- Node and edge concepts
- Conditional routing
- Multi-step reasoning

### 4. SalesHelper.ipynb - Production Sales Agent

**Purpose**: Complete implementation of a sales intelligence agent that analyzes companies and provides market insights.

**What you'll learn**:

- Real-world agent architecture
- Web scraping with browser automation
- Multi-agent coordination

Happy agent building! 🤖
