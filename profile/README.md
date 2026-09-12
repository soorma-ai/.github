<div align="center">
<h1>soorma.ai</h1>
<h3>Governed infrastructure for enterprise AI agents</h3>
</div>

### Mission

Soorma — *warrior*, *brave* — is a platform on which developers across
organizations build their own agentic systems.

The hard problem in production agentic systems is not prompting. It is governing
what a fleet of autonomous agents is permitted to do, and being able to say
afterwards who did what, under whose authority, and on whose behalf. Identity,
authority, and a complete audit record are foundations of the architecture here
rather than features added later.

### Status — rebuilding

The v0.x implementation is **retired**. It was built to explore a
distributed-cognition architecture and did that successfully, but it was not
built to be an enterprise platform: it grew without specifications, and it
predates the governance architecture the platform now targets. Refactoring it
toward an architecture it was never shaped for would have cost more than starting
again.

Nothing is released yet. Design precedes code, and the work happens in the open.

### Repositories

| Repository | What it is | Licence |
| :--- | :--- | :--- |
| [**soorma-core**](https://github.com/soorma-ai/soorma-core) | The server-side substrate — the shared planes agents run against, and where enforcement lives | FSL-1.1-ALv2 |
| [**soorma-sdk**](https://github.com/soorma-ai/soorma-sdk) | The client harness SDKs an agent embeds, in every language they ship in | Apache 2.0 |
| [**soorma-core-legacy**](https://github.com/soorma-ai/soorma-core-legacy) | The retired v0.x implementation, archived and read-only | MIT |

`soorma-core` is **source-available, not open source**. You may do anything with
it except offer a commercial product or service that competes with soorma.ai —
internal use at any scale, research, and education are all permitted. Every
release converts to Apache 2.0 two years after it ships, automatically and
irrevocably. That is the self-hosting guarantee: if soorma.ai ceases to exist,
everything older than two years is already Apache 2.0 and the rest converts on
schedule.

The harness is Apache 2.0 permanently. It runs client-side in the agent's hot
path and enforces nothing, so a use restriction there would reach into tenant
systems while defending nothing.

### Follow along

- [soorma.ai](https://www.soorma.ai)
- Watch [soorma-core](https://github.com/soorma-ai/soorma-core) to see the substrate take shape

<div align="center"><sub>© 2026 soorma.ai</sub></div>
