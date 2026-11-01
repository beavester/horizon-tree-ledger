# Horizon Tree test ledger

Public, dated rules for testing one claim about [Horizon Tree](https://horizon-tree.vercel.app). This repo exists so outsiders can check that the rules were set before any result. It is not investment advice and contains no company calls.

**Status on 1 November 2026: the claim is untested.** Nothing here shows it true or false.

## The claim

Claude finds links between fields of technology that are true, useful and new to specialists on both sides, more often than capable people given the same brief.

## How it is judged

**Supported** only if both F1 and F3 meet their "supported" thresholds.
**Refuted** if both F1 and F3 meet their "false" thresholds.
**If nothing is supported by 2028-11-01, the claim counts as false, not pending.**
If F1, F2 and F6 fail but F3 passes, the claim falls back to: "wide reading finds overlooked public links", with no claim of an edge.

| Test | Part of the claim | False if | Supported if | By |
|---|---|---|---|---|
| F1 | Better than capable people | Claude minus humans is 5 points or less, or Claude is under 15% | Claude is 25% or more, and 15 points or more above both humans and Claude's own within-field links, with the interval above 0 | 2027-03-31 |
| F2 | Breadth, not diligence | Claude minus within-field is 5 points or less | 15 points or more, interval above 0 | 2027-03-31 |
| F3 | Links nobody has stated | 90 or more of 100 links had an earlier public statement, or fewer than 5 of 100 are new and true | 20 or more of 100 have no earlier public statement and are rated true from both sides | 2027-06-30 |
| F4 | Links anticipate specialists | Fewer than 3 of 100 are later stated independently | 10 or more of 100 | 2028-11-01 |
| F5 | Cross-field links predict better | Brier score no better than a same-field control or the base rate, at 100+ per arm | Better than both by 0.05 or more | 2028-11-01 |
| F6 | Core to the ranked list | 1 or fewer of 100 cross-field-seeded names survive review, or under half the survival rate of a same-cycle control of 100 calendar-seeded names | 10 or more of 100, each failing if its link is removed | 2027-02-28 |
| F7 | Edge over markets | At 36 months, at or below the placebo median or the single-field book | Beats both, t of 2 or more | 2029-11-01 |

For F1, the score is the share of links blind specialists rate new AND true AND useful.

A pass on F6 cannot support the headline claim, because Claude runs that review gate. F6 can only remove the claim from the ranked list.

## What does not count as evidence

- any count graded only by Claude
- any chain chosen after reading the data
- any result on the rerate rows ranked on 1 November 2026
- any replay or retrospective score
- reach, edge counts or graph views
- praise from a rater who knew the source

## Limits

The thresholds are judgment calls made by an AI reviewer before any result, not derived from theory. The power figures behind them rest on assumptions. No market result within 12 months can confirm the claim. Spending, recruiting and any publication of company lists are separate decisions and are not promised here.

## Changes

Any threshold changed after a related result voids that test, and the project's site must say so. The git history and tags are the record.

## Frozen inputs

SHA-256 fingerprints of inputs fixed before any new links were generated. The files stay private until they are published; the fingerprint lets anyone check them later.

- 2026-11-01, link pool for test F3 (42 combinations and 618 prerequisite links): `079f702611b9decfc33ba817f57e74e09eaef60d84165174df02414fde4a4c60`
