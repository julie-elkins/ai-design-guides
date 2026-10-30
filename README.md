# AI Design Guides

One starting point for public design patterns, MCP tool contracts, AI operational
guides, and runnable evidence.

This repository is a directory and orientation layer. It does not copy the guides it
links to. Each linked repository remains the **canonical source**, meaning the
authoritative location for the content, examples, labs, and implementation evidence it
owns.

## Choose your path

### New learner

Start with the [Agent Evaluation Learning Path](https://github.com/julie-elkins/agent-evaluation-learning-path).
It provides the recommended sequence from technical foundations through building,
production operations, workflow evidence, measurement validity, and security.

Use the [Claude Architect Lab](https://github.com/julie-elkins/claude-architect-lab)
when you are ready for the first guided build path.

### Design-pattern reader

Start with the [Agent Systems Design Guide](https://github.com/julie-elkins/agent-systems-design-guide).
It explains the reusable decisions behind evidence contracts, refusal, metadata-only
boundaries, independent evaluation, human approval, semantic task outcomes, and
multi-turn agent evaluation.

### MCP builder

Read [Designing MCP Servers for Agent Callers](https://github.com/julie-elkins/mcp-server-design-guide).
It applies the same discipline to Model Context Protocol tool schemas, refusal shapes,
diagnostics, identity, credentials, stdio behavior, and real-client testing.

### Reviewer, recruiter, or hiring manager

Use this short path:

1. Read the [Agent Systems Design Guide](https://github.com/julie-elkins/agent-systems-design-guide)
   to see the reusable design reasoning.
2. Read [Agent Evaluation and Release](https://github.com/julie-elkins/agent-systems-design-guide/blob/main/AGENT_EVALUATION_AND_RELEASE.md)
   to see how requirements become component, trajectory, semantic, behavioral, and
   end-to-end evidence.
3. Read the [Research Design Guide for AI Systems](https://github.com/julie-elkins/agent-systems-design-guide/blob/main/RESEARCH_DESIGN_GUIDE.md)
   to see how a research question becomes a protocol, artifact, result, and bounded claim.
4. Open the [Agent Assurance Harness showcase](https://github.com/julie-elkins/agent-assurance-harness/blob/main/SHOWCASE.md)
   to see runnable synthetic evidence.
5. Use the [Agent Evaluation Checklist](https://github.com/julie-elkins/agent-assurance-harness/blob/main/AGENT_EVALUATION_CHECKLIST.md)
   to review the evaluation contract, evidence, grader validity, repeated runs, and
   release decision.
6. Read the [Production AI Agent Readiness Checklist](https://github.com/julie-elkins/agent-assurance-harness/blob/main/docs/PRODUCTION_AI_AGENT_READINESS_CHECKLIST.md)
   to see how the controls are reviewed without claiming production approval.

## Guide map

### General agent and workflow design

- [Agent Systems Design Guide](https://github.com/julie-elkins/agent-systems-design-guide)
  -- reusable patterns for agents, evaluations, technical-content systems, MCP
  servers, and developer tools.
- [Research Design Guide for AI Systems](https://github.com/julie-elkins/agent-systems-design-guide/blob/main/RESEARCH_DESIGN_GUIDE.md)
  -- how to define a bounded research question, lock a protocol, build a reproducible
  artifact, report uncertainty, and keep claims within the evidence.
- [Agent Evaluation and Release](https://github.com/julie-elkins/agent-systems-design-guide/blob/main/AGENT_EVALUATION_AND_RELEASE.md)
  -- how to move from requirements through test cases, traces, deterministic and
  semantic checks, multi-turn and trajectory evaluation, grader validation, and a
  bounded release decision.

### MCP design

- [MCP Server Design Guide](https://github.com/julie-elkins/mcp-server-design-guide)
  -- tool contracts and the failure modes that appear when a model chooses and
  interprets tools.

### Production operations and readiness

These documents remain in the
[Agent Assurance Harness](https://github.com/julie-elkins/agent-assurance-harness),
where the synthetic controls and runnable labs live:

- [Production AI Engineering Bridge](https://github.com/julie-elkins/agent-assurance-harness/blob/main/docs/PRODUCTION_AI_ENGINEERING_BRIDGE.md)
  -- connect a locally working workflow to operational evidence.
- [AI Incident Response](https://github.com/julie-elkins/agent-assurance-harness/blob/main/docs/AI_INCIDENT_RESPONSE.md)
  -- adapt incident response to model, context, tool, authorization, and recovery
  boundaries.
- [AI Incident Response Tabletop Lab](https://github.com/julie-elkins/agent-assurance-harness/blob/main/examples/ai-incident-response-lab/README.md)
  -- discuss containment, evidence, authority, and recovery using synthetic scenarios.
- [Advanced Production Operations](https://github.com/julie-elkins/agent-assurance-harness/blob/main/docs/ADVANCED_PRODUCTION_OPERATIONS.md)
  -- assign organizational ownership, communicate safely, and manage production
  changes.
- [Production AI Agent Readiness Checklist](https://github.com/julie-elkins/agent-assurance-harness/blob/main/docs/PRODUCTION_AI_AGENT_READINESS_CHECKLIST.md)
  -- cross-check evidence across ownership, delivery, authorization, observability,
  evaluation, guardrails, approval, change management, and recovery.

### Runnable evidence

- [Agent Assurance Harness](https://github.com/julie-elkins/agent-assurance-harness)
  -- offline, provider-neutral synthetic controls for acting, abstaining, and
  reporting honestly.
- [LLM Eval Validity](https://github.com/julie-elkins/llm-eval-validity)
  -- test whether an evaluation supports the decision being made from it.
- [Agent Evaluation Checklist](https://github.com/julie-elkins/agent-assurance-harness/blob/main/AGENT_EVALUATION_CHECKLIST.md)
  -- an operational review surface requiring an owner, evidence artifact, decision
  rule, and missing-evidence action for each evaluation control.

## How the repositories fit together

```text
AI Design Guides
    ├── design patterns
    │     ├── Agent Systems Design Guide
    │     │     ├── Agent Evaluation and Release
    │     │     └── Research Design Guide
    │     └── MCP Server Design Guide
    ├── operational guides and runnable evidence
    │     ├── Agent Assurance Harness
    │     └── Agent Evaluation Checklist
    └── recommended learning sequence
          └── Agent Evaluation Learning Path
```

The design guides explain the decisions. The harness demonstrates bounded synthetic
evidence. The learning path tells a new learner what to read and run next.

## Scope and limits

This hub contains public links and orientation text only. It does not prove production
readiness, live model quality, customer adoption, learner completion, or business
impact. It does not authorize access to private data or external systems.

If a link points to a claim, lesson, lab, or implementation, inspect the linked
repository for its evidence and limitations.

MIT License.
