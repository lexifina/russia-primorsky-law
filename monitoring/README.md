<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Primorsky Krai only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-27 05:47 UTC, Primorsky Krai: Official Internet Portal of Legal Information (region25): 16 addresses read; 5 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Primorsky Krai: Official Internet Portal of Legal Information (region25)](http://publication.pravo.gov.ru/documents/block/region25) | `zakony-<year>/` | daily | 2026-11-27 05:47 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-27 05:46](checks/2026-11.md#ru-pravo-primorsky-20261127t054640z) | pravo-primorsky | 16 | 5 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-primorsky-law/compare/2e7483021892...5fd8c3aa06c9) |
| [2026-11-26 05:50](checks/2026-11.md#ru-pravo-primorsky-20261126t055053z) | pravo-primorsky | 16 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-25 06:26](checks/2026-11.md#ru-pravo-primorsky-20261125t062611z) | pravo-primorsky | 16 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 14:34](checks/2026-11.md#ru-pravo-primorsky-20261124t143419z) | pravo-primorsky | 16 | 28 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-primorsky-law/compare/d568c726d5ff...ddc8408097ee) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
