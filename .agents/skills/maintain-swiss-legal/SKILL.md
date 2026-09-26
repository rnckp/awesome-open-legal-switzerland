---
name: maintain-swiss-legal
description: Maintain the awesome-open-legal-switzerland directory by finding and verifying new Swiss legal sources, updating outdated entries, and fixing duplicates, misplaced resources, access claims, and editorial issues. Use for recurring refreshes or targeted audits of this repository.
---

# Maintain Swiss Legal Resources

Keep the repository's README useful for finding Swiss legal sources, reusable datasets, and relevant tools. Prefer a smaller, well-supported list over growth for its own sake.

## Start from the current repository

Read `README.md`, applicable `AGENTS.md` instructions, and the working-tree diff. Treat the README's scope and contribution rules as the current editorial policy; preserve unrelated user edits. Resolve paths from the repository root, without relying on a particular checkout location.

For an ordinary refresh, perform discovery, an existing-entry audit, and local corrections. For a targeted request, limit work to the requested subject or checks. A review-only request produces findings without edits. Do not commit, push, open pull requests, or contact maintainers unless requested.

## Discover useful additions

Browse current sources rather than relying on memory. Search in German, French, Italian, and English as useful, covering federal and cantonal resources rather than only German-language or AI projects. Use the README's discovery directories as leads, then verify the original publisher.

Look across legislation and lawmaking, courts and regulators, guidance, registers and disclosures, legal scholarship, archives, research datasets, and developer tools. Prioritize gaps and resources offering distinct content, better access, reusable data, or a meaningful new capability. No minimum number of additions is required.

Apply these inclusion rules:

- Require a concrete Swiss legal use. Lawmaking, direct democracy, and political accountability belong; general government statistics or sector data do not qualify merely because they might support compliance.
- Accept free-to-consult sources, explicitly reusable data, and open-source tools under the README's policy. Exclude trials and limited commercial free tiers. Identify registration, geographic restrictions, API credentials, quotas, and paid dependencies when material.
- Distinguish official publishers, independent interfaces, derived datasets, and generated answers. A catalogue record does not imply free full text; a repository does not imply an open-source licence.
- Keep directories and community resources selective. Additional wrappers around the same source need an identifiable benefit; do not add every MCP server or AI demo.
- Before reintroducing a removed resource, check the available repository history and whether the reason for removal has changed. Justement and the food-safety MCP were deliberately excluded; reassess only with evidence of a material change or a user request.

## Audit and verify

For a full refresh, inventory all entries and their links. Review every entry's relevance, placement, duplication, and wording; attempt primary-link checks across the list, and inspect supporting API, code, download, and terms links where claims depend on them. Prioritize substantive re-verification of volatile claims, previously uncertain entries, moved sites, software integrations, and dataset releases. Explicitly report any coverage left incomplete.

Use the publisher's resource page, documentation, dataset card, release record, and licence as evidence. Search snippets and third-party lists are discovery aids, not sufficient support for additions or factual corrections. Record concise working notes with the entry, check date, evidence URL, finding, and proposed action; keep these outside the committed README unless a persistent report is requested.

Check:

- Whether the destination still serves the described resource, including redirects, renamed projects, and replacement platforms. HTTP 200 alone does not establish usefulness.
- Whether the content is full text, metadata, headnotes, summaries, catalogue records, or generated output.
- Jurisdiction, dates, languages, and completeness. Coverage of all cantons does not mean all courts or all decisions; multilingual collections do not imply translations of every item.
- Dataset versions and actual release history. Separate a fixed historical corpus from a maintained service, and stated update intentions from demonstrated updates. A valuable archive is not obsolete because it stops at a historical date.
- Access and reuse separately. Verify which licence applies to software, metadata, source documents, or derived data. Prefer the licence file or formal rights statement; qualify claims supported only by package metadata or conflicting documentation.
- Whether an API still exists and what access it requires. Use documentation or small unauthenticated read-only checks; do not install or enable listed MCP servers, run candidate code, or download large corpora merely to verify a listing.

A timeout, HTTP 403/429, bot challenge, or JavaScript-only response means unverified, not defunct. Try the publisher's navigation, canonical URL, and an alternative read-only access method before deciding. Remove or replace confirmed obsolete, out-of-scope, or redundant entries; retain uncertain entries with restrained wording and report the uncertainty. If browsing is unavailable, complete structural work but do not claim current external verification.

## Edit concisely and place consistently

Use the existing Markdown bullet style: linked name, useful content and coverage, then access methods and known terms. Avoid marketing, unsupported superlatives, volatile record counts, and generic disclaimers. Date claims tied to a release or status notice. Keep evidence in direct resource/documentation links rather than adding research narration to the README.

Prefer one main entry per project, with API, download, and source-code links together. Separate entries are justified for distinct tasks; cross-reference them instead of repeating a project's entire description. Merge a hosted MCP endpoint and its source repository into one entry.

Place resources by their material or task, following the current headings:

- Legislation and treaties with legal texts; parliamentary and consultation material with lawmaking, or archives for historical datasets.
- Court decisions apart from administrative rulings and recommendations; guidance apart from legislation.
- Research corpora and benchmarks together; APIs, libraries, AI applications, and MCP integrations under developer tools.
- Journals, commentaries, repositories, and catalogues under literature; discovery directories and events under community resources.

Prefer official sources before independent interfaces. Preserve the separate list of all 26 official cantonal collections and its canton-code order. Keep the contents dropdown collapsed by default. Adjust headings only when a concrete classification problem warrants it, updating the contents and all affected cross-references.

## Validate and deliver

Review the final diff for accidental deletions, duplicate projects under different names, scope drift, and unsupported claims. Check internal anchors and relative links, contents coverage, the closed `<details>` block, and all 26 unique canton entries. Run `git diff --check`. Recheck changed external destinations when they have not already been verified during this run.

Return a concise summary of additions, corrections, moves/merges, and removals with reasons. Include primary evidence links for material factual changes or unresolved conflicts. State what was checked and what remains unverified; never describe a sampled audit as exhaustive. No-change results are valid. Leave only requested maintenance artifacts in the working tree, without automatically adding audit logs, timestamps, or tooling.
