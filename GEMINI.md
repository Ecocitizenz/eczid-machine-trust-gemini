# ECZ-ID Machine Trust

ECZ-ID Machine Trust plugins: local-first, read-only evidence reviews and Resolver posture checks for MCP servers, agents, APIs, SBOM / CRA and DORA. Free agent plugins, MIT-licensed, no purchase required. No account. No source upload. No telemetry.

## Doctrine

- Backend/Core writes canonical ECZ-ID truth. TrustOps owns acquisition, payment and entitlement. Resolver is the public read-only proof surface. The Developer Gateway documents and routes.
- This plugin inspects, explains and routes. It never writes truth, activates proof, marks anything bound, runs checkout or grants entitlement.
- OBSERVED is not ENFORCED. Nothing in a plugin mediates traffic; ENFORCED requires genuine mediation proof, which only the VS Code Local Trust Gate produces.
- No numeric safety, security or trust score. Results use evidence, ReasonCodes and Review Priority (LOW / NORMAL / ELEVATED / HIGH) with the reasons shown.
- Absence of public Resolver proof does not mean a target is unsafe. Local policy decides. Re-check before reliance.
- Local-first and privacy-first: reviews read filenames and paths in the workspace you point them at. No source, prompt, secret or tool payload is uploaded. No telemetry. Credential-shaped values are never displayed or recorded, only key names.

## Skills in this extension

- `ecz-id-verify` — ECZ-ID MCP Verifier: ECZ-ID public proof checks.
- `mcp-trust-review` — ECZ-ID MCP Trust: Review MCP servers in a repo.
- `agent-trust-review` — ECZ-ID Agent Trust: Review agent reach in a repo.
- `sbom-cra-evidence-review` — ECZ-ID SBOM & CRA Readiness: SBOM & CRA evidence review.
- `api-trust-review` — ECZ-ID API Trust: Review API surfaces in a repo.
- `dora-evidence-review` — ECZ-ID DORA Readiness: Review DORA evidence gaps.

Documentation: https://developers.ecocitizenz.com
