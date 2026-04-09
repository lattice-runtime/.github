<div align="center">

# Lattice Runtime

### Don't adopt a vendor.

**Model-agnostic managed agent infrastructure.**<br>
**Any model. Your infrastructure. Governed.**

---

We build the runtime layer between your agents and your models.<br>
One Go binary. Any LLM behind it. Five governance gates on every action.

</div>

## What we ship

- **[Lattice Runtime](https://github.com/lattice-runtime/lattice-runtime)** — managed agent infrastructure. Model-agnostic, self-hosted, governed. Single Go binary with embedded Temporal, cryptographic audit, RBAC+ABAC policy engine, budget enforcement, and WireGuard zero-trust mesh.

- **[Website](https://latticeruntime.com)** — landing page, full interactive architecture, and engineering blog.

## The pitch in 30 seconds

Today's managed agent platforms lock you to one model, one cloud, one vendor. When the provider deprecates a model version, your agents break. When compliance says data can't leave your infra, you're stuck. When you need Opus for planning but Sonnet for file edits, you pay Opus prices for everything.

Lattice Runtime decouples the brain from the model:

```
generate(messages, tools) → response    // any model
getEvents(from, limit)    → stream      // durable session, yours
execute(name, input)      → string      // 6 runtime backends
```

Each interface can fail independently. Each can be swapped. The abstraction outlasts the provider.

## Get early access

We're a two-person team rolling out access in phases.

1. **[Star the repo](https://github.com/lattice-runtime/lattice-runtime)** — we reach out to stargazers first
2. **[Open an issue](https://github.com/lattice-runtime/lattice-runtime/issues/new?template=early-access.md)** — tell us your use case
3. **Watch for the invite**

---

<div align="center">

**The abstraction outlasts the provider.**

[latticeruntime.com](https://latticeruntime.com) · [Architecture](https://latticeruntime.com/architecture) · [Blog](https://latticeruntime.com/blog)

</div>
