# 🤖 Multi-Agent Content Creator

Hey there! Welcome to my Multi-Agent Content Creator project - where I let AI agents duke it out to create killer content proposals.

## What's this all about?

I built this (Google Colab notebook)[https://github.com/kenny08gt/social_media_content_planner_Agents/blob/main/social_media_content_planner_Agents.ipynb] that leverages OpenAI's Agents SDK to create a collaborative AI workspace. The project uses three specialized agents that work together (and sometimes argue) to come up with the best content proposals:

- 📝 **Copywriter Agent** - The wordsmith with a knack for compelling language
- 📊 **CMO Agent** - The marketing strategist who keeps business goals in focus
- 🧠 **GenZ Agent** - The cultural pulse-checker who knows what's trending

## Why I made this

Getting content right is hard. Different perspectives matter. So I thought: why not have specialized AI agents collaborate and challenge each other's ideas? The results are way more interesting than using a single AI.

## How it works

1. Input your content brief/challenge
2. Watch the agents discuss, debate, and refine ideas in real-time
3. See them evaluate each other's suggestions
4. Get the final proposal with insights from all three perspectives

## Tech stack

- Google Colab notebook environment
- OpenAI Agents SDK
- Python for orchestration
- Some prompt engineering magic ✨

## Try it yourself

1. Clone this repo
2. Open the notebook in Google Colab
3. Add your Gemini API key
4. Run the cells and watch the agents collaborate!

```python
# Quick example of how the agent initialization looks
copywriter = Agent(
    name="Copywriter",
    role="Expert content creator focused on compelling language and narratives",
    tools=[research_tool, content_analysis]
)
```

## What I learned

Building this taught me a ton about:
- Orchestrating multi-agent systems
- Getting agents to effectively collaborate
- Balancing different expert perspectives
- The challenges of prompt engineering at scale

## Where to next?

I'm working on expanding this with:
- More specialized agents (Designer? Data Analyst?)
- Better conflict resolution between competing ideas
- Memory systems so agents can learn from past projects
- A simple UI so non-technical folks can use it

Feel free to fork, contribute, or hit me up with questions. Let's make content creation more collaborative and fun!

---

*Made with ☕ and a slightly unhealthy obsession with making AIs talk to each other*
