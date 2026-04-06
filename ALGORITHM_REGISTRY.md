# Algorithm Registry — Domain Mining Protocols

Every domain is an algorithm. Every deed is a block. Every sale is a block reward.

## The Model

In crypto mining, GPUs compute hashes to find blocks. Miners get rewarded when blocks are found and sold (via exchange). The algorithm determines the workload profile.

In AI mining, GPUs score pairs through the tribunal to file deeds. Miners get rewarded when deeds are sold (via shop). The domain determines the workload profile.

The deed is a **Real World Asset (RWA)**. It has provenance (origin), quality (dual-judge scores), process (Merkle + Hedera), economics (energy cost), and trust (blockchain anchor). When a customer buys a Proof of Location package, they're buying deeds. The revenue flows back to the miners who produced them.

---

## Algorithms

### MedHash — Medical Domain Mining

```
MedHash
  Target:     Medical training pairs (clinical, pharma, diagnostic)
  Difficulty:  HIGH — long clinical text, complex reasoning
  GPU Profile: Memory-heavy (large KV cache, dense tokens)
  Clock:       Core 1,200 MHz | Mem MAX | Power 200-250W
  Hashrate:    ~300 pairs/hr per judge pair
  Block:       1 deed = 1 dual-judge scored medical pair
  Block Reward: Proportional share of medical location sales ($29-$199)
  RWA Value:   Medical RJ deed = relocates model to clinical specialist
  Inventory:   417,136 pairs available | 5,038 deeds filed | 4,295 RJ
```

### CREHash — Commercial Real Estate Mining

```
CREHash
  Target:     CRE underwriting, IC memos, lease abstracting, debt analysis
  Difficulty:  MEDIUM — structured numeric content, moderate length
  GPU Profile: Balanced (compute for math, memory for templates)
  Clock:       Core 1,500 MHz | Mem MAX | Power 250-300W
  Hashrate:    ~500 pairs/hr per judge pair
  Block:       1 deed = 1 dual-judge scored CRE pair
  Block Reward: Proportional share of CRE location sales
  RWA Value:   CRE RJ deed = relocates model to deal analyst
  Inventory:   810,097 pairs available | 833 deeds filed (just started)
```

### GrantHash — Grants & Business Formation Mining

```
GrantHash
  Target:     Federal grants, 501(c)(3), SBIR/STTR, SBA, business formation
  Difficulty:  MEDIUM — long-form, regulatory, formulaic
  GPU Profile: Memory-heavy (long grant narratives)
  Clock:       Core 1,200 MHz | Mem MAX | Power 200-250W
  Hashrate:    ~380-777 pairs/hr per judge pair
  Block:       1 deed = 1 dual-judge scored grants pair
  Block Reward: Proportional share of Master Writer sales ($29-$199)
  RWA Value:   Grants RJ deed = relocates model to grant specialist
  Inventory:   35,271 pairs available | 12,336 deeds filed | ~95% RJ
```

### LegalHash — Legal & Compliance Mining

```
LegalHash
  Target:     Credit repair, consumer protection, regulatory compliance
  Difficulty:  HIGH — dense regulatory text, citation-heavy
  GPU Profile: Memory-heavy (long legal text)
  Clock:       Core 1,200 MHz | Mem MAX | Power 200-250W
  Hashrate:    ~380 pairs/hr per judge pair
  Block:       1 deed = 1 dual-judge scored legal pair
  Block Reward: Proportional share of legal location sales
  RWA Value:   Legal RJ deed = relocates model to compliance expert
  Inventory:   5,001 pairs available | 5,009 deeds filed (complete)
```

### AvionHash — Aviation Mining

```
AvionHash
  Target:     Flight safety, maintenance, FAA compliance, NTSB analysis
  Difficulty:  MEDIUM — technical, standards-heavy, moderate length
  GPU Profile: Balanced
  Clock:       Core 1,500 MHz | Mem 13,365 MHz | Power 250W
  Hashrate:    ~500 pairs/hr per judge pair
  Block:       1 deed = 1 dual-judge scored aviation pair
  Block Reward: Proportional share of aviation location sales
  RWA Value:   Aviation RJ deed = relocates model to safety analyst
  Inventory:   41,477 pairs available | 0 deeds filed (in queue)
```

### WikiHash — Doctrine & Strategy Mining

```
WikiHash
  Target:     Company doctrine, architecture, strategy, competitive intel
  Difficulty:  LOW — shorter, conceptual, strategic
  GPU Profile: Compute-forward (reasoning-heavy, shorter sequences)
  Clock:       Core 1,800 MHz | Mem auto | Power 250W
  Hashrate:    ~800 pairs/hr per judge pair
  Block:       1 deed = 1 dual-judge scored strategy pair
  Block Reward: Internal value — trains the Board Member model
  RWA Value:   Strategy RJ deed = relocates model to company advisor
  Inventory:   500 pairs generating (Board Member cook)
```

---

## Mining Economics

### Block Reward Model

```
Customer buys "Medical Starter" package ($29)
  → Contains 1,000 RJ medical deeds
  → Each deed was mined by GPU compute (scored by tribunal)
  → Revenue: $29
  → COGS: energy cost of 1,000 deeds = $0.078 (at $0.000078/deed)
  → Gross margin: 99.7%
  → Miner reward pool: $29 × miner_share% = distributed to GPUs

Pool Distribution:
  Judge A GPU:  40% (primary scorer)
  Judge B GPU:  30% (secondary scorer, cross-validation)
  Deed Recorder: 10% (filing + Merkle)
  Infrastructure: 20% (NAS, networking, Hedera anchoring)
```

### Hashrate by Algorithm

| Algorithm | Pairs/hr | Wh/deed | Cost/deed | Deeds/kWh |
|-----------|----------|---------|-----------|-----------|
| MedHash | 300 | 1.10 | $0.00011 | 909 |
| CREHash | 500 | 0.78 | $0.000078 | 1,282 |
| GrantHash | 777 | 0.50 | $0.000050 | 2,000 |
| LegalHash | 380 | 0.90 | $0.000090 | 1,111 |
| AvionHash | 500 | 0.78 | $0.000078 | 1,282 |
| WikiHash | 800 | 0.45 | $0.000045 | 2,222 |

### Revenue Per Algorithm

| Algorithm | Package Price | Deeds/Package | Revenue/Deed | Energy Cost | Margin |
|-----------|-------------|---------------|-------------|-------------|--------|
| MedHash | $29-$199 | 1,000-10,000 | $0.029-$0.020 | $0.00011 | 99.6% |
| CREHash | $29-$199 | 1,000-10,000 | $0.029-$0.020 | $0.000078 | 99.7% |
| GrantHash | $29-$199 | 1,000-10,000 | $0.029-$0.020 | $0.000050 | 99.8% |

---

## The RWA Thesis

A Royal Jelly deed is a **Real World Asset**:

1. **It has provenance** — origin tracked, source identified, fingerprint hashed
2. **It has quality** — dual-judge scored, 5 dimensions, per-dimension reasoning
3. **It has process** — Merkle tree sealed, batch verified, Hedera anchored
4. **It has economics** — energy cost measured, cost-to-mint calculated
5. **It has trust** — immutable timestamp, verifiable by anyone, ENS permanent URL
6. **It has utility** — relocates models from generic to specialist (measurable delta)
7. **It has market value** — sold on swarmandbee.ai/shop ($29-$199 per package)

When a customer buys a package, they're buying **title to a location**. The deeds prove the location exists. The Proof of Location proves the relocation worked. The blockchain proves it's real.

The miners who produced those deeds created the asset. The revenue flows back to the compute that created it. **Same as mining: GPUs create value, value gets sold, miners get paid.**

---

## Pool Architecture (Future)

```
SWARM MINING POOL
  ├── Algorithm selection: MedHash / CREHash / GrantHash / ...
  ├── Flight sheet: clock profile per algorithm
  ├── Hashrate: pairs scored per hour
  ├── Shares: deeds filed (proportional credit)
  ├── Block: Merkle batch sealed (50 deeds)
  ├── Block reward: revenue from deed sales
  ├── Payout: proportional to shares
  └── Dashboard: swarmandbee.ai/chain (live)
```

A miner with 10x RTX 3090s joins the pool:
- Selects MedHash (medical domain)
- Applies flight sheet (Core 1,200 | Mem MAX | PL 150W)
- Each card runs a judge instance (5 judge pairs)
- Scores 1,500 medical pairs/hr
- Files ~1,200 RJ deeds/hr (80% yield)
- Earns proportional share of medical package sales
- Revenue: ~$0.029 × 1,200 = $34.80/hr in deed value created
- Energy cost: 1,500W × $0.10/kWh = $0.15/hr
- **Net: $34.65/hr mining medical deeds**

Compare to ETH mining at its peak: ~$1-3/hr per 3090.
**Medical deed mining: $3.48/hr per 3090.** Better than ETH at its peak.

---

*The deed proves where it came from. The title insures the quality. The Proof of Location proves the outcome. The miner gets paid.*

*Validate the Validator. Mine the Location.*
