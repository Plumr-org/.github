<p align="center">
  <img src="https://raw.githubusercontent.com/Plumr-org/.github/main/profile/plumr-logo.svg" alt="Plumr" width="84" />
</p>

<h1 align="center">Plumr</h1>

<p align="center">
  <strong>Design agents. Deploy intelligence.</strong>
</p>

<p align="center">
  The visual studio for building, testing, and deploying production-grade AI agents.
</p>

<p align="center">
  <a href="https://plumr.studio">Website</a>
  ·
  <a href="https://app.plumr.studio">Studio</a>
  ·
  <a href="https://github.com/Plumr-org/sdks">SDKs</a>
  ·
  <a href="mailto:hello@plumr.studio">Contact</a>
</p>

---

## What we build

Plumr is a visual platform for composing AI agents. You drag nodes onto a canvas — an orchestrator, sub-agents, tools, prompts, classifiers — connect them, configure your models, and ship the whole thing as a streaming HTTP API. Bring your own keys for OpenAI, Anthropic, or Gemini; we handle the runtime.

```
input  →  orchestrator  ⇄  { sub-agents · tools · prompts }  →  streamed response
```

Every call streams Server-Sent Events for token deltas, tool calls, and run telemetry, so clients can render reasoning in real time.

## What lives here

| Repository                                                           | What it is                                                          |
| -------------------------------------------------------------------- | ------------------------------------------------------------------- |
| [**sdks**](https://github.com/Plumr-org/sdks)                        | Official Plumr client libraries — TypeScript, Python, Go, and more. |

Most repositories are private during the closed beta. If you've got beta access, you'll see the rest from your dashboard.

## Get involved

- Read the docs at [plumr.studio/docs](https://plumr.studio/docs)
- File issues or open discussions on the [SDKs repo](https://github.com/Plumr-org/sdks)
- Email [hello@plumr.studio](mailto:hello@plumr.studio) for partnerships, beta access, or anything else

<br/>

<p align="center">
  <sub>Plumr is in private beta. <a href="https://plumr.studio">Request access →</a></sub>
</p>
