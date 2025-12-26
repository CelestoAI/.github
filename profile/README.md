<div align="center">
<h2>
Stop building infra and<br>
Start building agents 🚀
</h2>

<div align="left">
    
```py
from agentor.tools import GetWeatherTool
from agentor import Agentor

agent = Agentor(
    name="Weather Agent",
    model="gpt-5-mini",  # Use any LLM provider - gemini/gemini-2.5-pro or anthropic/claude-3.5
    tools=[GetWeatherTool()]
)
result = agent.run("What is the weather in London?")  # Run the Agent
print(result)

# Serve Agent with a single line of code
agent.serve()
```
</div>

</div>
