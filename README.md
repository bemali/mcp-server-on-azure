MCP implementation on Azure
https://learn.microsoft.com/en-us/azure/azure-functions/functions-mcp-tutorial?tabs=self-hosted&pivots=programming-language-python

Install Azure functions extension
Initialize the project with UV `uv init`, `uv venv`, `.venv/scripts/activate`
In command pallet type Azure Functions: Create project

Select a project type ->	Choose Self-hosted MCP server.
Select a language for the MCP server ->	Choose Python.
Include sample server code ->	Choose Yes.
Select how you would like to open your project -> 	Choose Open in current window.

Start locally - run `uv run func start` or `func start` if uv run does not work
prerequisits:
npm installation (check where npm, if not found install npm)
azure function core tools installation (after above) `npm install -g azure-functions-core-tools@4 --unsafe-perm true`, add to path variables. since npm is added to path variables, this is added automatically. check if func is availabe with the command `func --version`