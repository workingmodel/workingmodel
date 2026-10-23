### Hi, I'm Adam 👋

I run [Working Model](https://www.workingmodel.co) in Toronto. I started out as a developer, spent 20+ years at agencies including Sapient, Jam3, Leo Burnett and Publicis, and moved from front-end architecture into technical direction. Today I build across the stack: client sites and digital products, developer tools, and production AI systems.

**Right now:** Claude Code agents, MCP servers, and evals that show whether an agent actually got better.

---

#### AI agents & MCP

| | |
|---|---|
| **[agent-evals](https://github.com/workingmodel/agent-evals)** | Unit tests for Claude Code agents. It runs golden tasks headless and saves full traces, then scores each run with rule checks and an LLM-judge rubric. A regression against the baseline fails the build. Includes prompt-injection canary tests. `pipx install wm-agent-evals` |
| **[create-mcp-server](https://github.com/workingmodel/create-mcp-server)** | Scaffolds a typed, tested MCP server in under a minute. Three templates, stdio or SSE, and Zod-inferred tool definitions. `npx @workingmodel/create-mcp-server my-server` |
| **[figma-vector-mcp](https://github.com/workingmodel/wm-figma-vector-mcp)** | An MCP server and Figma plugin that let Claude draw fully editable vectors on the Figma canvas. 58 tools, covering paths, gradients, boolean operations, auto layout, components and SVG/PNG export. |
| **[llms-file-generator](https://github.com/workingmodel/wm-wp-plugin-llms-file-generator)** | A WordPress plugin that keeps `/llms.txt` and `/llms-full.txt` up to date, so AI models can read your site. |

#### Zero-config CLIs

You run one command and it tells you what's wrong in plain English. No setup, no dashboard, no API key.

- [`why-is-this-slow`](https://github.com/workingmodel/why-is-this-slow): profiles a Node app and reports the bottleneck
- [`who-ate-my-ram`](https://github.com/workingmodel/who-ate-my-ram): finds the Node process that is slowly leaking memory
- [`what-is-this-package-actually-doing`](https://github.com/workingmodel/what-is-this-package-actually-doing): runs an npm package and shows its network calls, file writes and child processes
- [`why-wont-this-install`](https://github.com/workingmodel/why-wont-this-install), [`why-is-this-failing-in-prod`](https://github.com/workingmodel/why-is-this-failing-in-prod), [`where-did-my-env-go`](https://github.com/workingmodel/where-did-my-env-go), [`who-changed-this`](https://github.com/workingmodel/who-changed-this)

#### Starters

[WordPress base theme](https://github.com/workingmodel/wm-wordpress-base-theme) (Vite, TypeScript, Tailwind, GSAP, React islands) · [Next.js site starter](https://github.com/workingmodel/wm-site-starter) (Tailwind tokens, GSAP, shadcn/ui)

---

TypeScript · Python · Node · PHP · Next.js · React · Claude Code · MCP · AWS Lambda · Three.js / WebGL · GSAP

[workingmodel.co](https://www.workingmodel.co) · [npm](https://www.npmjs.com/~working-model) · [PyPI](https://pypi.org/project/wm-agent-evals/) · [LinkedIn](https://www.linkedin.com/in/adamsmithprofile) · hi@workingmodel.co
