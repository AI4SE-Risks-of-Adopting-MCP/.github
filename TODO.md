# Outstanding Tasks

Track these items before and after the repository goes public.

## Required before going public

- [x] Set GitHub Organization name — replace `<YOUR-ORG>` in [README.md](README.md) and [CITATION.cff](CITATION.cff)
- [ ] Add OpenReview submission link / DOI badge to [README.md](README.md) once paper is submitted (deadline: 2026-05-31)
- [ ] Replace [assets/sequence-diagram.svg](assets/sequence-diagram.svg) with the real rendered diagram
- [ ] Replace [assets/sequence-diagram.puml](assets/sequence-diagram.puml) with the real PlantUML source
- [ ] Upload demo video to GitHub Releases (create release tagged `v1.0-demo`, title: "Demo: Cross-Server Tool Poisoning Attack") and update the video placeholder section in [README.md](README.md) with the release link
- [ ] Fill in contact email in [SECURITY.md](SECURITY.md)
- [ ] Create the three private repos in the same GitHub Organization: `BankingMCP`, `BankingAPI`, `FinanceNewsMCP`
- [ ] Add a research-use-only / do-not-deploy LICENSE file to each private repo (`BankingMCP`, `BankingAPI`, `FinanceNewsMCP`) — these must not use CC BY 4.0 (too permissive for attack artifacts); a custom notice or a restrictive license (e.g. CC BY-NC-ND 4.0) is appropriate

## Optional / post-submission

- [ ] Add `assets/demo-thumbnail.png` (a static preview frame from the video, used as a linked image in the README video section)
- [ ] Update [CITATION.cff](CITATION.cff) with final proceedings DOI once paper is published
- [ ] Update the BibTeX block in [README.md](README.md) with final proceedings metadata (page numbers, DOI)
- [ ] Remove or archive this TODO.md once all items are resolved
