# Can a shared link open a digitized manuscript at the right page?

Open a digitized book at the page someone actually meant to share.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/link-to-manuscript-page/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-link-to-manuscript-page/pulls)

## Why this matters

IIIF Content State describes a portable way to open an object at a particular place. Mirador tracks support for importing that state. A single-page example is a small, useful piece of the wider proposal.

## What to contribute

Choose an openly accessible IIIF manifest and create a Content State link for one page. Prototype loading it in a fresh Mirador session.

## How reviewers check it

Publish the manifest and target canvas URLs. Show that a new session selects the intended page. Include what happens when the manifest or canvas identifier is invalid.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/link-to-manuscript-page
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/link-to-manuscript-page/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-link-to-manuscript-page/security/advisories/new) for security reports.

## Sources

- [Mirador issue \#4386](<https://github.com/ProjectMirador/mirador/issues/4386>)
- [IIIF Content State API](<https://iiif.io/api/content-state/1.0/>)
