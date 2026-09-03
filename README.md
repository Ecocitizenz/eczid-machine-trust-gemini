# ECZ-ID Machine Trust — Gemini CLI extension

> **GENERATED — DO NOT HAND EDIT**
>
> - Canonical source repo: https://github.com/Ecocitizenz/eczid-agent-plugins
> - Canonical source commit: 11ffd8ff2cb5a4d17b6aeee1ae91487da1ae7e03
> - Generation command: npm run gemini (in the canonical source repo)
>
> Every file in this repository is written by the ECZ-ID Plugin Foundry from the canonical
> estate above. Edits made here are overwritten by the next generation and are not the
> source of truth. Open issues and pull requests against the canonical source repo.

ECZ-ID Machine Trust plugins: local-first, read-only evidence reviews and Resolver posture checks for MCP servers, agents, APIs, SBOM / CRA and DORA. Free agent plugins, MIT-licensed, no purchase required. No account. No source upload. No telemetry.

## Free. No purchase required.

Every skill in this extension is free and open source under the MIT licence. No account, no sign-in, no licence key, no trial and no paywall. The paid ECZ-ID products (VS Code Pro editions, TrustOps Passports and tiers) are separate products that this extension does not sell, unlock or require.

## Install

```
gemini extensions install https://github.com/Ecocitizenz/eczid-machine-trust-gemini
```

Gemini CLI reads `gemini-extension.json` at the root of this repository and auto-discovers every skill at `skills/<name>/SKILL.md`. The extension configures one pinned, read-only stdio MCP server (`@ecocitizenz/ecz-id-mcp-verifier@0.9.0`), launched with npx; nothing is installed globally.

## Skills

| Skill | Product | What it answers |
|---|---|---|
| `ecz-id-verify` | ECZ-ID MCP Verifier | ECZ-ID public proof checks |
| `mcp-trust-review` | ECZ-ID MCP Trust | Review MCP servers in a repo |
| `agent-trust-review` | ECZ-ID Agent Trust | Review agent reach in a repo |
| `sbom-cra-evidence-review` | ECZ-ID SBOM & CRA Readiness | SBOM & CRA evidence review |
| `api-trust-review` | ECZ-ID API Trust | Review API surfaces in a repo |
| `dora-evidence-review` | ECZ-ID DORA Readiness | Review DORA evidence gaps |

## What every skill does and does not do

- Backend/Core writes canonical ECZ-ID truth. TrustOps owns acquisition, payment and entitlement. Resolver is the public read-only proof surface. The Developer Gateway documents and routes.
- This plugin inspects, explains and routes. It never writes truth, activates proof, marks anything bound, runs checkout or grants entitlement.
- OBSERVED is not ENFORCED. Nothing in a plugin mediates traffic; ENFORCED requires genuine mediation proof, which only the VS Code Local Trust Gate produces.
- No numeric safety, security or trust score. Results use evidence, ReasonCodes and Review Priority (LOW / NORMAL / ELEVATED / HIGH) with the reasons shown.
- Absence of public Resolver proof does not mean a target is unsafe. Local policy decides. Re-check before reliance.
- Local-first and privacy-first: reviews read filenames and paths in the workspace you point them at. No source, prompt, secret or tool payload is uploaded. No telemetry. Credential-shaped values are never displayed or recorded, only key names.

## Other hosts

Claude Code, VS Code, GitHub Copilot, Cursor, Codex CLI and Kiro install the same skills as Agent Plugins 1.0.0 packages from the canonical estate: https://github.com/Ecocitizenz/eczid-agent-plugins

Licence: MIT. The ECZ-ID Verifier npm package carries its own licence.
