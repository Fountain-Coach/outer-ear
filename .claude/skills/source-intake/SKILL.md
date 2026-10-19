# Source intake and public disclosure review

## Purpose
Preserve approved public project originals as PDFs, faithful searchable Markdown transcriptions and verifiable provenance, without exposing private artist or applicant information.

## When to use
Every new project sketch, revised application paper, CV, budget, correspondence, rights decision or agreement proposed for this PUBLIC repo.

## Steps
1. Read AGENTS.md, PLANS.md, FCIS Publication and Source Policy and existing documents/SOURCES.md.
2. Check origin, authorship, public distribution rights, private contacts, signatures, financial/account data and consent. Withhold any uncertain personal or confidential content.
3. SHA-256 each source PDF; compare with existing sources; preserve byte-for-byte, deduplicating identical copies.
4. Transcribe text and headings into Markdown without paraphrase. Join print line wraps and reflect lists/section breaks; state those transformations.
5. Link transcript to original, update source manifest, and document any withheld source without disclosing its sensitive contents.
6. Locally verify hashes, complete transcription, Markdown links, no private CV/agreement, no credentials, Git diff and no Actions.
7. Only then commit; provide a real Git commit witness and update PLANS/FCIS_AUDIT with accurate claim status.

## Output contract
Approved original PDF + linked readable .md + hash manifest + documented rights/publication gate + verified Git commit; private material remains outside public Git.
