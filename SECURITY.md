# Security and Responsible Disclosure

## Scope of This Disclosure

This repository and the associated private repositories (BankingMCP, BankingAPI, FinanceNewsMCP) are **research artifacts** for the paper "Managing the Risks of Adopting the Model Context Protocol." The attack technique demonstrated — cross-server tool poisoning via a malicious MCP server — is real and fully reproducible.

The private repositories contain working proof-of-concept code. They are access-gated intentionally to prevent the artifacts from being repurposed for unauthorized attacks.

## Important Caveats

- **All IBANs** used in the demo are synthetic and non-functional. No real bank accounts are involved.
- **PSD3 Art. 17b** is fabricated. It does not exist in any EU payment services directive. The citation in the demo is part of the attack payload itself — designed to exploit the model's deference to regulatory language.
- The `FinanceNewsMCP` artifact carries a **do-not-deploy notice** in its source code. It must not be run outside a controlled research environment.
- This is a responsible demonstration of a **documented vulnerability class** (MCP tool poisoning, per OWASP GenAI and Invariant Labs prior disclosures), not a novel zero-day being withheld.

## Vulnerability Class

Tool poisoning via MCP is a known and publicly documented vulnerability class. The paper describes the mechanism in full. The artifact makes one concrete instantiation demonstrable end-to-end. The underlying issue — MCP's lack of provenance separation between server outputs — is architectural and affects any host that connects multiple MCP servers without human-in-the-loop confirmation of irreversible actions.

## Responsible Use

By requesting access to the private repositories, users agree to:
- Use the artifacts only for academic research, security evaluation, or defensive tooling
- Credit the authors in any published work that builds on these artifacts
- Not deploy FinanceNewsMCP or derivatives against real users or systems without authorization

## Contact

For security-related questions about these artifacts, please contact:

<!-- Replace with the authors' contact email -->
**[contact email — to be filled in by authors]**

For access requests, use the [issue template](../../issues/new?template=access-request.yml).
