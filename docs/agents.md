# Agent Reference

Complete reference for all specialized AI agents organized by category with model assignments.

## Agent Categories

### Architecture & System Design

#### Core Architecture

| Agent                                                                                      | Model  | Description                                                        |
| ------------------------------------------------------------------------------------------ | ------ | ------------------------------------------------------------------ |
| [backend-architect](../plugins/backend-development/agents/backend-architect.md)            | opus   | RESTful API design, microservice boundaries, database schemas      |
| [frontend-developer](../plugins/multi-platform-apps/agents/frontend-developer.md)          | sonnet | React components, responsive layouts, client-side state management |
| [graphql-architect](../plugins/backend-development/agents/graphql-architect.md)            | opus   | GraphQL schemas, resolvers, federation architecture                |
| [architect-reviewer](../plugins/comprehensive-review/agents/architect-review.md)           | opus   | Architectural consistency analysis and pattern validation          |
| [cloud-architect](../plugins/cloud-infrastructure/agents/cloud-architect.md)               | opus   | AWS/Azure/GCP infrastructure design and cost optimization          |
| [hybrid-cloud-architect](../plugins/cloud-infrastructure/agents/hybrid-cloud-architect.md) | opus   | Multi-cloud strategies across cloud and on-premises environments   |
| [kubernetes-architect](../plugins/kubernetes-operations/agents/kubernetes-architect.md)    | opus   | Cloud-native infrastructure with Kubernetes and GitOps             |

#### UI/UX & Mobile

| Agent                                                                                    | Model  | Description                                        |
| ---------------------------------------------------------------------------------------- | ------ | -------------------------------------------------- |
| [ui-ux-designer](../plugins/multi-platform-apps/agents/ui-ux-designer.md)                | sonnet | Interface design, wireframes, design systems       |
| [ui-visual-validator](../plugins/accessibility-compliance/agents/ui-visual-validator.md) | sonnet | Visual regression testing and UI verification      |
| [mobile-developer](../plugins/multi-platform-apps/agents/mobile-developer.md)            | sonnet | React Native and Flutter application development   |
| [ios-developer](../plugins/multi-platform-apps/agents/ios-developer.md)                  | sonnet | Native iOS development with Swift/SwiftUI          |
| [flutter-expert](../plugins/multi-platform-apps/agents/flutter-expert.md)                | sonnet | Advanced Flutter development with state management |

### Programming Languages

#### Systems & Low-Level

| Agent                                                             | Model  | Description                                                 |
| ----------------------------------------------------------------- | ------ | ----------------------------------------------------------- |
| [c-pro](../plugins/systems-programming/agents/c-pro.md)           | sonnet | System programming with memory management and OS interfaces |
| [cpp-pro](../plugins/systems-programming/agents/cpp-pro.md)       | sonnet | Modern C++ with RAII, smart pointers, STL algorithms        |
| [rust-pro](../plugins/systems-programming/agents/rust-pro.md)     | sonnet | Memory-safe systems programming with ownership patterns     |
| [golang-pro](../plugins/systems-programming/agents/golang-pro.md) | sonnet | Concurrent programming with goroutines and channels         |

#### Web & Application

| Agent                                                                       | Model  | Description                                             |
| --------------------------------------------------------------------------- | ------ | ------------------------------------------------------- |
| [javascript-pro](../plugins/javascript-typescript/agents/javascript-pro.md) | sonnet | Modern JavaScript with ES6+, async patterns, Node.js    |
| [typescript-pro](../plugins/javascript-typescript/agents/typescript-pro.md) | sonnet | Advanced TypeScript with type systems and generics      |
| [ruby-pro](../plugins/web-scripting/agents/ruby-pro.md)                     | sonnet | Ruby with metaprogramming, Rails patterns, gem development |
| [php-pro](../plugins/web-scripting/agents/php-pro.md)                       | sonnet | Modern PHP with frameworks and performance optimization |

#### Enterprise & JVM

| Agent                                                       | Model  | Description                                                          |
| ----------------------------------------------------------- | ------ | -------------------------------------------------------------------- |
| [java-pro](../plugins/jvm-languages/agents/java-pro.md)     | sonnet | Modern Java with streams, concurrency, JVM optimization              |
| [scala-pro](../plugins/jvm-languages/agents/scala-pro.md)   | sonnet | Enterprise Scala with functional programming and distributed systems |
| [csharp-pro](../plugins/jvm-languages/agents/csharp-pro.md) | sonnet | C# development with .NET frameworks and patterns                     |
| [bash-pro](../plugins/shell-scripting/agents/bash-pro.md)   | sonnet | Production-grade Bash with defensive programming patterns            |
| [posix-shell-pro](../plugins/shell-scripting/agents/posix-shell-pro.md) | sonnet | POSIX-compliant shell scripting for maximum portability |

#### Specialized Platforms

| Agent                                                                              | Model  | Description                                     |
| ---------------------------------------------------------------------------------- | ------ | ----------------------------------------------- |
| [elixir-pro](../plugins/functional-programming/agents/elixir-pro.md)               | sonnet | Elixir with OTP patterns and Phoenix frameworks |
| [sql-pro](../plugins/database-design/agents/sql-pro.md)                            | sonnet | Complex SQL queries and database optimization   |

### Infrastructure & Operations

#### DevOps & Deployment

| Agent                                                                                  | Model  | Description                                                        |
| -------------------------------------------------------------------------------------- | ------ | ------------------------------------------------------------------ |
| [deployment-engineer](../plugins/cloud-infrastructure/agents/deployment-engineer.md)   | sonnet | CI/CD pipelines, containerization, cloud deployments               |
| [terraform-specialist](../plugins/cloud-infrastructure/agents/terraform-specialist.md) | sonnet | Infrastructure as Code with Terraform modules and state management |
| [dx-optimizer](../plugins/team-collaboration/agents/dx-optimizer.md)                   | sonnet | Developer experience optimization and tooling improvements         |

#### Database Management

| Agent                                                                                  | Model  | Description                                                         |
| -------------------------------------------------------------------------------------- | ------ | ------------------------------------------------------------------- |
| [database-optimizer](../plugins/observability-monitoring/agents/database-optimizer.md) | sonnet | Query optimization, index design, migration strategies              |
| [database-architect](../plugins/database-design/agents/database-architect.md)          | opus   | Database design from scratch, technology selection, schema modeling |

#### Network

| Agent                                                                              | Model  | Description                                         |
| ---------------------------------------------------------------------------------- | ------ | --------------------------------------------------- |
| [network-engineer](../plugins/observability-monitoring/agents/network-engineer.md) | sonnet | Network debugging, load balancing, traffic analysis |

### Quality Assurance & Security

#### Code Quality & Review

| Agent                                                                                            | Model | Description                                                  |
| ------------------------------------------------------------------------------------------------ | ----- | ------------------------------------------------------------ |
| [code-reviewer](../plugins/comprehensive-review/agents/code-reviewer.md)                         | opus  | Code review with security focus and production reliability   |
| [security-auditor](../plugins/comprehensive-review/agents/security-auditor.md)                   | opus  | Vulnerability assessment and OWASP compliance                |
| [frontend-security-coder](../plugins/frontend-mobile-security/agents/frontend-security-coder.md) | opus  | XSS prevention, CSP implementation, client-side security     |
| [mobile-security-coder](../plugins/frontend-mobile-security/agents/mobile-security-coder.md)     | opus  | Mobile security patterns, WebView security, biometric auth   |

#### Testing & Debugging

| Agent                                                                         | Model  | Description                                                |
| ----------------------------------------------------------------------------- | ------ | ---------------------------------------------------------- |
| [test-automator](../plugins/codebase-cleanup/agents/test-automator.md)        | sonnet | Comprehensive test suite creation (unit, integration, e2e) |
| [tdd-orchestrator](../plugins/backend-development/agents/tdd-orchestrator.md) | sonnet | Test-Driven Development methodology guidance               |
| [debugger](../plugins/error-debugging/agents/debugger.md)                     | sonnet | Error resolution and test failure analysis                 |
| [error-detective](../plugins/error-debugging/agents/error-detective.md)       | sonnet | Log analysis and error pattern recognition                 |

#### Performance & Observability

| Agent                                                                                          | Model | Description                                                    |
| ---------------------------------------------------------------------------------------------- | ----- | -------------------------------------------------------------- |
| [performance-engineer](../plugins/observability-monitoring/agents/performance-engineer.md)     | opus  | Application profiling and optimization                         |
| [observability-engineer](../plugins/observability-monitoring/agents/observability-engineer.md) | opus  | Production monitoring, distributed tracing, SLI/SLO management |

### AI & LLM Development

| Agent                                                                       | Model | Description                                              |
| --------------------------------------------------------------------------- | ----- | -------------------------------------------------------- |
| [ai-engineer](../plugins/llm-application-dev/agents/ai-engineer.md)         | opus  | LLM applications, RAG systems, prompt pipelines          |
| [prompt-engineer](../plugins/llm-application-dev/agents/prompt-engineer.md) | opus  | LLM prompt optimization and engineering                  |

### Documentation & Technical Writing

| Agent                                                                                | Model  | Description                                       |
| ------------------------------------------------------------------------------------ | ------ | ------------------------------------------------- |
| [docs-architect](../plugins/code-documentation/agents/docs-architect.md)             | opus   | Comprehensive technical documentation generation  |
| [api-documenter](../plugins/api-testing-observability/agents/api-documenter.md)      | sonnet | OpenAPI/Swagger specifications and developer docs |
| [reference-builder](../plugins/documentation-generation/agents/reference-builder.md) | haiku  | Technical references and API documentation        |
| [tutorial-engineer](../plugins/code-documentation/agents/tutorial-engineer.md)       | sonnet | Step-by-step tutorials and educational content    |
| [mermaid-expert](../plugins/documentation-generation/agents/mermaid-expert.md)       | sonnet | Diagram creation (flowcharts, sequences, ERDs)    |


### Specialized Domains

| Agent                                                                           | Model  | Description                                   |
| ------------------------------------------------------------------------------- | ------ | --------------------------------------------- |
| [legacy-modernizer](../plugins/framework-migration/agents/legacy-modernizer.md) | sonnet | Legacy code refactoring and modernization     |
| [context-manager](../plugins/agent-orchestration/agents/context-manager.md)     | haiku  | Multi-agent context management                |

## Model Configuration

Agents are assigned to specific Claude models based on task complexity and computational requirements.

### Model Distribution Summary

| Model  | Agent Count | Use Case                                                                           |
| ------ | ----------- | ---------------------------------------------------------------------------------- |
| Haiku  | 2           | Fast execution tasks: context management, API documentation                        |
| Sonnet | 60          | Complex reasoning, architecture, language expertise, orchestration, security       |

### Model Selection Criteria

#### Haiku - Fast Execution & Deterministic Tasks

**Use when:**

- Generating code from well-defined specifications
- Creating tests following established patterns
- Writing documentation with clear templates
- Executing infrastructure operations
- Performing database query optimization
- Handling customer support responses
- Processing SEO optimization tasks
- Managing deployment pipelines

#### Sonnet - Complex Reasoning & Architecture

**Use when:**

- Designing system architecture
- Making technology selection decisions
- Performing security audits
- Reviewing code for architectural patterns
- Creating complex AI/ML pipelines
- Providing language-specific expertise
- Orchestrating multi-agent workflows
- Handling business-critical legal/HR matters

### Hybrid Orchestration Patterns

The plugin ecosystem leverages Sonnet + Haiku orchestration for optimal performance and cost efficiency:

#### Pattern 1: Planning → Execution

```
Sonnet: backend-architect (design API architecture)
  ↓
Haiku: Generate API endpoints following spec
  ↓
Haiku: test-automator (generate comprehensive tests)
  ↓
Sonnet: code-reviewer (architectural review)
```

#### Pattern 2: Reasoning → Action (Performance)

```
Sonnet: performance-engineer (diagnose bottlenecks, create strategy)
  ↓
Haiku: Generate optimization code
  ↓
Haiku: deployment-engineer (deploy optimizations)
  ↓
Sonnet: observability-engineer (implement monitoring)
```

#### Pattern 3: Complex → Simple (Database Design)

```
Sonnet: database-architect (schema design, technology selection)
  ↓
Haiku: Generate migration scripts
  ↓
Haiku: Generate optimized queries
  ↓
Sonnet: database-optimizer (tune query performance)
```

#### Pattern 4: Multi-Agent Workflows

```
Full-Stack Feature Development:
Sonnet: backend-architect + frontend-developer (design components)
  ↓
Haiku: Generate code following designs
  ↓
Haiku: test-automator (unit + integration tests)
  ↓
Sonnet: security-auditor (security review)
  ↓
Haiku: deployment-engineer (CI/CD setup)
  ↓
Haiku: Setup observability stack
```

## Agent Invocation

### Natural Language

Agents can be invoked through natural language when you need Claude to reason about which specialist to use:

```
"Use backend-architect to design the authentication API"
"Have security-auditor scan for OWASP vulnerabilities"
"Get performance-engineer to optimize this database query"
```

### Slash Commands

Many agents are accessible through plugin slash commands for direct invocation:

```bash
/backend-development:feature-development user authentication
/security-scanning:security-sast
/incident-response:smart-fix "memory leak in payment service"
```

## Contributing

To add a new agent:

1. Create `plugins/{plugin-name}/agents/{agent-name}.md`
2. Add frontmatter with name, description, and model assignment
3. Write comprehensive system prompt
4. Update plugin definition in `.claude-plugin/marketplace.json`

See [Contributing Guide](../CONTRIBUTING.md) for details.
