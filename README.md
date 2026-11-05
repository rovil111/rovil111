# Hi, I'm Rovil Nigam

Senior Test Consultant at Microsoft. I work on test automation and quality engineering, with a particular interest in how to test AI systems.

## Projects

Each project runs from a fresh clone with no external environment, and each has a CI pipeline.

| Project | What it shows | Stack |
| --- | --- | --- |
| [playwright-quality-framework](https://github.com/rovil111/playwright-quality-framework) | Layered UI, API and accessibility automation with parallel-safe test data | Playwright, TypeScript, axe-core |
| [dotnet-api-testing](https://github.com/rovil111/dotnet-api-testing) | API testing with boundary, contract and concurrency checks | C#, .NET 10, MSTest |
| [llm-eval-regression-kit](https://github.com/rovil111/llm-eval-regression-kit) | Release gates for grounded AI answers: hallucination, injection and PII checks | TypeScript, Vitest |
| [playwright-mcp-tests](https://github.com/rovil111/playwright-mcp-tests) | Testing the tool layer AI agents depend on | Playwright MCP, TypeScript |
| [k6-performance-gates](https://github.com/rovil111/k6-performance-gates) | Load tests with SLO thresholds that fail the build | k6, JavaScript |

## How I approach testing

- A check that has never failed proves little, so I test the tests with seeded defects.
- Tests should be isolated, parallel-safe and explain their own failures.
- AI features deserve the same discipline as other software: datasets, gates and regression tracking.

*These are personal projects and aren't affiliated with or endorsed by my employer.*
