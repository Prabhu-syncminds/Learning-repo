# What is google gemini-cli? and how is it used?

Google Gemini CLI is an open-source AI agent designed to bring the power of Google's Gemini AI model directly into the terminal. It offers developers and users lightweight, terminal-first access to the Gemini 2.5 Pro model, which supports a massive 1 million token context window. Gemini CLI is built for coding assistance but is versatile enough to support a wide range of tasks, such as code understanding, debugging, running DevOps tasks, content generation, problem solving, and research. It uses a reason and act (ReAct) loop mechanism to enable interactive and intelligent task completion, including file operations, shell commands, web searching, and interacting with Model Context Protocol (MCP) servers for custom integrations.

### Key Features and Usage

- Free tier with 60 requests per minute and 1,000 requests per day via a personal Google account.
- Supports powerful Gemini 2.5 Pro AI with built-in tools like Google Search grounding, file read/write, command execution, and web fetching.
- Terminal-focused, designed primarily for developers who prefer command-line workflows.
- Extensible via MCP standards and customizable through config files and prompts.
- Installation options include instant use via npx, global installation via npm or Homebrew.
- After installation, users authenticate with a Google account to start using it.
- Users interact with Gemini CLI through natural language queries or commands and can use built-in tools triggered by the AI to perform complex tasks.
- It can be used non-interactively in scripts to automate workflows.


### How to Use

1. Install Gemini CLI (e.g., via `npx https://github.com/google-gemini/gemini-cli` for instant use or `npm install -g @google/gemini-cli` for global install).
2. Launch the CLI by typing `gemini` in the terminal.
3. Authenticate with a Google account (API key or other methods also supported).
4. Enter natural language queries or commands.
5. Use slash commands like `/help`, `/tools`, or `/quit` for assistance and managing sessions.
6. Gemini CLI will respond directly in the terminal, performing computations or leveraging built-in tools as needed.

This tool is ideal for developers who want seamless AI assistance directly within their development environments, enhancing productivity by reducing context switches and automating complex command-line tasks.

References:

- Gemini CLI GitHub and official docs[^1][^2][^3][^5][^7]
<span style="display:none">[^10][^4][^6][^8][^9]</span>

<div style="text-align: center">⁂</div>

[^1]: https://github.com/google-gemini/gemini-cli

[^2]: https://www.f22labs.com/blogs/what-is-google-gemini-cli-how-to-install-and-use-it/

[^3]: https://cloud.google.com/gemini/docs/codeassist/gemini-cli

[^4]: https://javascript.plainenglish.io/i-tried-googles-gemini-cli-and-it-changed-how-i-code-forever-4794d3c02081

[^5]: https://blog.google/technology/developers/introducing-gemini-cli-open-source-ai-agent/

[^6]: https://www.youtube.com/watch?v=qqP1ucSiVkE

[^7]: https://codelabs.developers.google.com/gemini-cli-hands-on

[^8]: https://developers.googleblog.com/en/gemini-cli-is-now-integrated-into-zed/

[^9]: https://www.youtube.com/watch?v=KUCZe1xBKFM

[^10]: https://developers.google.com/gemini-code-assist/docs/overview

