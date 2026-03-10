# TraceRoot

**Open trust infrastructure for agent skills and local agent runtimes.**

TraceRoot is an open-source ecosystem for making agent skills and local agent runtimes easier to inspect, trust, and secure.

As agent ecosystems grow, the biggest risks are no longer just model quality or tool capability. The real problems are becoming:

- untrusted skills and plugin supply chains
- unsafe local runtime exposure
- overbroad permissions
- missing trust metadata
- weak provenance and auditability
- dangerous execution patterns that are hard to inspect before damage happens

TraceRoot exists to build practical, developer-friendly trust infrastructure for agent ecosystems.

## Mission

Build open, model-agnostic trust tooling for agent skills, manifests, execution provenance, and local agent runtime security.

TraceRoot is designed to work across agent ecosystems instead of being tied to a single model provider, runtime, or framework.

## Principles

- **Open first** — trust infrastructure should be inspectable and community-driven
- **Model agnostic** — not tied to one LLM vendor
- **Runtime aware** — focused on how agents actually run, not just abstract policy
- **Developer friendly** — easy to integrate into local projects, CI, and skill pipelines
- **Practical over theoretical** — solve real security and trust issues visible in agent ecosystems today

## Projects

### `traceroot-audit`
Open-source trust and security scanner for agent skills and local agent runtimes.

It helps developers detect:

- risky or suspicious skill behavior
- unsafe execution patterns
- overbroad permissions
- missing trust metadata
- weak provenance signals
- unsafe local runtime and deployment exposure

## Why TraceRoot

Agent platforms will continue improving built-in approvals, sandboxing, and tool controls.

But the broader ecosystem still needs open infrastructure for:

- trustable skill metadata
- external auditing
- supply-chain inspection
- provenance
- runtime posture checks
- portable trust signals across projects

TraceRoot focuses on that layer.

## Scope

TraceRoot is **not** trying to build:

- a new agent runtime
- a universal LLM control plane
- a full security platform for all AI systems
- a replacement for model-provider-native approvals

TraceRoot focuses specifically on **trust infrastructure for agent skills and local agent runtimes**.

## Get involved

If you are building agent skills, local agent tooling, security rules, manifests, or provenance systems, contributions and discussions are welcome.

## License

Apache-2.0
