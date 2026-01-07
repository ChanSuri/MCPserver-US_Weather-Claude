# Building simple MCP weather to use in Claude for Desktop and other clients.

## US National Weather service, the queries will only work for US locations.

# In Claude for Desktop:
- What’s the weather in Sacramento?
- What are the active weather alerts in Texas?

# When you ask a question:
- The client sends your question to Claude
- Claude analyzes the available tools and decides which one(s) to use
- The client executes the chosen tool(s) through the MCP server
- The results are sent back to Claude
- Claude formulates a natural language response
- The response is displayed to you!
