# Addendum A: Apple Options

**Continues from:** [Private AI for Research Papers: Laptop Recommendation](local-ai-recommendation-v3.md) · **Date:** October 2026 · **Budget ceiling:** €5,000 including VAT

> ## TL;DR
> - **Moving to Apple is realistic.** A Mac does the same job as the recommended HP laptop, with faster memory and more mature local-AI software. In exchange you get less memory per euro and a change of system.
> - **Best value:** **Mac mini M5 Pro, 64GB (~€3,450).** It can be used as a new main computer, or left on the desk as an AI box used from the existing Windows laptop.
> - **Best laptop:** **MacBook Pro 14" M5 Pro, 64GB (~€4,450).**
> - **Best desktop:** **Mac Studio M5 Max, 64GB (~€4,200).** It is the fastest option in budget.
> - **128GB on Apple is over budget when new** (~€6,100 and up). Refurbished M4 Max 128GB machines occasionally come close.
> - **Older hardware is not much cheaper in 2026.** The memory shortage has pushed high-memory refurbished Macs to around, and sometimes above, their original prices.
> - **Test first:** an existing M3 Max with 64GB is a close stand-in for the 64GB options, so the acceptance test (main document, [section 10](local-ai-recommendation-v3.md#10-acceptance-test)) can be run before anything is bought.

---

## Contents

- [A1. Why consider Apple](#a1-why-consider-apple)
- [A2. How Apple prices work in 2026](#a2-how-apple-prices-work-in-2026)
- [A3. Options by budget](#a3-options-by-budget)
- [A4. Mac mini](#a4-mac-mini)
- [A5. Mac Studio](#a5-mac-studio)
- [A6. MacBook Pro](#a6-macbook-pro)
- [A7. Refurbished and older Macs](#a7-refurbished-and-older-macs)
- [A8. What each memory size can run](#a8-what-each-memory-size-can-run)
- [A9. Moving from Windows to Mac](#a9-moving-from-windows-to-mac)
- [A10. Mac mini as an AI box for a Windows laptop](#a10-mac-mini-as-an-ai-box-for-a-windows-laptop)
- [A11. Test before buying](#a11-test-before-buying)
- [A12. Recommendation](#a12-recommendation)
- [A13. Sources](#a13-sources)

---

## A1. Why consider Apple

> **TL;DR:** Macs read memory faster than the AMD laptops, and their local-AI software is the most mature. The price is less memory for the money, plus learning macOS.

| | HP ZBook Ultra G1a (main document) | Apple M5 Pro / M5 Max |
|---|---|---|
| Memory speed (bandwidth) | 256–273GB/s | **307GB/s (M5 Pro) · 460–614GB/s (M5 Max)** |
| Memory in budget | **Up to 128GB** | Up to 64GB new |
| Share of memory usable by AI | ~75% under Windows (up to 96GB of 128GB) | ~75% by default under macOS (adjustable) |
| Reading long documents | Slower | Faster: M5 chips add AI accelerators to every GPU core |
| Local-AI software | Good, but new models are sometimes slow to arrive | **Most mature:** Apple's MLX framework, LM Studio, Ollama |
| Noise and heat | Fans under load | Mac mini and Mac Studio are near-silent |
| System | Windows (familiar) | macOS (new to learn) |

**In short:** Apple buys **speed and polish**, while the AMD laptops buy **capacity**. For summarising papers with the mid-size, figure-reading models, 64GB is enough, so Apple's trade-off works well here.

---

## A2. How Apple prices work in 2026

> **TL;DR:** Irish prices run about 22% above US prices. Apple raised prices in June 2026. Memory upgrades are expensive. Education pricing helps a little.

- **Irish versus US:** the Mac Studio M5 Max starts at **€3,049** in Ireland versus **$2,499** in the US, roughly **×1.22**. That ratio is used below where only US upgrade prices are known.
- **June 2026 price rise:** Apple raised Mac prices mid-year because of the global memory shortage. For example, the Mac mini's starting price rose by $200.
- **Memory is the expensive part:** the 64GB option on the Mac mini M5 Pro is reported at about **$1,000** on its own.
- **Education pricing:** Apple's [Education Store (Ireland)](https://www.apple.com/ie-edu/store) is open to university staff, with typically modest discounts on Macs. Check the price for the exact configuration.

**Price confidence:** base prices are taken from Apple Ireland's store (high confidence). Prices with upgrades are estimates from US upgrade costs × 1.22 (moderate confidence). **Confirm in Apple's configurator before purchase.**

---

## A3. Options by budget

> **TL;DR:** About €3,000 buys a 48GB Mac mini. About €3,500 buys a 64GB Mac mini (best value). €4,000–5,000 buys a 64GB Mac Studio or a 64GB MacBook Pro. New 128GB Macs exceed €5,000.

| Budget (incl. VAT) | Machine | Memory | Bandwidth | Est. Irish price | Type |
|---|---|---|---|---|---|
| **~€2,250** | Mac mini M5 Pro (18-core CPU / 20-core GPU) | 24GB | 307GB/s | €2,249 (base) | Desktop |
| **~€3,000** | Mac mini M5 Pro | 48GB | 307GB/s | ~€2,950–3,000 | Desktop |
| **~€3,500** | ⭐ **Mac mini M5 Pro** | **64GB** | 307GB/s | **~€3,450** | Desktop |
| **~€3,700** | Mac Studio M5 Max (40-core GPU) | 48GB | 614GB/s | €3,709 (base) | Desktop |
| **~€4,200** | ⭐ **Mac Studio M5 Max (40-core GPU)** | **64GB** | **614GB/s** | **~€4,200** | Desktop |
| **~€4,450** | ⭐ **MacBook Pro 14" M5 Pro** | **64GB** | 307GB/s | **~€4,450** | Laptop |
| **~€4,900–5,100** | MacBook Pro 14" M5 Max (40-core GPU) | 48GB | 614GB/s | ~€4,900–5,100 | Laptop |
| **€5,000 (if found)** | Refurbished MacBook Pro or Mac Studio, M4 Max | 128GB | 546GB/s | ~€4,800–5,600 | Either |
| ❌ Over budget | Mac Studio M5 Max | 128GB | 614GB/s | ~€6,100 | Desktop |
| ❌ Over budget | MacBook Pro M5 Max | 128GB | 614GB/s | ~€7,000+ | Laptop |
| ❌ Over budget | Mac Studio M5 Ultra | 96GB+ | 1.2TB/s | from €6,699 | Desktop |

Note that a Mac mini or Mac Studio also needs a **monitor, keyboard and mouse** (roughly €300–600) unless existing ones are reused.

---

## A4. Mac mini

<img src="https://www.apple.com/v/mac-mini/ab/images/meta/mac-mini__dvce2jrm11w2_og.jpg" alt="Mac mini" width="480">

> **TL;DR:** The lowest-cost way onto Apple. Choose the **M5 Pro with 64GB**. The cheaper M6 model tops out at 32GB, which is too little for this job.

- **Released:** August 2026, in two versions:
  - **M6:** up to 32GB of memory and 170GB/s. ❌ Too small for the figure-reading models with room for long documents.
  - **M5 Pro:** up to **64GB** of memory and **307GB/s**. ✅ The one to buy.
- **Irish base prices:** €1,079 (M6) · €2,029 (M5 Pro 15-core) · €2,249 (M5 Pro 18-core/20-core GPU)
- **Recommended configuration:** M5 Pro, 18-core CPU, 20-core GPU, **64GB**, 1TB, **~€3,450** (estimate)
- **Two ways to use it:**
  1. As a **new main computer** (a full move to Mac; see [A9](#a9-moving-from-windows-to-mac)).
  2. As a **silent AI box** on the desk, used from the existing Windows laptop (see [A10](#a10-mac-mini-as-an-ai-box-for-a-windows-laptop)).
- **Links:** [Apple Ireland: Mac mini](https://www.apple.com/ie/mac-mini/) · [tech specs](https://www.apple.com/ie/mac-mini/specs/) · [buy](https://www.apple.com/ie/shop/buy-mac/mac-mini)

---

## A5. Mac Studio

<img src="https://www.apple.com/v/mac-studio/n/images/meta/mac-studio_overview__eedzbosm1t26_og.png" alt="Mac Studio" width="480">

> **TL;DR:** About twice the memory speed of the Mac mini, so answers appear noticeably faster. **The 64GB M5 Max (~€4,200) is the fastest machine in budget.** The 128GB version (~€6,100) is over.

- **Released:** August 2026, with M5 Max (up to 128GB, up to 614GB/s) or M5 Ultra (96–512GB, 1.2TB/s).
- **Irish base prices:** €3,049 (M5 Max, 32-core GPU, 36GB) · €3,709 (M5 Max, 40-core GPU, 48GB) · €6,699 (M5 Ultra)
- **Recommended configuration:** M5 Max, **40-core GPU** (this gives the full 614GB/s), **64GB**, **~€4,200** (estimate)
- **Why not 128GB?** About €6,100. It would add the largest text model (gpt-oss-120b), which is useful but not essential for summarising papers.
- **Links:** [Apple Ireland: Mac Studio](https://www.apple.com/ie/mac-studio/) · [tech specs](https://www.apple.com/ie/mac-studio/specs/) · [buy](https://www.apple.com/ie/shop/buy-mac/mac-studio)

---

## A6. MacBook Pro

<img src="https://www.apple.com/v/macbook-pro/ax/images/meta/macbook-pro__difvbgz1plsi_og.png" alt="MacBook Pro" width="480">

> **TL;DR:** For a portable Mac, the **M5 Pro with 64GB (~€4,450)** is the sensible buy. The M5 Max is faster but only 48GB fits the budget.

| Configuration | Memory | Bandwidth | Est. price | Verdict |
|---|---|---|---|---|
| 14" M5 Pro (18-core / 20-core GPU) | **64GB** | 307GB/s | ~€4,450 | ⭐ **Best balance** |
| 14" M5 Max (40-core GPU) | 48GB | 614GB/s | ~€4,900–5,100 | Faster, but less memory |
| 14" or 16" M5 Max | 128GB | 614GB/s | ~€7,000+ | ❌ Over budget |

- The M5 Pro MacBook Pro has the **same memory speed as the M5 Pro Mac mini**, but costs about €1,000 more for portability, a screen and a battery.
- **Links:** [Apple Ireland: MacBook Pro](https://www.apple.com/ie/macbook-pro/) · [tech specs](https://www.apple.com/ie/macbook-pro/specs/) · [buy](https://www.apple.com/ie/shop/buy-mac/macbook-pro)

---

## A7. Refurbished and older Macs

> **TL;DR:** Refurbished is the **only** route to a 128GB Mac within budget, but high-memory refurbished stock is scarce and no longer cheap. Buy only with a warranty.

### What has changed

High-memory Macs have held, and sometimes gained, value because of the 2026 memory shortage:

- A refurbished **Mac Studio M4 Max, 128GB / 1TB** was tracked at **$4,579** in July 2026, **above** its **$3,699** launch price.
- Resale analysis in May 2026 found 128GB MacBook Pro M3/M4 Max upgrades retaining about **60–85%** of their original cost, well above the usual rate.

### Older machines worth looking for

| Machine | Year | Memory | Bandwidth | Example refurbished price (US) | Notes |
|---|---|---|---|---|---|
| MacBook Pro 14" M4 Max (40-core GPU) | 2024 | 128GB | 546GB/s | ~$3,999 (Back Market, "Good") | ⭐ Best refurbished find, if available in Ireland/EU |
| MacBook Pro 14" M3 Max (40-core GPU) | 2023 | 128GB | 400GB/s | ~$4,130–4,600 | Same chip family as an existing M3 Max |
| Mac Studio M4 Max (40-core GPU) | 2025 | 128GB | 546GB/s | ~$4,579 | Desktop route to 128GB |
| Mac Studio M3 Ultra | 2025 | 96GB | 819GB/s | ~$4,499–5,649 | Very fast, but usually over budget |
| Mac Studio M1/M2 Ultra | 2022–23 | 64–128GB | 800GB/s | Varies | Fast answers but slow on long documents; older, shorter future software support |

US prices × ~1.2 gives a rough Irish/EU equivalent (low–moderate confidence).

### Where to look

- [Apple Certified Refurbished (Ireland)](https://www.apple.com/ie/shop/refurbished/mac): one-year Apple warranty, the same as new. Stock changes daily.
- [Back Market Ireland](https://www.backmarket.ie/): one-year seller warranty; condition grades vary.
- University procurement may restrict refurbished purchases, so check first.

**Rule of thumb:** a refurbished 128GB M4 Max at **€5,000 or less** is a strong buy. Above that, the new 64GB options give better value.

---

## A8. What each memory size can run

> **TL;DR:** 48GB runs the figure-reading models. 64GB runs them comfortably with long documents. Only 96–128GB adds the largest text model.

The AI can use about **75%** of a Mac's memory by default (adjustable by the technical colleague).

| Mac memory | Usable by AI (approx.) | [Gemma 4](https://ai.google.dev/gemma/docs/core/model_card_4) 26B/31B (reads figures, ~20GB) | [Qwen3.5-35B-A3B](https://huggingface.co/Qwen/Qwen3.5-35B-A3B) (reads figures, ~24GB) | [gpt-oss-120b](https://openai.com/index/introducing-gpt-oss/) (text only, ~63GB) |
|---|---|---|---|---|
| 24GB | ~18GB | ❌ | ❌ | ❌ |
| 36GB | ~27GB | ⚠️ Tight | ⚠️ Tight | ❌ |
| 48GB | ~36GB | ✅ | ✅ | ❌ |
| **64GB** | **~48GB** | ✅ **Comfortable** | ✅ **Comfortable** | ❌ |
| 96GB | ~72GB | ✅ | ✅ | ✅ |
| 128GB | ~96GB | ✅ | ✅ | ✅ |

**Speed (approximate):** at the same memory size, an M5 Max produces answers about twice as fast as an M5 Pro, and roughly 2–2.4× as fast as the AMD laptops in the main document. This estimate is based on memory bandwidth, not on benchmarks.

---

## A9. Moving from Windows to Mac

> **TL;DR:** Very doable for typical academic work. The main checks are university IT support for Macs and any Windows-only software.

| Area | Status on Mac |
|---|---|
| Microsoft 365 (Word, Excel, PowerPoint, Outlook, Teams) | ✅ Native Mac versions |
| Reference managers (Zotero, EndNote, Mendeley) | ✅ Available |
| Statistics and science tools (R, Python, MATLAB, SPSS) | ✅ Generally available; check specific licences |
| Windows-only software | ⚠️ Keep the existing Windows laptop, or run Windows in [Parallels Desktop](https://www.parallels.com/products/desktop/) (paid) |
| University IT support | ⚠️ **Check** that IT supports and manages Macs (device management, encryption, VPN) |
| Learning curve | Modest; the main differences are the menu bar, Finder and keyboard shortcuts |

**Lowest-risk transition:** buy a **Mac mini** and keep the Windows laptop. The Mac starts as the AI box ([A10](#a10-mac-mini-as-an-ai-box-for-a-windows-laptop)) and can become the main computer gradually, or never.

---

## A10. Mac mini as an AI box for a Windows laptop

> **TL;DR:** The Mac mini can sit on the desk running the AI, while the existing Windows laptop is used through a web browser. It is simpler than the Linux boxes in the main document's footnote, because macOS needs little looking after.

How it works:

1. The technical colleague installs [LM Studio](https://lmstudio.ai/) or [Ollama](https://ollama.com/) on the Mac mini and loads the tested models.
2. A browser-based chat interface (for example [Open WebUI](https://github.com/open-webui/open-webui)) runs on the Mac mini.
3. The Windows laptop opens a bookmarked page on the local network. Documents are processed on the Mac mini and never leave the office network.

Compared with the main document's options:

| | HP laptop (main recommendation) | Mac mini as AI box |
|---|---|---|
| Cost (64GB) | Quote needed | ~€3,450 |
| Change for the user | New laptop | **None**; same laptop, a browser bookmark |
| Portability | ✅ Anywhere | ❌ Office only, unless IT-approved remote access |
| Maintenance | Windows laptop | macOS box; low effort |
| Security setup | Standard laptop controls | Network access must be restricted; IT sign-off needed |

---

## A11. Test before buying

> **TL;DR:** An M3 Max MacBook Pro with 64GB (400GB/s) closely approximates the 64GB options, so run the acceptance test on it first and decide with evidence.

The M3 Max is John's work laptop, so he can be the test subject.

| Test machine | Comparable to | Difference |
|---|---|---|
| M3 Max, 64GB, 400GB/s | Mac mini M5 Pro 64GB (307GB/s) | The M3 Max answers somewhat faster; the M5 Pro reads long documents faster |
| M3 Max, 64GB, 400GB/s | Mac Studio M5 Max 64GB (614GB/s) | The M5 Max is faster on both |

Steps:

1. Install LM Studio and the candidate models (Gemma 4, Qwen3.5-35B-A3B) on the M3 Max.
2. Run the eight test papers from the main document's [acceptance test](local-ai-recommendation-v3.md#10-acceptance-test).
3. If quality and speed are acceptable, **any 64GB Apple option will perform at least comparably**. Choose on form factor and price.
4. If quality falls short, the issue is the **models**, not the hardware. More memory or a cloud service is the answer, not a faster Mac.

For context, a 64GB M3 Max cost roughly €5,000 three years ago, and similar money buys a similar memory size today. Apple's prices have not fallen, but the M5 generation is faster at the same memory size.

---

## A12. Recommendation

> **TL;DR:** If a move to Apple is acceptable, buy the **Mac mini M5 Pro 64GB** (best value, lowest-risk transition). Choose the **Mac Studio M5 Max 64GB** for more speed, or the **MacBook Pro M5 Pro 64GB** if a laptop is essential.

| Priority | Choice | Est. price |
|---|---|---|
| **Best value / easiest transition** | ⭐ Mac mini M5 Pro, 64GB, 1TB | ~€3,450 |
| **Fastest in budget** | Mac Studio M5 Max (40-core GPU), 64GB | ~€4,200 |
| **Must be a laptop** | MacBook Pro 14" M5 Pro, 64GB | ~€4,450 |
| **Must have 128GB** | Refurbished M4 Max 128GB at ≤ €5,000, if found | ~€4,800–5,600 |
| **Avoid for this job** | Mac mini M6 (32GB maximum); any Mac with 24–36GB | — |

### Apple versus the main recommendation

| If the priority is… | Choose |
|---|---|
| Staying on Windows, with maximum memory per euro | HP ZBook Ultra G1a (main document) |
| Speed, quiet operation and mature AI software | Apple (this addendum) |
| No change at all for the user | Mac mini as an AI box (A10) or the AMD box (main document's footnote) |

### Next steps

1. **Run the acceptance test on the existing M3 Max** ([A11](#a11-test-before-buying)).
2. **Confirm that university IT supports Macs.**
3. **Price the exact configuration** in Apple's Irish and Education stores.
4. **Check Apple Certified Refurbished** for 128GB M4 Max stock at or below €5,000.

---

## A13. Sources

> **TL;DR:** Apple's Irish store and specifications, Apple's newsroom, US launch coverage, and refurbished-price trackers.

**Apple (official)**

- Apple Newsroom, [The new Mac mini and Mac Studio are available today](https://www.apple.com/newsroom/2026/09/the-new-mac-mini-and-mac-studio-are-available-today/) (September 2026)
- Apple Ireland: [Mac mini](https://www.apple.com/ie/mac-mini/) · [Mac Studio](https://www.apple.com/ie/mac-studio/) · [MacBook Pro](https://www.apple.com/ie/macbook-pro/) · [Refurbished Mac](https://www.apple.com/ie/shop/refurbished/mac) · [Education Store](https://www.apple.com/ie-edu/store)

**Specifications and pricing coverage**

- MacRumors, [Mac mini roundup](https://www.macrumors.com/roundup/mac-mini/) and [Mac Studio buyer's guide: M5 Max vs M5 Ultra](https://www.macrumors.com/guide/m5-max-vs-m5-ultra/)
- Macworld, [Mac Studio (M5 Max) review](https://www.macworld.com/article/3238319/mac-studio-m5-max-review.html)
- Technology.org, [Mac mini M6 vs M5 Pro pricing](https://www.technology.org/2026/08/27/mac-mini-m5-pro-vs-m6-price/)
- Wikipedia, [Apple M5](https://en.wikipedia.org/wiki/Apple_M5) and [Apple M4](https://en.wikipedia.org/wiki/Apple_M4) (chip memory and bandwidth summary)

**Refurbished and resale**

- refurb.me, [Mac Studio (Early 2025) refurbished price history](https://www.refurb.me/stats/mac-studio/mac-studio-early-2025) and [refurbished MacBook Pro M4 Max](https://www.refurb.me/refurbished/macbook/macbook-pro/m4-max)
- Macfax, [MacBook Pro resale value in 2026](https://macfax.com/blog/how-much-is-a-used-macbook-pro-worth-in-2026)
- Back Market, [Ireland](https://www.backmarket.ie/)

---

*Product images are hotlinked from Apple's website and remain Apple's property. Prices marked "est." are derived from US upgrade prices and should be confirmed in Apple's configurator.*
