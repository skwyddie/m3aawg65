# M3AAWG 65 — Links & References

A curated collection of resources, analyses, research and demos related to the **Model Context Protocol (MCP)**, agent-to-agent attacks, and related security topics discussed during M3AAWG 65.

> NOTE: This repository is a link directory only. Follow each linked resource for origin, context and full details.

---

## Table of contents

- [Research Papers](#research-papers)
- [Analysis & Incident Reports](#analysis--incident-reports)
- [Demos & Code Repositories](#demos--code-repositories)
- [Scanners & Discovery Tools](#scanners--discovery-tools)
- [Best practices & Security Guides](#best-practices--security-guides)
- [Videos & Presentations](#videos--presentations)
- [Contributing](#contributing)
- [License & Credits](#license--credits)

---

## Research Papers

- **Cross-agent privilege escalation — analysis**  
  Peer/industry write-up on cross-agent privilege escalation and how cooperating agents can free each other.  
  https://embracethered.com/blog/posts/2025/cross-agent-privilege-escalation-agents-that-free-each-other/

- **arXiv preprint (2509.24272)**  
  Research paper (arXiv) related to MCP/agent security (see paper for full abstract and technical details).  
  https://arxiv.org/abs/2509.24272

- **arXiv preprint (2407.15847)**  
  Additional academic work relevant to LLM/agent security and related attack surfaces.  
  https://arxiv.org/abs/2407.15847

---

## Analysis & Incident Reports

- **Cato Networks — CATO-CTRL PoC attack**  
  Technical blog post describing a proof-of-concept attack targeting Atlassian’s MCP integration (Cato Networks analysis).  
  https://www.catonetworks.com/blog/cato-ctrl-poc-attack-targeting-atlassians-mcp/

- **Kaspersky Securelist — supply-chain abuse via MCP**  
  Security analysis describing how Model Context Protocol integrations were abused in supply-chain attacks.  
  https://securelist.com/model-context-protocol-for-ai-integration-abused-in-supply-chain-attacks/117473/

- **Pillar Security — GitHub Copilot / Cursor vulnerability write-up**  
  Blog post describing a new vulnerability in GitHub Copilot and Cursor and how code agents could be weaponized.  
  https://www.pillar.security/blog/new-vulnerability-in-github-copilot-and-cursor-how-hackers-can-weaponize-code-agents

- **Pillar Security — Security risks of MCP**  
  Deep-dive article outlining various security risks introduced by Model Context Protocol deployments.  
  https://www.pillar.security/blog/the-security-risks-of-model-context-protocol-mcp

- **Invariant Labs — MCP GitHub vulnerability analysis**  
  Incident/analysis write-up covering a GitHub-related MCP vulnerability and its implications.  
  https://invariantlabs.ai/blog/mcp-github-vulnerability

- **HiddenLayer — exploiting MCP tool parameters**  
  Technical exploration of how MCP tool parameters can be abused and examples of attack vectors.  
  https://hiddenlayer.com/innovation-hub/exploiting-mcp-tool-parameters/

---

## Demos & Code Repositories

- **Demo: malicious MCP server (video + code)**  
  Video walkthrough plus the demo repo for a malicious MCP server used to demonstrate abuse cases.  
  - Video: https://www.youtube.com/watch?v=NQbbAoP_zEg&t=630s  
  - Code: https://github.com/alejandro-ao/demo-malicous-mcp-server

- **`damn-vulnerable-MCP-server` (repo + demo)**  
  Vulnerable MCP server repo intended for testing and demo purposes; includes a demo video.  
  - Repo: https://github.com/harishsg993010/damn-vulnerable-MCP-server  
  - Demo video: https://www.youtube.com/watch?v=4BI7VWfDVQE

- **`LLMmap` — mapping LLM/agent behaviors**  
  Repository for LLM mapping/analysis tools relevant to attack surface exploration and taxonomy.  
  https://github.com/pasquini-dario/LLMmap

- **`demo-malicous-mcp-server` (alternate)**  
  Another demo implementation used in presentations illustrating malicious MCP servers.  
  https://github.com/alejandro-ao/demo-malicous-mcp-server

---

## Scanners & Discovery Tools

- **Knostic — finding MCP servers with Shodan**  
  Blog post showing how MCP servers can be discovered via Shodan and why exposed servers are risky.  
  https://www.knostic.ai/blog/find-mcp-server-shodan

- **Knostic — MCP-Scanner**  
  Open-source scanner to detect MCP server instances and quickly assess exposure.  
  https://github.com/knostic/MCP-Scanner

- **Glama — MCP vulnerable server demo (hosted example)**  
  Hosted demo instance demonstrating a deliberately vulnerable MCP server for study and testing.  
  https://glama.ai/mcp/servers/@kenhuangus/mcp-vulnerable-server-demo

---

## Best practices & Security Guides

- **MCP Specification — security best practices (draft)**  
  Draft of the MCP specification containing recommended security best practices for implementers.  
  https://modelcontextprotocol.io/specification/draft/basic/security_best_practices

- **OAuth for Model Context Protocol — practical guide**  
  Discussion and guidance on using OAuth with MCP for secure authorization flows and integration patterns.  
  https://aaronparecki.com/2025/04/03/15/oauth-for-model-context-protocol

- **Sandipan Haldar — SAFE framework**  
  A blog post describing a SAFE framework (security-minded approach) for tooling/agent interactions.  
  https://www.sandipanhaldar.com/blog/safe_framework

---

## Videos & Presentations

- **Presentation: MCP / security demo (YouTube)**  
  Recorded talk/demonstration relevant to MCP attack modes and defensive considerations.  
  https://www.youtube.com/watch?v=W1exZ-KKNIE

- **YouTube — Exploits & MCP demos**  
  Additional recorded talk demonstrating MCP vulnerabilities and attack walkthroughs.  
  https://www.youtube.com/watch?v=oDjHQgIFPIo

- **Demo video (malicious MCP server)**  
  Walkthrough video demonstrating the demo malicious MCP server (see code above).  
  https://www.youtube.com/watch?v=NQbbAoP_zEg&t=630s

