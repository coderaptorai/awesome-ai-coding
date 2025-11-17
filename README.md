# Awesome AI Coding ✨

> A curated list of awesome AI-powered coding tools, libraries, frameworks, and resources.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

AI is revolutionizing how we write, review, debug, and understand code. This list covers the best tools from IDE integrations to autonomous agents, code completion engines to testing frameworks.

## Contents

- [AI Coding Assistants](#ai-coding-assistants)
- [IDE Extensions & Plugins](#ide-extensions--plugins)
- [Code Completion Engines](#code-completion-engines)
- [Code Review & Analysis](#code-review--analysis)
- [AI Agents & Autonomous Coding](#ai-agents--autonomous-coding)
- [Testing & Quality Assurance](#testing--quality-assurance)
- [Documentation & Code Understanding](#documentation--code-understanding)
- [Code Search & Navigation](#code-search--navigation)
- [Refactoring & Migration](#refactoring--migration)
- [Language Models for Code](#language-models-for-code)
- [Datasets & Benchmarks](#datasets--benchmarks)
- [Research Papers](#research-papers)
- [Developer Tools & Frameworks](#developer-tools--frameworks)
- [Open Source Projects](#open-source-projects)

---

## AI Coding Assistants

*Full-featured AI assistants for coding*

- **[Cursor](https://cursor.com)** - AI-first code editor built on VS Code with Claude Sonnet 4, GPT-4, and other models. Features Tab completion, Cmd+K inline editing, and Agent mode for autonomous coding.
- **[Claude Code](https://docs.claude.com/en/docs/claude-code)** - Terminal-first AI agent by Anthropic with 200K token context window. Autonomous multi-step task execution with incremental permissions.
- **[GitHub Copilot](https://github.com/features/copilot)** - AI pair programmer powered by OpenAI Codex. Suggests whole lines or entire functions as you type.
- **[Cody by Sourcegraph](https://sourcegraph.com/cody)** - AI coding assistant with codebase context awareness. Works with VS Code, JetBrains, and Neovim.
- **[Amazon Q Developer](https://aws.amazon.com/q/developer/)** - AWS AI assistant for building, deploying, and operating applications. Includes code transformation and security scanning.
- **[Tabnine](https://www.tabnine.com)** - AI code completion that learns from your code patterns. Supports multiple LLMs and can run locally.
- **[Replit AI](https://replit.com/ai)** - Collaborative AI coding in the browser. Build and deploy applications with natural language.
- **[Windsurf](https://windsurf.ai)** - IDE with built-in AI flows for code generation, debugging, and documentation.
- **[Qodo (formerly Codium AI)](https://www.qodo.ai)** - AI-powered test generation and code quality platform.

## IDE Extensions & Plugins

*Extensions that bring AI to your favorite IDE*

### VS Code

- **[Continue](https://continue.dev)** - Open-source autopilot for VS Code. Works with Claude, GPT-4, Code Llama, and more.
- **[CodeGPT](https://github.com/carlrobertoh/CodeGPT)** - JetBrains and VS Code extensions for using ChatGPT inside your IDE.
- **[Aide](https://aide.dev)** - Open-source AI-native IDE extension for VS Code and JetBrains.
- **[Pieces for Developers](https://pieces.app)** - On-device AI assistant that helps you capture, enrich, and reuse code snippets.
- **[Bito AI](https://bito.ai)** - AI dev tool with code generation, test creation, and documentation.

### JetBrains

- **[JetBrains AI Assistant](https://www.jetbrains.com/ai/)** - Built-in AI assistant for all JetBrains IDEs with context awareness.
- **[Qodo Gen](https://www.qodo.ai/products/qodo-gen/)** - Test generation directly in IntelliJ IDEA and other JetBrains IDEs.

### Vim/Neovim

- **[CodeGPT.nvim](https://github.com/dpayne/CodeGPT.nvim)** - ChatGPT integration for Neovim with code explanation and generation.
- **[CopilotChat.nvim](https://github.com/CopilotC-Nvim/CopilotChat.nvim)** - Chat interface for GitHub Copilot in Neovim.
- **[nvim-cmp](https://github.com/hrsh7th/nvim-cmp)** - Completion engine with AI provider integrations.

## Code Completion Engines

*Smart autocomplete and code suggestions*

- **[Tabby](https://github.com/TabbyML/tabby)** - Self-hosted AI coding assistant. Open-source alternative to GitHub Copilot.
- **[FauxPilot](https://github.com/fauxpilot/fauxpilot)** - Open-source GitHub Copilot server powered by SalesForce CodeGen.
- **[StarCoder](https://huggingface.co/bigcode/starcoder)** - Open-access LLM for code with 15B parameters trained on 80+ programming languages.
- **[CodeLlama](https://github.com/facebookresearch/codellama)** - Meta's code-specialized LLM built on Llama 2.
- **[WizardCoder](https://github.com/nlpxucan/WizardLM)** - Empowering code LLMs with Evol-Instruct.
- **[DeepSeek Coder](https://github.com/deepseek-ai/DeepSeek-Coder)** - Open-source code model trained on 2T tokens with strong performance.
- **[SantaCoder](https://huggingface.co/bigcode/santacoder)** - 1.1B parameter model trained on Python, Java, and JavaScript.

## Code Review & Analysis

*AI-powered code review and security analysis*

- **[CodeRabbit](https://coderabbit.ai)** - AI code reviewer that provides context-aware feedback on pull requests.
- **[Codium PR-Agent](https://github.com/Codium-ai/pr-agent)** - Open-source AI agent for automated PR analysis and review.
- **[Sweep](https://sweep.dev)** - AI junior developer that turns bugs and feature requests into code changes via PR.
- **[Gito](https://gito.ai)** - AI code reviewer for GitHub Actions with Jira/Linear integration.
- **[Glide](https://glideapps.com)** - Structured pull request walkthroughs with AI analysis.
- **[DeepCode](https://www.deepcode.ai)** - AI-based static analysis for security vulnerabilities and code quality.
- **[Codiga](https://www.codiga.io)** - Real-time static code analysis with AI-powered suggestions.
- **[Sourcery](https://sourcery.ai)** - Python code review tool with instant refactoring suggestions.

## AI Agents & Autonomous Coding

*Autonomous agents that can code independently*

- **[Devin by Cognition AI](https://www.cognition-labs.com/devin)** - First AI software engineer. Plans and executes complex engineering tasks autonomously.
- **[GPT-Engineer](https://github.com/gpt-engineer-org/gpt-engineer)** - Specify what you want to build, AI asks clarifying questions, then builds it.
- **[Aider](https://github.com/paul-gauthier/aider)** - AI pair programming in your terminal. Works with local git repositories.
- **[SWE-agent](https://github.com/princeton-nlp/SWE-agent)** - Autonomous agent that solves GitHub issues end-to-end.
- **[OpenHands](https://github.com/All-Hands-AI/OpenHands)** - Platform for software development agents powered by AI.
- **[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** - Autonomous AI agent that chains GPT-4 calls to accomplish goals.
- **[MetaGPT](https://github.com/geekan/MetaGPT)** - Multi-agent framework. Assign different roles to GPTs to form a software company.
- **[Mentat](https://github.com/AbanteAI/mentat)** - Coding assistant that understands your entire codebase and makes coordinated edits.
- **[Devon](https://github.com/entropy-research/Devon)** - Open-source AI pair programmer that can do the boring stuff.

## Testing & Quality Assurance

*AI tools for test generation and quality*

- **[Test.ai](https://test.ai)** - AI-powered test automation for mobile and web applications.
- **[Mutahunter](https://github.com/codeintegrity-ai/mutahunter)** - Open-source AI for mutation testing and code security.
- **[DiffBlue Cover](https://www.diffblue.com)** - Automated unit test generation for Java.
- **[Ponicode](https://ponicode.com)** - AI-powered unit test generation (acquired by CircleCI).
- **[TestGPT](https://testgpt.dev)** - Generate unit tests using GPT models.
- **[Codium Cover-Agent](https://github.com/Codium-ai/cover-agent)** - Open-source tool for automated test generation and coverage improvement.
- **[QA Wolf](https://www.qawolf.com)** - AI-native end-to-end test automation platform.

## Documentation & Code Understanding

*Tools for understanding and documenting code*

- **[Mintlify](https://mintlify.com)** - AI-powered documentation generator. Automatically creates beautiful docs from your code.
- **[Stenography](https://stenography.dev)** - Automatic code documentation and explanation.
- **[Readable](https://readable.so)** - AI that generates comments and documentation for your codebase.
- **[Bito Docs](https://docs.bito.ai)** - AI-generated technical documentation from code.
- **[Code2Prompt](https://github.com/mufeedvh/code2prompt)** - Generate LLM prompts from your codebase for code understanding.
- **[Trelent](https://trelent.net)** - Write helpful docstrings using AI.

## Code Search & Navigation

*AI-enhanced code search and understanding*

- **[Bloop](https://bloop.ai)** - Fast code search with natural language. Uses AI to understand intent.
- **[Phind](https://www.phind.com)** - AI search engine for developers. Get instant answers with code examples.
- **[Sourcegraph](https://sourcegraph.com)** - Universal code search with AI assistance (Cody).
- **[Greptile](https://greptile.com)** - AI-powered codebase understanding and search API.
- **[CodeQuery](https://codequery.com)** - Semantic code search powered by AI embeddings.

## Refactoring & Migration

*AI tools for code transformation and modernization*

- **[Amazon Q Code Transformation](https://aws.amazon.com/q/developer/)** - Upgrade Java, .NET, and mainframe code to modern versions.
- **[Moderne](https://moderne.io)** - Automated code refactoring and migration at scale.
- **[Cursor Code Migration](https://cursor.com)** - Use Cursor's agent mode to migrate codebases between frameworks.
- **[Refact.ai](https://refact.ai)** - Open-source AI refactoring assistant.
- **[grit.io](https://www.grit.io)** - Automated code migrations and dependency upgrades.
- **[Atomist](https://atomist.com)** - Software delivery automation with code transformations.

## Language Models for Code

*Pre-trained models specifically designed for code*

### Open Source Models

- **[Code Llama](https://github.com/facebookresearch/codellama)** - 7B to 70B parameter models for code generation by Meta.
- **[StarCoder 2](https://huggingface.co/bigcode/starcoder2-15b)** - Family of code LLMs (3B-15B) trained on The Stack v2.
- **[DeepSeek Coder V2](https://github.com/deepseek-ai/DeepSeek-Coder-V2)** - Open-source MoE model with 236B parameters.
- **[Qwen2.5-Coder](https://github.com/QwenLM/Qwen2.5-Coder)** - State-of-the-art code model series from Alibaba (1.5B-32B).
- **[Codestral](https://mistral.ai/news/codestral/)** - Mistral AI's 22B parameter code model.
- **[CodeGemma](https://ai.google.dev/gemma)** - Google's open code LLMs (2B-7B) based on Gemma.
- **[CodeT5+](https://github.com/salesforce/CodeT5)** - Salesforce's unified encoder-decoder models for code.
- **[Phi-3](https://azure.microsoft.com/en-us/products/phi-3)** - Microsoft's small language models with strong code capabilities.
- **[OpenCodeInterpreter](https://github.com/OpenCodeInterpreter/OpenCodeInterpreter)** - Open-source code interpreter models.

### Commercial Models

- **[GPT-4o](https://openai.com/index/gpt-4o-mini/)** - OpenAI's flagship model with excellent code generation.
- **[Claude 4 Sonnet](https://www.anthropic.com/claude)** - Anthropic's latest model, excels at long-context coding tasks.
- **[Gemini 2.0](https://deepmind.google/technologies/gemini/)** - Google's multimodal AI with 1M+ token context for code.
- **[DeepSeek R1](https://api-docs.deepseek.com/)** - Reasoning model with strong coding performance.
- **[Codex](https://openai.com/blog/openai-codex)** - OpenAI's original code model (powers GitHub Copilot).

## Datasets & Benchmarks

*Training data and evaluation benchmarks*

### Datasets

- **[The Stack](https://huggingface.co/datasets/bigcode/the-stack)** - 6TB of permissively licensed source code in 358 languages.
- **[The Stack v2](https://huggingface.co/datasets/bigcode/the-stack-v2)** - Improved version with better deduplication and quality.
- **[CodeSearchNet](https://github.com/github/CodeSearchNet)** - Dataset of 6M functions from GitHub with documentation.
- **[CodeXGLUE](https://github.com/microsoft/CodeXGLUE)** - Benchmark dataset for code understanding and generation.
- **[HumanEval](https://github.com/openai/human-eval)** - Hand-written evaluation set for code generation (164 problems).
- **[MBPP](https://github.com/google-research/google-research/tree/master/mbpp)** - Mostly Basic Python Problems dataset for code generation.
- **[APPS](https://github.com/hendrycks/apps)** - 10K Python programming problems for evaluating code models.

### Benchmarks

- **[HumanEval+](https://github.com/evalplus/evalplus)** - Extended version of HumanEval with more test cases.
- **[SWE-bench](https://www.swebench.com)** - Benchmark for evaluating AI on real-world GitHub issues.
- **[LiveCodeBench](https://livecodebench.github.io)** - Holistic benchmark that continuously collects new problems.
- **[CodeForces](https://codeforces.com)** - Competitive programming problems used for model evaluation.
- **[BigCodeBench](https://huggingface.co/spaces/bigcode/bigcodebench-leaderboard)** - Practical programming task benchmark.
- **[ClassEval](https://github.com/FudanSELab/ClassEval)** - Class-level code generation benchmark.

## Research Papers

*Important papers in AI-assisted coding*

### Foundational Papers

- [Evaluating Large Language Models Trained on Code](https://arxiv.org/abs/2107.03374) - OpenAI Codex paper (2021)
- [CodeT5: Identifier-aware Unified Pre-trained Encoder-Decoder Models](https://arxiv.org/abs/2109.00859) (2021)
- [InCoder: A Generative Model for Code Infilling and Synthesis](https://arxiv.org/abs/2204.05999) (2022)
- [StarCoder: may the source be with you!](https://arxiv.org/abs/2305.06161) (2023)
- [Code Llama: Open Foundation Models for Code](https://arxiv.org/abs/2308.12950) (2023)
- [DeepSeek-Coder: When the Large Language Model Meets Programming](https://arxiv.org/abs/2401.14196) (2024)

### Code Understanding

- [CodeBERT: A Pre-Trained Model for Programming and Natural Languages](https://arxiv.org/abs/2002.08155) (2020)
- [GraphCodeBERT: Pre-training Code Representations with Data Flow](https://arxiv.org/abs/2009.08366) (2020)
- [UniXcoder: Unified Cross-Modal Pre-training for Code Representation](https://arxiv.org/abs/2203.03850) (2022)

### Code Generation & Synthesis

- [Competition-Level Code Generation with AlphaCode](https://arxiv.org/abs/2203.07814) - DeepMind (2022)
- [StarCoder 2 and The Stack v2](https://arxiv.org/abs/2402.19173) (2024)
- [WizardCoder: Empowering Code Large Language Models with Evol-Instruct](https://arxiv.org/abs/2306.08568) (2023)
- [Self-Instruct: Aligning Language Models with Self-Generated Instructions](https://arxiv.org/abs/2212.10560) (2023)

### Program Repair & Testing

- [SelfEvolve: A Code Evolution Framework via Large Language Models](https://arxiv.org/abs/2306.02907) (2023)
- [Is AI the better programming partner?](https://cacm.acm.org/research/is-ai-the-better-programming-partner/) - GitHub Copilot study (2022)
- [Can ChatGPT Replace StackOverflow?](https://arxiv.org/abs/2308.02312) (2023)

### Industrial Deployment

- [CodeCompose: A Large-Scale Industrial Deployment of AI-assisted Code Authoring](https://arxiv.org/abs/2305.12050) - Meta (2023)
- [ML-Enhanced Code Completion Improves Developer Productivity](https://arxiv.org/abs/2205.06537) - Google (2022)

## Developer Tools & Frameworks

*Frameworks and tools for building AI coding applications*

### Development Frameworks

- **[LangChain](https://github.com/langchain-ai/langchain)** - Framework for building LLM applications with code tools.
- **[LlamaIndex](https://www.llamaindex.ai)** - Data framework for LLM applications with codebase indexing.
- **[Semantic Kernel](https://github.com/microsoft/semantic-kernel)** - Microsoft's SDK for integrating AI into applications.
- **[AutoGen](https://github.com/microsoft/autogen)** - Multi-agent conversation framework for building code agents.
- **[CrewAI](https://github.com/joaomdmoura/crewAI)** - Framework for orchestrating role-playing autonomous AI agents.
- **[PydanticAI](https://ai.pydantic.dev)** - Agent framework from the makers of Pydantic.

### Code Analysis & Parsing

- **[Tree-sitter](https://tree-sitter.github.io/tree-sitter/)** - Parser generator and incremental parsing library for code.
- **[SourceGraph's Code Intelligence](https://sourcegraph.com/code-intelligence)** - Libraries for code navigation and analysis.
- **[ast](https://docs.python.org/3/library/ast.html)** - Python's built-in abstract syntax tree module.
- **[Esprima](https://esprima.org)** - JavaScript parser with syntax tree generation.
- **[jq](https://stedolan.github.io/jq/)** - Command-line JSON processor useful for code analysis.

### Model Context Protocol (MCP)

- **[MCP Servers](https://github.com/modelcontextprotocol/servers)** - Official collection of MCP servers for tool integration.
- **[Roundtable MCP Server](https://github.com/roundtable-ai/roundtable-mcp)** - Zero-config MCP server unifying AI coding assistants.
- **[ToolHive](https://toolhive.ai)** - Marketplace for finding and deploying MCP servers.

## Open Source Projects

*Notable open-source projects in AI coding*

### Self-Hosted Solutions

- **[LocalAI](https://github.com/mudler/LocalAI)** - Free, open-source OpenAI alternative that runs locally.
- **[Ollama](https://ollama.ai)** - Run code LLMs locally with a simple CLI interface.
- **[LM Studio](https://lmstudio.ai)** - Desktop app for running local LLMs with UI.
- **[Jan.ai](https://jan.ai)** - Open-source ChatGPT alternative that runs 100% offline.
- **[Tabby](https://tabby.tabbyml.com)** - Self-hosted AI coding assistant with model customization.

### Code Analysis Tools

- **[promptr](https://github.com/ferrislucas/promptr)** - CLI tool for operating on codebases using GPT.
- **[code-collator](https://github.com/jayshenk/code-collator)** - Creates markdown files describing entire codebases for LLMs.
- **[batchai](https://github.com/TechElevateCode/batchai)** - Batch processing of project codes with AI.
- **[CodeTF](https://github.com/salesforce/CodeTF)** - One-stop library for state-of-the-art code LLMs.
- **[Rift](https://github.com/morph-labs/rift)** - Open-source LSP leveraging language models.

### Specialized Tools

- **[vibe-compiler](https://github.com/joshskeen/vibe-compiler)** - Self-compiling tool transforming markdown to code using LLMs.
- **[auto-pr](https://github.com/irgolic/AutoPR)** - Automated pull request workflow.
- **[Pinokio](https://pinokio.computer)** - Browser for installing and running AI applications locally.
- **[Cherry Studio](https://github.com/kangfenmao/cherry-studio)** - Desktop client supporting multiple LLM providers.

## Learning Resources

*Tutorials, courses, and documentation*

### Official Documentation

- [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- [Claude Code Documentation](https://docs.claude.com/en/docs/claude-code)
- [Cursor Documentation](https://docs.cursor.com)
- [Anthropic Prompt Engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering)
- [OpenAI API Documentation](https://platform.openai.com/docs)

### Courses & Tutorials

- [DeepLearning.AI - ChatGPT Prompt Engineering](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)
- [Coursera - Prompt Engineering Specialization](https://www.coursera.org/specializations/prompt-engineering)
- [The Complete AI Coding Course (Udemy)](https://www.udemy.com/course/the-complete-ai-coding-course-2025-cursor-ai-v0-vercel/)
- [Building AI Applications](https://www.buildingai.dev)

### Community Resources

- [r/cursor](https://reddit.com/r/cursor) - Cursor IDE community
- [r/ClaudeAI](https://reddit.com/r/ClaudeAI) - Claude and Claude Code discussions
- [Cursor Forum](https://forum.cursor.com) - Official Cursor community forum
- [AI Coding Discord Servers](https://discord.com/servers) - Various AI coding communities

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

See [LICENSE](LICENSE) file for details.

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
