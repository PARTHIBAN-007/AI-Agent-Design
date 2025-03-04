# Agent
An agent is an autonomous entity that perceives its environment, processes information, and takes actions to achieve specific goals. Agents can be software-based (e.g., AI chatbots) or physical (e.g., robots). They operate using decision-making logic and may interact with other agents or systems.


## Agent Patterns
A structured design approach for organizing AI agents to perform tasks efficiently.

### 1. Reflection Pattern
   - **Definition**: The agent self-evaluates its output and iteratively improves it.
   - **Example**: A code generator agent writes an initial draft, then reviews and refines it before passing it forward.

### 2. Tool Pattern
   - **Definition**: The agent uses external tools (e.g., APIs, databases, or file systems) to enhance its functionality.
   - **Example**: The File Writer Agent in this pipeline uses a tool (`write_str_to_text`) to save the output.

### 3. Planning Pattern
   - **Definition**: The agent autonomously plans a sequence of tasks before executing them.
   - **Example**: A planning agent first determines if code should be translated before generating it.

### 4. Multi-Agent Pattern
   - **Definition**: Multiple agents collaborate to complete a complex task in a structured workflow.
   - **Example**: The three-agent pipeline in this project follows this pattern, with each agent performing a specific role in sequence.

<img src = "https://github.com/neural-maze/agentic_patterns/raw/main/img/agentic_patterns.png" height ="650">

### For More Details:
- Official Repository : [NeuralMaze](https://github.com/neural-maze/agentic_patterns)
