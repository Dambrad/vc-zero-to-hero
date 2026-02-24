# Module 02: Startup Valuations
## What Is Your Company Actually Worth?

---

**← [Module 01](./module-01-vc-ecosystem.md)** | **[Back to Syllabus](./README.md)** | **[Next Module →](./module-03-funding-stages.md)**

---

## 🎯 What You'll Learn

- The difference between pre-money and post-money valuation
- How startups are valued at different stages (with no revenue, early revenue, and scale)
- The four main valuation methods used in venture capital
- Why valuations are often more art than science — and what drives them
- How to sanity-check a valuation number

---

## ⏱️ Estimated Time

| Section | Time |
|---------|------|
| Core Concepts | 60–75 min |
| Case Study | 20–30 min |
| Lab Exercise | 45–60 min |
| Resources | Self-paced |
| **Total** | **~3–4 hours** |

---

## 📖 Core Concepts

### 2.1 — The Hardest Question in Venture: "What's It Worth?"

Valuing a startup is genuinely hard. Unlike public companies — which have years of financial statements, stock price history, and analyst coverage — startups often have:

- Little to no revenue
- No profitability (sometimes for years)
- Highly uncertain futures
- Products that don't exist yet

And yet, billions of dollars are invested at these valuations every year. How?

The answer: **valuation is a negotiation anchored by narrative, data, and comparable market transactions.** It's part science, part art, part storytelling.

> 💡 **Key Mindset Shift:** A startup valuation is not a precise calculation. It is an agreed-upon fiction that reflects what a willing buyer (investor) and willing seller (founder) can agree on today, given their best guesses about the future.

---

### 2.2 — Pre-Money vs. Post-Money Valuation

These are the two most important terms in any early-stage deal. Confuse them, and you'll miscalculate how much of your company you're selling.

**Pre-Money Valuation:** What the company is worth *before* new investment comes in.

**Post-Money Valuation:** What the company is worth *after* the investment.

**The formula:**
```
Post-Money = Pre-Money + New Investment
```

**Example:**
- Pre-money valuation: $8,000,000
- VC invests: $2,000,000
- Post-money valuation: $10,000,000
- VC's ownership: $2M ÷ $10M = **20%**

> ⚠️ **Watch Out:** When a VC says "we'll value you at $10M," always clarify — is that pre-money or post-money? The difference is everything.

**Side-by-side comparison:**

| Scenario | Pre-Money | Investment | Post-Money | Investor Owns |
|----------|-----------|-----------|------------|---------------|
| A | $8M | $2M | $10M | 20% |
| B | $10M | $2M | $12M | 16.7% |

Same $2M investment, but in Scenario B the founder gives away less. The pre-money number is what you negotiate.

---

### 2.3 — How Valuations Work at Different Stages

Startup valuations follow the lifecycle of the company. Here's a general (not universal) map:

| Stage | Typical Valuation | What Drives It |
|-------|------------------|----------------|
| **Idea / Pre-revenue** | $500K – $3M | Founder credibility, concept, market |
| **Pre-seed** | $1M – $5M | MVP, early users, founder track record |
| **Seed** | $5M – $15M | Revenue signal, product-market fit hints |
| **Series A** | $15M – $60M | Proven growth, unit economics, team |
| **Series B** | $50M – $200M | Scale, strong metrics, category leader |
| **Series C+** | $200M – $1B+ | Revenue, market leadership, expansion |

> 🚨 **These ranges shift with market conditions.** In 2021's bull market, seed-stage companies were valued at $20M+. In 2023's downturn, those same companies were worth a fraction of that. Macro conditions matter enormously.

---

### 2.4 — The Four Main Valuation Methods

#### Method 1: Comparable Transactions (Comps)
*"What did similar companies get valued at?"*

This is the most common approach at every stage. If three SaaS companies with $2M ARR (annual recurring revenue) recently raised Seed rounds at $15–20M valuations, then a similar SaaS company with $2M ARR is probably worth around $15–20M.

**How it works:**
1. Find recent transactions in your industry (Crunchbase, PitchBook, press releases)
2. Identify companies at a similar stage with similar metrics
3. Extract their valuation multiples (e.g., Price/ARR multiple)
4. Apply those multiples to your company

**Common multiples used:**
- **Revenue Multiple** (ARR): Common in SaaS — e.g., "10x ARR" means a company with $2M ARR might be valued at $20M
- **GMV Multiple**: Common in marketplaces
- **Monthly Active Users (MAU)**: Common in consumer apps

**Limitation:** Comps are only as good as the data you find. Private transaction data is often unavailable.

---

#### Method 2: The VC Method
*"What return does the investor need, and what does that imply today?"*

This is the most VC-specific approach. VCs work backwards from the exit.

**The formula:**
```
Pre-Money Valuation = (Exit Value × VC Ownership at Exit) ÷ Required Return Multiple − Investment
```

**Step-by-step example:**
1. VC believes the company could be worth **$100M in 5 years** (the "terminal value")
2. VC wants a **10x return** on a $2M investment → needs $20M at exit
3. Needed ownership at exit: $20M ÷ $100M = **20%**
4. Accounting for future dilution (assume 20% dilution from future rounds), VC needs **25% now** to have 20% at exit
5. With 25% ownership and a $2M investment: Post-money = $2M ÷ 25% = **$8M post-money**
6. Pre-money = $8M − $2M = **$6M pre-money**

**Key insight:** VCs are always thinking about the exit. Every valuation they offer you today reflects their projection of where you could go.

---

#### Method 3: The Berkus Method
*"Value what you can see, not what you hope for."*

Created by angel investor Dave Berkus, this method is used for **very early-stage companies** with no revenue. It assigns value to five elements:

| Element | Max Value Added |
|---------|----------------|
| Compelling idea / concept | $500K |
| Working prototype | $500K |
| Strong management team | $500K |
| Strategic relationships | $500K |
| Product rollout / early sales | $500K |
| **Maximum Pre-Money Value** | **$2.5M** |

This gives a structured way to value something that is mostly still a vision.

---

#### Method 4: Discounted Cash Flow (DCF)
*"What is the present value of all future cash flows?"*

DCF is the gold standard in traditional finance. You project all future cash flows and discount them back to today using a risk-adjusted rate.

**The challenge with startups:** DCF requires reliable future projections. Startups don't have reliable projections. The math is there, but the inputs are wildly uncertain, making DCF less useful at early stages.

> 🧠 **Reality Check:** Most early-stage VC deals are NOT valued using DCF. DCF becomes more relevant at later stages (Series C+) or in private equity. For startups, comps and the VC method are far more common.

---

### 2.5 — What Actually Drives Valuation in Practice

Beyond the math, here's what actually moves the needle in a real valuation negotiation:

**Things that *increase* your valuation:**
- Multiple investors competing to invest (creates an auction)
- Strong founder pedigree (previous exits, well-known background)
- Exceptional growth metrics (MoM revenue growth > 20%)
- Hot market or sector (AI in 2023–2025, for example)
- Scarcity (VC FOMO — fear of missing out)

**Things that *decrease* your valuation:**
- Single interested investor (no competition)
- Weak or unproven team
- Slow growth or declining metrics
- Unfavorable macro environment (rate hikes, tech downturn)
- Desperation (VCs can smell it)

> 💡 **The most powerful valuation tool available to a founder: competing term sheets.** Nothing raises your valuation faster than another investor making an offer.

---

## 🌍 Real-World Case Study: Airbnb's Valuation Journey

**The Early Days (2008–2009):** When Brian Chesky and Joe Gebbia first pitched Airbnb, they were essentially saying "let strangers sleep in other strangers' homes." Every major VC passed. The concept seemed bizarre and unscalable. The company nearly failed multiple times.

**Seed Round (2009):** Y Combinator accepted them into their batch. Sequoia's Mike Moritz reportedly passed, saying he didn't understand the business. They raised a small seed round from various angels at a valuation of roughly **$2.4M**.

**Series A (2010):** After demonstrating growth — $2M in bookings over the summer — Sequoia (who had passed earlier) came back in. Greylock and others also participated. They raised $7.2M at a **$70M pre-money valuation** — a massive jump driven by proven demand and growth metrics.

**Series B (2011):** $112M raised. Valuation: ~$1.3 billion. Airbnb became one of the first companies to enter "unicorn" status.

**IPO (2020):** Despite the pandemic devastating travel globally, Airbnb went public at a valuation of **$47 billion**. By end of their first day of trading: **$86 billion**.

**What This Teaches Us:**
1. Early valuation is highly tied to narrative — the Seed valuation was based almost entirely on the idea and the team's willingness to hustle (they sold novelty cereal to fund the company)
2. Series A valuation jumped dramatically once real growth data existed
3. Valuations are *not* linear — they don't grow uniformly; they respond to proof points
4. A "no" from a VC today is not permanent — markets, data, and context change

> 🤔 **Reflection Question:** Airbnb went from $2.4M to $47B. What was the moment when the valuation truly reflected the business potential, and not just hope?

---

## 🔬 Lab Exercise: Apply the VC Method

**Objective:** Use the VC Method to calculate a pre-money valuation for a hypothetical startup.

**Time:** 45–60 minutes

**Scenario:**
You are a VC looking at "CleanRoute," a B2B SaaS startup that helps trucking companies optimize routes for fuel efficiency. Here's what you know:

- They're asking for $2M from you
- You believe the company could be worth **$80M in 5 years** if things go well
- Your fund targets a **15x return** on Seed investments
- You expect the founders to raise 2 more rounds before exit, diluting your stake by approximately **30%**

**Your Task:**

**Step 1 — Calculate the required return**
```
Required return = Investment × Target multiple
Required return = $2M × 15x = ?
```

**Step 2 — Calculate required ownership at exit**
```
Required ownership at exit = Required return ÷ Exit value
Required ownership at exit = ? ÷ $80M = ?
```

**Step 3 — Adjust for future dilution**
```
Required ownership NOW = Required ownership at exit ÷ (1 − dilution percentage)
Required ownership NOW = ? ÷ (1 − 0.30) = ?
```

**Step 4 — Calculate post-money valuation**
```
Post-money valuation = Investment ÷ Required ownership NOW
Post-money valuation = $2M ÷ ? = ?
```

**Step 5 — Calculate pre-money valuation**
```
Pre-money valuation = Post-money − Investment
Pre-money valuation = ? − $2M = ?
```

**Bonus Challenge:**
The founder thinks they deserve a $10M pre-money valuation. Given your calculations, how would you respond? What would need to change (exit value, return target, dilution assumption) to justify $10M pre-money?

**Answer Key:**
*(Try it yourself first!)*
- Step 1: $30M required return
- Step 2: 37.5% ownership at exit
- Step 3: 53.6% ownership needed now (37.5% ÷ 0.70)
- Step 4: $3.73M post-money ($2M ÷ 53.6%)
- Step 5: $1.73M pre-money

*Note: This shows why early-stage valuations are so low from the VC's perspective. The math demands it. The founder's negotiation is about changing the exit value assumption.*

---

## 📚 Resource Pack

### 📺 YouTube Videos
1. **"Pre-Money vs Post-Money Valuation Explained"** — 500 Global
   Search: `500 Global pre money post money valuation explained`
   *Clear, concise, and beginner-friendly.*

2. **"How to Value a Startup"** — Slidebean (Founder's Edition)
   Search: `Slidebean how to value a startup`
   *Excellent visual breakdown with real startup examples.*

3. **"VC Math: How Venture Capitalists Make Investment Decisions"** — Stanford eCorner
   Search: `Stanford eCorner VC math investment decisions`
   *Academic but very clear on the return math.*

4. **"Startup Valuation Explained for Founders"** — Andreessen Horowitz (a16z)
   Search: `a16z startup valuation explained founders`

### 📖 Books
- *Venture Deals*, **Chapter 4** — Pre and Post-Money Valuation
- *Secrets of Sand Hill Road*, **Chapters 4–5** — How VCs think about price

### 🌐 Articles
- **"Startup Valuation Methods"** — CB Insights: Search `CB Insights startup valuation methods`
- **"The Berkus Method"** — Dave Berkus's own explanation: `berkus.com`
- **Fred Wilson on Valuation**: Search `Fred Wilson AVC valuation post`
- **Y Combinator's Guide to Startup Valuations**: Search `YC startup valuation guide`

---

## ✅ Module 02 Checklist

- [ ] I can explain pre-money vs. post-money with a numerical example
- [ ] I understand why valuations are different at different funding stages
- [ ] I can walk through the VC Method step by step
- [ ] I know what the Berkus Method is and when it's used
- [ ] I completed the CleanRoute lab exercise and got the right answer (or understood why I didn't)
- [ ] I understand what actually moves a valuation number in a real negotiation

---

## 🔁 Module Summary (TL;DR)

Startup valuations are **negotiated, not calculated**. Pre-money is what you're worth *before* investment; post-money is *after*. The four main methods are Comps, the VC Method, the Berkus Method, and DCF — but in practice, comps and the VC method dominate. Valuations rise with growth, team credibility, and investor competition. The most powerful tool a founder has is **competing term sheets**.

---

**← [Module 01: The VC Ecosystem](./module-01-vc-ecosystem.md)** | **[Next Module: Funding Stages →](./module-03-funding-stages.md)**
