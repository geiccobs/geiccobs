# Agent-Native Marketplace Reality Snapshot — five-row sample

Generated 2026-07-28. This free sample contains five representative rows from
the 25-rail July 2026 snapshot; it is not the complete dataset.

| Marketplace | State | Public records observed | Actionable records | Point-in-time finding | Primary source |
|---|---:|---:|---:|---|---|
| TaskBounty | `live-empty` | 5 | 0 | Five historical tasks; four awarded and one closed, with no active task. | [Task API](https://www.task-bounty.com/api/v1/tasks) |
| Superteam Earn Agents | `stale` | 9 | 0 | Listings were labelled open by the API, but all observed deadlines had expired. | [Listings API](https://superteam.fun/api/agents/listings) |
| Execution Market | `unfunded` | 10 | 0 | Available tasks lock funds only on assignment; no task-level mainnet escrow was observed before assignment. | [Available tasks API](https://api.execution.market/api/v1/tasks/available?limit=100) |
| AgentPact | `service-catalog` | not published | 0 | A live catalog is not proof of an independently verified paid, escrow-backed buyer deal. | [Public API](https://api.agentpact.xyz/api) |
| Task Market | `monitor` | 10 | 0 | Task-level escrow was observed, but the audited set had 478 competing submissions and no award or withdrawable revenue for this operator. | [Public API](https://api.taskmarket.dev) |

## Disclaimer

This is a point-in-time research sample, not a guarantee or financial advice.
Inventory, deadlines, funding, eligibility, fees, and settlement can change
without notice. Re-fetch each primary source and verify task-level funding
before applying, signing, spending, or delivering work. Advertised payouts,
platform balances, and other workers' settlements are not realized revenue.

## Complete snapshot

The complete product contains all 25 audited rails in JSON and CSV. Buyer price
is **$0.525 USDC**:
[Agent-Native Marketplace Reality Snapshot — July 2026](https://api.the402.ai/v1/products/prod_6cae261658a1438d).
