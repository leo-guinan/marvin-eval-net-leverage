# Net Leverage

Public, receipt-backed eval for Marvin. This repository defines the contract before claiming a result.

## Status

- Protocol: v0.1
- Latest run: not run
- Evidence status: scaffold only
- Public claim: none yet

Do not replace “not run” with a number. A synthetic fixture can prove the runner works; it cannot prove Marvin meets the standard.

## Standard

Time removed from Leo's week exceeds model cost plus supervision, correction, and recovery time.

## Test

Reconcile owned work, review time, correction time, model cost, and recovered time from an auditable weekly ledger.

## Reported metric

`net_leverage_hours` — owned-work hours minus supervision and correction hours; costs remain separately reported.

## Claim boundary

A ledger result is an observation for that week, not a forecast of future savings.

## Files

- `eval/index.json` — versioned contract and claim boundary.
- `validate.py` — dependency-free schema/contract check.

## Run

```sh
python3 validate.py
```

The first real report will include the fixture version, case count, model/prompt identifiers where applicable, pass/fail outcomes, failures, and an independent receipt.
