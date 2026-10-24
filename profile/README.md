# 🌟 Sidera Protocol

**Stellar Name Service — send payments to `alice.sid`, not to a checksum.**

Sidera maps human-readable names to Stellar addresses with **memo hints**,
so exchange payments stop getting lost and wallets stop asking users to
paste 56 characters.

## The suite

| Repo | Layer | CI |
|---|---|---|
| [sidera-contracts](https://github.com/Sidera-Protocol/sidera-contracts) | Soroban name registry — deployed on **testnet** (`CAJL7DAF…GZKVQ`) | ![CI](https://github.com/Sidera-Protocol/sidera-contracts/actions/workflows/ci.yml/badge.svg) |
| [sidera-sdk](https://github.com/Sidera-Protocol/sidera-sdk) | TypeScript client — resolution, memo parsing, transactions | ![CI](https://github.com/Sidera-Protocol/sidera-sdk/actions/workflows/ci.yml/badge.svg) |
| [sidera-app](https://github.com/Sidera-Protocol/sidera-app) | Next.js dashboard — search, resolve, claim | ![CI](https://github.com/Sidera-Protocol/sidera-app/actions/workflows/ci.yml/badge.svg) |

## Why it matters

Every mature chain converged on a name service (ENS, SNS, ANS). Stellar —
the payments chain — had none. And Stellar's failure modes are worse:
exchanges require **memos**, and a memo-less payment is a lost payment.
Sidera treats the memo hint as a first-class part of resolution.

## Contribute

Contributions are welcome across all three repos. Start with any issue
labeled `external-contributors`. Read the `CONTRIBUTING.md` in each repo;
comment on an issue and wait for assignment before starting work.
