# Scope of results and maturation priorities

This note supplements the public dossier. It explains how to read the results without reducing the project to its limitations or presenting internal tests as universal validation. The engine, implementation recipes, configurations, and raw logs remain private.

## What the central contribution is

The project brings together four reinforcing parts:

1. **A descriptive framework** — states, relations, and dynamics make it possible to ask comparable questions across different domains without assigning them the same laws or units.
2. **A shared-world runtime** — specialized mechanisms can read or transform shared state in an ordered execution.
3. **An experimental loop** — event provenance, checkpoints, resumption, branch comparisons, and ablations make selected connections examinable in defined scenarios.
4. **A broad portfolio** — physics, matter, water, chemistry, bodies, perception, memory, action, collective relations, and tools for creating and observing worlds are covered at different maturity levels.

The intended distinction lies in their combination: compose heterogeneous domains in one world, follow the transfers the system records, then intervene on a branch to see whether a later consequence changes. This program is broader than one test or a long-duration run. This note clarifies the current scope of its main elements.

## How to interpret the five open questions

| Question | What is available | What the results support | Next priority |
|---|---|---|---|
| **Time and synchronization** | An ordered loop and a static inventory of 44 phases and 71 components: 49 classified by reference step, 17 by elapsed time, and 5 mixed. | Calls and their timing regimes are catalogued. This does not mean that the cadences and units of every domain are already harmonized. | Complete temporal contracts at domain boundaries and compare trajectories under different time partitions, starting with mechanisms sensitive to `dt` and thresholds. |
| **Causal attribution** | Event provenance, checkpoints, deterministic replay in qualified cases, branch comparisons, and ablations across several campaigns. | A recorded link helps trace declared provenance. A controlled comparison can show a mechanism’s local contribution under tested conditions; the journal alone does not establish complete causation. | Extend paired interventions to cross-domain connections and retain observables, controls, and limits with each result. |
| **Endurance** | A 47.99-hour resource record with 2,873 measurements and 416 net ticks, alongside a separate set of six aggregate world snapshots. | The process remained present at the samples, but no new tick was recorded during the final nine minutes. The window ends about 50 seconds short of 48 hours; the snapshots do not describe the residents’ full trajectory. | Measure process duration, tick advancement, and world state separately, with timestamps that align them. This is a hardware endurance indicator, not the main integrated result. [Detailed record and graph](https://github.com/Gaaboy/moteur-mondes-causaux/tree/main/evidence/run-record-01). |
| **Reproducibility** | Thousands of targeted checks and many campaigns; some resumption and replay checks are deterministic under explicit conditions. Overlapping batches remain distinct. | There is a substantial base of internal checks. Counts are not an additive total, and they do not amount to independent replication or third-party validation. | Keep protocols, comparators, versions, and criteria attached to each campaign; extend independent repetitions where a result depends on them. |
| **Generalization** | Coupled mechanisms and observed results across a range of domains and scenarios, including retained failures and mixed outcomes. | Results describe the conditions actually tested; they do not promise that an arbitrary model can be integrated or that an effect transfers to every world. | Broaden scenarios and transfer conditions progressively, without confusing architectural extensibility with automatic universal compatibility. |

The endurance measurement can be inspected in context with its filtered series and detailed record in the separate French repository: [public report and graph](https://github.com/Gaaboy/moteur-mondes-causaux/tree/main/evidence/run-record-01), [monitor data](https://github.com/Gaaboy/moteur-mondes-causaux/blob/main/evidence/run-record-01/resource-monitor-public.csv), [world snapshots](https://github.com/Gaaboy/moteur-mondes-causaux/blob/main/evidence/run-record-01/observed-world-output-public.csv).

![Filtered memory and tick-advancement series from the 47.99-hour record.](https://raw.githubusercontent.com/Gaaboy/moteur-mondes-causaux/main/evidence/run-record-01/run-metrics.svg)

## Work order

The priorities are not equivalent. The first two most directly strengthen the central technical proposition:

1. **Temporal contracts for connections** — specify and qualify what a mechanism reads and writes, at which cadence, in what units, and with what subdivision effects.
2. **Causal evidence through intervention** — connect provenance, control, intervention, and measured consequence in representative integrated scenarios.
3. **Progress during long runs** — distinguish an active process, an advancing world, and entity trajectories; align logs before describing world endurance.
4. **Repetitions and reproducibility** — strengthen paired comparisons and resumptions under conditions relevant to each result.
5. **Transfer and generalization** — broaden domains and worlds as temporal and causal contracts become better established.

The 47.99-hour measurement is worth retaining because it informs process stability and memory use. It should neither be hidden nor take the place of composition results, domain campaigns, and intervention comparisons. Likewise, the lack of external validation bounds current claims; it does not erase internal tests, resumption tools, or observed capabilities.

## Recommended public wording

The dossier describes an experimental multi-domain runtime and an observation-and-intervention loop exercised in defined scenarios. Its internal results cover integrated campaigns, domain calibrations, targeted checks, and long trajectories, with favorable, mixed, and negative outcomes. Temporal contracts are not yet harmonized everywhere; causal attribution must be supported by interventions specific to each question; the 47.99-hour endurance record does not establish 48 hours of continuous progress; and the results do not amount to independent validation or generalization to every model.

This wording shows the breadth of the work while keeping each claim within its observations. No proprietary implementation detail is needed to make that distinction.

