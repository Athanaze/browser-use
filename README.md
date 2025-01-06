# Use without pip install browser-use, to not have telemetry

The easiest way is to modify one of the example script. Must be run from the main folder, otherwise there is an error because the static folder is referenced as .static

The api key can be set directly in code, and gpt-4o-mini works about as well as got-4o and is obviously quite a bit cheaper:

llm = ChatOpenAI(model='gpt-4o-mini', api_key="sk-proj-j...")

