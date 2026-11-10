# OF-Chatter: capability and validation snapshot

**Updated:** November 10, 2026. **Installed local preview:** Chatter Control **0.10.0**. **Companion:** Qwen Desktop **0.7.3**.

This is a public implementation summary. It contains no application source, private conversations, account records, local paths, datasets, model artifacts or installers. Local implementation is distinct from governed application-source admission and release approval.

## Capability status

| Capability | Implemented locally | Qualification boundary |
| --- | --- | --- |
| Windows application | Per-user installer/ZIP, bundled dashboard/API/PostgreSQL | Unsigned local preview; no public binary download here |
| Unified workspace | Highlighted navigation; files/personality, practice, datasets, candidate tests and agency review | Synthetic screenshots show the actual UI, not live operating results |
| Document intake | TXT/MD/CSV/JSON/JSONL/text PDF/DOCX, bounded extraction, quarantine, source hashes and supported Word sender layouts | No OCR; uncertain speaker attribution is reported |
| Named profiles | Saved instructions, exact revisions and assigned training datasets | Selecting a profile does not load its trained weights |
| Dataset paths | Independently reviewed Studio versions and explicitly owner-delegated local versions | Local delegation never claims independent Checker approval |
| Requested training | Qwen3-8B-abliterated with Unsloth QLoRA, 4-bit base, rank 16; durable start/cancel/results | Requires original weights/CUDA Python; uploads and feedback never automatically train |
| Flexible datasets | Any nonempty valid training set; grouped holdout where feasible | Resource/integrity/authorization limits remain; unavailable evaluation is explicit |
| Result evidence | Manifest, adapter artifacts, provenance hashes and held-out loss where available | Selected job/progress/audit evidence; no full persisted console log or loss curve |
| Private candidate chat | Direct loading of the verified saved LoRA; multi-turn context, saved sessions, reply ratings and corrections | No activation or website connection; separate human quality evaluation remains necessary |
| Candidate review export | Original responses and review history preserved; corrected/positively rated examples can be exported | Exports require later curation/review; ratings do not modify weights |
| Qwen companion | Requested file/data preparation, readiness/training, current-result lookup and normal-shortcut reconnection | Authenticated loopback; app permissions remain with the user; no workshop approve/send tool |
| Browser and agency workflow | Visible embedded Chromium, manual login, sampled observation, account/profile/model mapping, OBSERVE/SUPERVISED modes and flagged response review | Actual OnlyFans compatibility and delivery remain unverified |
| Supervised writer | Bound identity/fields, explicit placement and one-send approval, stale rejection, durable intent, reconciliation and stop/recovery | Synthetic fixture validation does not qualify a live connector |

## Current local verification

| Evidence | Recorded result | Limit |
| --- | --- | --- |
| Candidate-chat desktop checks | 62 tests passed | Local desktop suite at the candidate implementation revision |
| Candidate/workshop dashboard checks | Four relevant component tests passed; targeted lint, type checking and production build passed | Not a claim that every application suite ran |
| Python candidate prompt checks | Two tests passed | Context/role validation without training |
| Real adapter inference | Two conversational turns completed with previous-turn context | Functional inference only, no response-quality benchmark |
| Fine-tuning evidence | A completed local job, final manifest and saved adapter were verified | Per-profile transcripts, filenames and metrics remain private |
| Packaged application | Isolated database/API/dashboard startup, candidate tab, Windows encryption, restart and clean shutdown passed | Synthetic workspace, no real platform account |
| Installation integrity | Installed native modules and candidate worker matched the verified build | File integrity does not establish production security |

Public Docs CI validates these documentation files, local links and screenshot fingerprints. It does not run or approve the private application or validate private model artifacts.

## Private candidate test limits

Tests use the original non-thinking chat format, a 1,024-token window and up to 192 generated tokens. The full conversation is used; oversized input is rejected rather than silently truncated. Initial file verification/model loading can take minutes. The worker unloads after one minute idle, on Stop, on leaving the tab, before training or when the app exits. Testing pauses Chatter live drafting/observation and releases Ollama GPU models first. Other applications can still compete for GPU memory.

Conversations and corrections use Windows-protected storage with a 30-day retention period. Bounds are 50 saved sessions, 50 replies per session, 500 review events per session and the existing storage byte limit. Original files, explicit exports and adapter outputs are outside the encrypted learning store.

## Remaining work

1. Complete application-source admission, independent review and authorized exact-head application CI. This public documentation update grants none of those approvals.
2. Evaluate candidate voice, context handling and response quality through human review. A lower evaluation loss is not an accuracy or personality score.
3. Qualify real OnlyFans identity/field binding and delivery under issued authority. No unattended sending, account-operating scale or platform endorsement is claimed.
4. Complete signing, endurance/resource testing, retention and backup/recovery validation, and distribution hardening.

The [gallery](GALLERY.md) distinguishes current captures from historical screenshots. No production readiness, externally immutable audit or public application availability is asserted.
