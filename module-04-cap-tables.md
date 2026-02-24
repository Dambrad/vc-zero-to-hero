# Module 04: Cap Tables
## Tracking Ownership, Dilution, and the Real Score

---

**← [Module 03](./module-03-funding-stages.md)** | **[Back to Syllabus](./README.md)** | **[Next Module →](./module-05-term-sheets.md)**

---

## 🎯 What You'll Learn

- What a capitalization table (cap table) is and why it matters
- The difference between authorized shares, issued shares, and the fully diluted share count
- What dilution is and how it affects founders over time
- How option pools fit into the ownership picture
- How to build a simple cap table from scratch
- How to model a funding round and see its impact on ownership

---

## ⏱️ Estimated Time

| Section | Time |
|---------|------|
| Core Concepts | 60–75 min |
| Case Study | 20–30 min |
| Lab Exercise | 60–75 min |
| Resources | Self-paced |
| **Total** | **~3–4 hours** |

---

## 📖 Core Concepts

### 4.1 — What Is a Cap Table?

A **capitalization table** (cap table) is a spreadsheet or document that lists:
- **Who owns what** in the company
- **How many shares** they own
- **What percentage** of the company each person represents
- **What type of shares** they hold

Think of it as the **official scoreboard of ownership**. Every time the company issues new shares — to a founder, investor, or employee — the cap table is updated.

> 💡 **Why it matters:** Your cap table determines who gets paid, how much, and in what order when the company has an exit event (acquisition or IPO). A founder who doesn't understand their cap table can be blindsided at the moment of their biggest win.

---

### 4.2 — Share Types: The Basics

Not all shares are equal. Here are the three types you'll encounter most:

#### Common Stock
- Held by **founders** and **employees** (typically through options)
- The "plain vanilla" shares
- Last in line to get paid in a liquidation event
- Most voting rights go here, but often less economic priority

#### Preferred Stock
- Held by **investors** (VCs, angels)
- Has special rights and protections (liquidation preference, anti-dilution)
- Gets paid out *before* common in most exit scenarios
- We'll go deep on this in Module 05

#### Options (Stock Options)
- Held by **employees and advisors**
- Not shares themselves — they are the *right to purchase shares* at a fixed price
- Typically vest over time (see Module 06)
- Part of the "fully diluted" share count

---

### 4.3 — Key Terminology You Need to Know

#### Authorized Shares
The total number of shares the company is **legally allowed to issue**, as defined in the Certificate of Incorporation. This is the ceiling.

> Example: A company authorizes 10,000,000 shares. That doesn't mean all 10M exist yet — it just means the company *could* issue up to that many.

#### Issued Shares
The number of shares that have **actually been issued** to someone (founders, investors, employees). This is the actual count.

#### Fully Diluted Share Count
The total number of shares that *would* exist if every option, warrant, SAFE, and convertible note converted to equity. This is the most important number for calculating true ownership percentages.

```
Fully Diluted = Issued Common + Issued Preferred + All Unexercised Options + Warrants + Convertible Instruments
```

**Why fully diluted matters:** When you're told you own 30% of the company, the critical question is — 30% of *what*? Of issued shares? Or fully diluted? The answer can be very different.

#### Option Pool
A reserved block of shares set aside for future employee grants. Typically 10–20% of the fully diluted cap.

> ⚠️ **The Option Pool Shuffle:** VCs often require founders to set aside a new or expanded option pool *before* they invest, which comes out of the *pre-money* valuation. This dilutes founders, not the new investors. This is one of the subtler ways founders get squeezed in term sheet negotiations. We'll cover this in Module 05.

---

### 4.4 — Understanding Dilution

**Dilution** happens every time new shares are issued. Your percentage ownership goes down even though you still own the same number of shares.

**The analogy:** Imagine the company is a pizza. You start with the whole pizza. Every time you raise money or give out options, you cut more slices and give them away. Your original slices haven't changed in size — but as a fraction of the whole pizza, they represent less.

**A simple dilution example:**

| Event | Your Shares | Total Shares | Your % |
|-------|------------|--------------|--------|
| Company formation | 1,000,000 | 1,000,000 | 100% |
| Co-founder joins | 1,000,000 | 2,000,000 | 50% |
| Option pool created | 1,000,000 | 2,500,000 | 40% |
| Seed round (VC gets 20%) | 1,000,000 | 3,125,000 | 32% |
| Series A (VC gets 20%) | 1,000,000 | 3,906,250 | 25.6% |

After just two funding rounds, a founder who started at 50% (with a co-founder) is now at ~25.6%. This is completely normal and not inherently bad — **dilution is the cost of growth**. The question is whether the dollars raised help the company grow fast enough to make your smaller slice worth far more than your larger slice was.

> 💡 **The key insight:** It's better to own 20% of a $500M company than 80% of a $2M company. Dilution is only bad if the money raised doesn't create value.

---

### 4.5 — Pro-Rata Rights

**Pro-rata rights** give existing investors the right to invest in future rounds to maintain their ownership percentage.

> Example: VC owns 15% after the Seed round. At Series A, new shares are issued and their ownership would normally drop to 10%. Pro-rata rights allow them to invest additional money in the Series A to stay at 15%.

Why do founders care? Pro-rata rights can crowd out new investors at later stages. They also create tension when existing investors want to use them but new investors want a clean cap table.

---

## 🌍 Real-World Case Study: The Facebook Cap Table & Eduardo Saverin

One of the most famous (and dramatic) cap table stories in Silicon Valley history.

**The Beginning (2004):** Facebook was founded at Harvard by Mark Zuckerberg, Eduardo Saverin, Dustin Moskovitz, and Chris Hughes. Saverin was the co-founder who put in the first $19,000 and handled early business operations. He held approximately **34% of the company**.

**The Problem:** Saverin froze the original Facebook bank account in a dispute and moved back to New York. Meanwhile, Zuckerberg was building the company and adding key people like Sean Parker and early investor Peter Thiel.

**The Dilution:** When Facebook incorporated in Delaware as a new entity, new shares were issued. Saverin's stake was diluted from ~34% down to approximately **0.03%** — roughly $1,000 shares — a dilution that Saverin's legal team argued was done improperly to punish him rather than for legitimate business purposes.

**The Settlement:** Saverin sued. The case was settled out of court. The final movie "The Social Network" dramatizes this story. The actual settlement terms were not disclosed, but Saverin ultimately received a portion of Facebook's equity that made him a billionaire many times over at IPO.

**What This Teaches Us:**

1. **Cap tables are legally and financially binding documents.** Changes to them have enormous consequences.
2. **Founder agreements must address what happens if a co-founder leaves or disengages.** (This is typically handled through vesting — Module 06)
3. **Dilution can be used as a weapon** if agreements aren't clear.
4. **Always have a lawyer review any cap table changes** that affect your ownership.

> 🤔 **Reflection Question:** If you were Eduardo Saverin, what clause in a co-founder agreement would have protected you? What should every founding team put in writing from Day 1?

---

## 🔬 Lab Exercise: Build a Basic Cap Table

**Objective:** Build a cap table from scratch in Google Sheets or Excel, model two rounds of funding, and see how dilution works.

**Time:** 60–75 minutes

**Setup:** Download or open Google Sheets. Create a new spreadsheet titled **"StartupXYZ Cap Table"**

---

#### Part 1: Company Formation

Set up the following:

**Sheet 1: "Founding Round"**

| Name | Role | Share Class | Shares | % Ownership |
|------|------|-------------|--------|-------------|
| Alex Chen | CEO/Founder | Common | 4,000,000 | =B2/SUM(B2:B10) |
| Jamie Rivera | CTO/Founder | Common | 3,000,000 | |
| Option Pool | Employee Equity | Common (Reserved) | 1,000,000 | |
| **TOTAL** | | | **8,000,000** | **100%** |

*Your Task:* Enter this into a spreadsheet. Use formulas for the % column (each row ÷ total shares).

---

#### Part 2: Seed Round

A Seed investor offers $1.5M at a $6M pre-money valuation.

*Calculate:*
1. Post-money valuation = ?
2. Investor's ownership % = Investment ÷ Post-money = ?
3. New shares to issue = (Investor % × Total shares before round) ÷ (1 − Investor %)

*Hint:* Use the formula:
```
New shares = Existing shares × (Investment / Pre-money valuation)
```
```
New shares = 8,000,000 × ($1,500,000 / $6,000,000) = 2,000,000 new shares
```

**Sheet 2: "Post-Seed Cap Table"**

| Name | Shares | % Ownership |
|------|--------|-------------|
| Alex Chen | 4,000,000 | |
| Jamie Rivera | 3,000,000 | |
| Option Pool | 1,000,000 | |
| Seed VC | 2,000,000 | |
| **TOTAL** | **10,000,000** | **100%** |

*Fill in the % ownership column using formulas.*

---

#### Part 3: Series A Round

Now the company raises a $5M Series A at a $20M pre-money valuation. As part of the deal, the investors require a **10% post-money option pool** (new options must be added before the round is priced).

*Your Tasks:*
1. Add 1,500,000 new options to the option pool (bringing it to 2,500,000 total)
2. Calculate Series A investor's new shares using the same formula
3. Build "Sheet 3: Post-Series A Cap Table"
4. Show everyone's new ownership percentage

*Expected Result:* The founders should each be in the 25–35% range. The Seed VC should be around 15–20%. The Series A VC should have ~20%.

---

#### Part 4: Reflection Questions

Answer these in writing (a few sentences each):

1. How much did Alex's ownership change from founding to post-Series A?
2. If the company was acquired for $50M post-Series A, how much would Alex receive (assuming no liquidation preference complications)?
3. What would Alex's outcome be if the company was acquired for $200M?
4. Was dilution worth it? Justify your answer.

---

**Bonus:** Use [Carta's free cap table template](https://carta.com/cap-table-template/) or [Capshare](https://capshare.com) to recreate this cap table in a professional tool.

---

## 📚 Resource Pack

### 📺 YouTube Videos
1. **"Cap Tables Explained"** — Carta
   Search: `Carta cap table explained`
   *The leading cap table software company explains their own domain.*

2. **"How Startup Equity Works"** — Y Combinator
   Search: `Y Combinator how startup equity works`
   *Clean, authoritative, beginner-friendly.*

3. **"Cap Table Modeling"** — VC Lab
   Search: `VC Lab cap table modeling tutorial`
   *More technical walkthrough with actual spreadsheet work.*

4. **"Dilution Explained for Founders"** — Slidebean
   Search: `Slidebean dilution explained founders`
   *Visual and clear.*

### 📖 Books
- *Venture Deals*, **Chapters 5–6** — Cap tables and dilution mechanics
- *Secrets of Sand Hill Road*, **Chapter 6** — Ownership and dilution

### 🌐 Tools & Resources
- **[Carta](https://carta.com)** — The industry standard cap table management software (free for very early-stage)
- **[AngelList Cap Table Template](https://angel.co)** — Simple free template
- **[FAST Agreement (Y Combinator)](https://www.ycombinator.com/documents)** — Standard forms including cap table supporting docs
- **"The Option Pool Shuffle" blog post** — Search: `Venture Hacks option pool shuffle` — This is a must-read about how option pools affect founder dilution

---

## ✅ Module 04 Checklist

- [ ] I know the difference between authorized, issued, and fully diluted shares
- [ ] I can explain what dilution is using the pizza analogy (or any other analogy in my own words)
- [ ] I understand what an option pool is and why it matters
- [ ] I completed the cap table lab and correctly modeled both the Seed and Series A rounds
- [ ] I know what pro-rata rights are and why they matter to investors
- [ ] I understand the Facebook/Saverin story and what it teaches about cap table governance

---

## 🔁 Module Summary (TL;DR)

A cap table is the **source of truth for ownership**. Every new share issuance — to founders, investors, or employees — dilutes existing holders. **Dilution is normal and expected**, but it must be understood and monitored. The **fully diluted share count** is the right number to use when calculating true ownership. Option pools are set aside for employees but are typically funded by founders' equity. Always model rounds *before* signing term sheets to know exactly what you're agreeing to.

---

**← [Module 03: Funding Stages](./module-03-funding-stages.md)** | **[Next Module: Term Sheets →](./module-05-term-sheets.md)**
