# Nostradamus Intellect

**The public scorekeeper of forecasts.** Every claim sealed with a probability, a date and a way to be wrong — then
graded in public, ours included. Misses are printed at the same size as hits.

[![ledger seals](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fnostradamusintellect.com%2Fengine%2Frecord.json&query=%24.counts.ledger_seals&label=ledger%20seals&color=4fd2ff)](https://nostradamusintellect.com/ledger)
[![sealed statements](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fnostradamusintellect.com%2Fengine%2Frecord.json&query=%24.counts.sealed_statements&label=sealed%20statements&color=ffae6b)](https://nostradamusintellect.com/sealed-statements)
[![graded](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fnostradamusintellect.com%2Fengine%2Frecord.json&query=%24.counts.graded&label=graded&color=9fb4c9)](https://nostradamusintellect.com/proving-ground)
[![first verdict](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fnostradamusintellect.com%2Fengine%2Frecord.json&query=%24.first_verdict&label=first%20verdict&color=3ce28a)](https://nostradamusintellect.com/ledger/2026-warmest-year-on-record)

*Live figures, read from [/engine/record.json](https://nostradamusintellect.com/engine/record.json) each time this page is shown.*

## What we do

- **Seal.** Forecasts on geopolitics, finance, AI, climate, society and space, each with a probability, a resolve-by
  date and a criterion a stranger could adjudicate — hashed, and anchored to Bitcoin through OpenTimestamps before the
  outcome. [The ledger →](https://nostradamusintellect.com/ledger)
- **Score.** Brier scores against a stated baseline per item, a 72-hour public challenge window, rules pre-registered
  while every seal was pending. [How a seal is resolved →](https://nostradamusintellect.com/how-a-seal-is-resolved)
- **Seal other people's claims.** Dated, falsifiable forecasts by public figures, quoted exactly, steelmanned and graded
  on the same terms. [Sealed statements →](https://nostradamusintellect.com/sealed-statements)
- **Watch.** A deterministic engine of 36 named strands, moved by eight live wires under a published, versioned rule,
  shows how far the world has moved since each number was sealed. It tracks the numbers; it does not write them.
  [The Core →](https://nostradamusintellect.com/core)

## Use it

| | |
|---|---|
| Website | [nostradamusintellect.com](https://nostradamusintellect.com) |
| The record as JSON (free, no key) | [/engine/record.json](https://nostradamusintellect.com/engine/record.json) · one card: `/engine/cards/<id>.json` |
| MCP server (Claude, Cursor, any client) | `npx -y nostradamus-intellect mcp` — [setup](https://github.com/NostradamusIntellect/nostradamus-intellect-mcp#connect-it-to-an-ai-client-stdio) |
| CLI | `npx -y nostradamus-intellect summary` — [on npm](https://www.npmjs.com/package/nostradamus-intellect) |
| Verify every seal yourself | `npx -y nostradamus-intellect verify all` |
| For language models | [llms.txt](https://nostradamusintellect.com/llms.txt) · [llms-full.txt](https://nostradamusintellect.com/llms-full.txt) |
| What can be proven before the first grade | [The Proving Ground](https://nostradamusintellect.com/proving-ground) |

## How we keep score

1. **A sealed probability is never rewritten.** Corrections are dated addenda, printed under the seal.
2. **Misses are published at the same size as hits.**
3. **The same number for everyone.** Paying buys data, history, alerts and delivery — never a different probability.
4. **Every seal can be checked without trusting us.** The sealed fields, their SHA-256, the ledger root and the
   timestamp proofs are public.
5. **No track record is claimed before one exists.** 0 cards are graded; the first verdict is on 2027-02-28. On the
   sixteen ledger seals, a perfectly calibrated forecaster would still expect about five misses.

## Open source here

- [**nostradamus-intellect-mcp**](https://github.com/NostradamusIntellect/nostradamus-intellect-mcp) — the `ni` CLI and
  an MCP server for AI agents: search the record, read any card, the resolution calendar, the engine's strands, event or
  echo, verify a seal. Apache-2.0, no dependencies, read-only.
- [**nostradamus-intellect-protocol**](https://github.com/NostradamusIntellect/nostradamus-intellect-protocol) — how a
  forecast is written, sealed, verified and graded: the protocol, the card schema and a standalone verifier. CC BY 4.0.

## Work with us

Built in the open by one founder. We are looking for people:

- **Builders:** see [where we need help](https://github.com/NostradamusIntellect/nostradamus-intellect-mcp/blob/main/CONTRIBUTING.md)
  — a remote MCP endpoint, a Python client, framework adapters, reliability diagrams, translations. Issues and pull
  requests are welcome, and we are open to people who want to join the founding team: engineers, forecasters, data and
  research people, French-language editors.
- **Forecasters and researchers:** seal your own numbers through the
  [Observer Protocol](https://nostradamusintellect.com/observers) and be graded by the same rule on the same date.
- **Newsrooms, platforms and institutions:** the record as data, embeddable cards, questions commissioned by you and
  graded in public, calibration training for teams — [nostradamusintellect@proton.me](mailto:nostradamusintellect@proton.me)
- **Investors:** [nostradamusintellect@proton.me](mailto:nostradamusintellect@proton.me)
- **Donors and supporters:** reading the record is free forever, with no ads and no trackers. If you want to help keep
  it that way, write to us.
- **Agents:** connect through the [MCP server](https://github.com/NostradamusIntellect/nostradamus-intellect-mcp), or
  read [/engine/record.json](https://nostradamusintellect.com/engine/record.json) and
  [/llms.txt](https://nostradamusintellect.com/llms.txt). No key needed.
- **Found a wrong number or a seal that does not verify?** Open an issue. We correct in public, with a date.

Nothing can be bought: partnerships, sponsorship, donations and investment never change a probability, a date or a
criterion.

[nostradamusintellect.com](https://nostradamusintellect.com) · [X @Nostradamusmind](https://x.com/Nostradamusmind) ·
[nostradamusintellect@proton.me](mailto:nostradamusintellect@proton.me)

<sub>Not financial, medical, legal or safety advice. Forward-looking content is probabilistic simulation. This is not a
reading of Michel de Nostredame and not a horoscope.</sub>
