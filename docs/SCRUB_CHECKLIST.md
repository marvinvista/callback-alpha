# Scrub Checklist

Use this before publishing the repo or merging content changes.

## Source Safety

- No copied text from books, PDFs, courses, newsletters, or paid communities
- No close paraphrases that track the source structure too tightly
- No filenames, citations, or wording that reveal internal source documents unless intentionally public
- No excerpts that would be recognizable as lifted material

## Privacy And Confidentiality

- No customer names unless already public and intentionally included
- No account lists from private CRM data
- No deal notes, email threads, call transcripts, or meeting notes
- No internal company terminology that should stay private
- No personal data, email addresses, phone numbers, or employee details

## Repo Hygiene

- No absolute local filesystem paths
- No hidden dependency on private tools or documents
- No internal-only instructions such as "see my notes" or "based on our client examples"
- No placeholder TODOs that mention non-public materials

## Skill Quality

- Each skill still does one clear job
- `SKILL.md` remains concise
- Reference files support the skill instead of repeating it
- Output contracts still match the intended behavior
- Eval cases still reflect the skill's current scope

## Quick Commands

Run string scans from repo root:

```bash
rg -n "\\.pdf|TODO|internal|private|confidential" .
rg -n "copyright|all rights reserved|do not distribute" .
```

Review changed files manually for:

- suspiciously polished paragraphs that may be source-derived
- lists that mirror a known source too exactly
- examples that look like real customer data

## Release Decision

Publish only when:

1. the content is original or clearly redistributable
2. private context has been removed
3. the skill still works without hidden internal dependencies
4. the eval pack still passes spot checks
