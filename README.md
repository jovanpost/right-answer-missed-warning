# Right Answer, Missed Warning

When you paste an everyday document into a chatbot and ask one narrow question, does the model also tell you about the serious fact in the same document that you did not ask about?

This repo holds the pre-registration and frozen materials for that study. It is a self-funded, independent study, motivated by Shin (2026, arXiv 2606.26529v3).

**Status:** pre-registered. No model has been run on the study materials yet. Results, code and data will be added here after the run.

Author: Jovan Postoloski · ORCID [0009-0005-5176-9877](https://orcid.org/0009-0005-5176-9877)

## What is in this repo

| File | What it is |
|---|---|
| `pre-registration.pdf` | The full study plan, fixed before any run |
| `pre-registration.pdf.ots` | OpenTimestamps proof for the pre-registration |
| `study1-pairs-01-50.py` | The 50 frozen document pairs, questions and answer keys (source of truth) |
| `study1-judge-prompt.md` | The frozen prompt both AI judges use |
| `origin-note.txt.ots` | OpenTimestamps proof for a private, dated note on how the study started (only its hash is public) |
| `filing-day/` | Screenshots of each vendor's own pages used to pick the models, plus OpenRouter's live model list from filing day |

## Fingerprints (SHA-256)

Anyone can check a file with `shasum -a 256 <file>` (Mac or Linux).

| File | SHA-256 |
|---|---|
| `pre-registration.pdf` | `ea63504e05d3d39083f6c08a252a618e962f81c588b90b25070cab1d92295694` |
| `study1-pairs-01-50.py` | `b14afd01f0429eb6c43ccf7d7d87f52f9872fec0841c5c01397463805c50630b` |
| `study1-judge-prompt.md` | `0fc69b868df6d5a7fead85ea31bf0c36872d9686efb3b30e7ef9234ba34f008b` |
| `origin-note.txt` (private) | `939ea62684d154ca1b87f9628df58c5d20ba02bfce7e07a36a1aeccade673760` |

To check a timestamp proof: `ots verify pre-registration.pdf.ots` (needs the [OpenTimestamps client](https://github.com/opentimestamps/opentimestamps-client)).

## Changes

Any change after filing is a written, dated amendment in this repo, saying what changed, why, and whether any results had been seen.

## License

Code will be released under MIT and data under CC BY 4.0 together with the results.

AI assistance (Claude) was used to draft the documents and materials, as disclosed in the pre-registration.
