## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

Celesto turns agents from request/response scripts into always-on, coordinated systems.<br>
Deploy a production-grade runtime that handles security, scaling, and reliability.


<h2>
    Stop building infra and<br>
    Start building agents 🚀
</h2>

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
