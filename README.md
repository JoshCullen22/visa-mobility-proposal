# Visa: Outbound Mobility for Filipino Creative Workers

**Author:** Josh Cullen Santos, co-founder, 1Z Entertainment

A policy proposal to help Filipino artists and creative workers work abroad: an official
DFA endorsement letter, government talks on fair visa treatment in both directions, and one
inter-agency playbook. I wrote it and presented it to the Office of Senator Bam Aquino on
27 May 2026, then sent it to his office on 2 June 2026.

Every version below is anchored to the Bitcoin blockchain with
[OpenTimestamps](https://opentimestamps.org). The proof shows each exact file existed no later
than the listed block. Changing one byte of a PDF breaks its proof.

## Version history

| # | File | What it is | Bitcoin block | Earliest proven time (Philippine time) |
|---|---|---|---|---|
| 1 | `01-2026-05-27-one-page-brief.pdf` | One-page brief, the leave-behind | 951172 | 27 May 2026, 05:15 |
| 2 | `02-2026-05-27-deck-signal-edition.pdf` | Deck, alternate design | 951201 | 27 May 2026, 10:16 |
| 3 | `03-2026-05-27-deck-as-presented.pdf` | Deck as presented and sent on 2 June | 968956 | 28 September 2026, 14:28 (see note) |
| 4 | `04-2026-06-01-deck-expanded.pdf` | Expanded deck, revised after the meeting | 951986 | 1 June 2026, 21:36 |

**Note on file 3.** This deck was not stamped in May. Its Bitcoin proof dates from
28 September 2026. It is byte-identical to the file
attached to my email to the Senator's office on 2 June 2026.

SHA-256 fingerprints for all four files are in `SHA256SUMS`.

The git history of this repository records when each file was uploaded here. The dates that
count are the Bitcoin ones above.

## Clean edition (28 September 2026)

The folder `clean-edition-2026-09-28/` holds a layout-corrected copy of all four files. The
wording is unchanged. Only spacing and text-box sizes were adjusted so no line wraps into or
overlaps another.

These are new files, so their Bitcoin proofs date from 28 September 2026 (block 968957, 14:28 Philippine time). The originals above
stay exactly as they were, and they carry the May and June proofs.

## Check it yourself

1. Download a PDF and its matching `.ots` file.
2. Go to https://opentimestamps.org and drop in the `.ots` file, then the PDF.
3. It shows the Bitcoin block and time.

With the command-line client:

```
ots verify 01-2026-05-27-one-page-brief.pdf.ots
```
