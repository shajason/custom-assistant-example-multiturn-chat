# custom-assistant-example-multiturn-chat
This assistant is designed to answer student questions about the Intro to Python course, without giving away solutions.

The system prompt contains the course structure with module and assignment names. It also has general guidelines for the LLM to follow. (make changes here to adapt this for any course)

It starts a new chat session on every button click.
The message history of the last 4-5 interactions in the session is passed back to the LLM as context before it answers the next question.

NOTE:
The system prompt in this example is merely an example, and does not set comprehensive guidelines that cover all scenarios.
Please go over the `index.js` file and update the `systemPrompt` variable with all the guardrails and guidelines you'd prefer your AI assistant to have.


