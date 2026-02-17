# Finn — Your AI Finance Tracker That Actually Knows Your Money

> ⚠️ **DRAFT** — This specialist was created on Feb 17, 2026 and has not yet been manually reviewed. Content, structure, and instructions may change.

Every budgeting app tracks transactions. Finn tracks **your financial life** — your income, your debts, your goals, that car payment ending in March, and the emergency fund you've been building since September. He gives advice that gets smarter every session because he never forgets your situation.

## The Problem

You ask an AI to help with your budget. It gives you a generic 50/30/20 template. Next month, you ask again — it has no idea you exist. You re-explain your salary, your three credit cards, your goal of buying a house in two years. Every. Single. Time.

**Finn fixes this.**

## What Finn Does

💰 **Personalized Budgeting** — Budgets built around your actual income, expenses, and goals — not templates you'll abandon in two weeks

📊 **Spending Pattern Recognition** — Finn learns where your money goes and spots trends you might miss. "You've been spending 40% more on dining this quarter..."

🎯 **Goal Tracking** — Emergency fund, debt payoff, house down payment, retirement. Finn remembers every goal and tracks your progress across sessions.

💳 **Debt Strategy** — Avalanche, snowball, or hybrid — Finn knows your debts, rates, and balances, and recommends the approach that fits your personality

📈 **Investment Guidance** — Simple, practical investment advice aligned with your risk tolerance and timeline. No stock picks, just solid principles.

🧾 **Tax Awareness** — Seasonal reminders, deduction tracking, and knowing when to tell you "talk to a CPA about this one"

## How It Works

Finn is an **AI Specialist** built on [Magic Context](https://magiccontext.ai). Instead of starting every AI conversation from scratch, Finn maintains a persistent workspace — your financial profile, spending patterns, goals, and history — that carries across every session.

```
┌──────────────────────────────────────────┐
│          Finn's Workspace                │
├──────────────────────────────────────────┤
│                                          │
│  📋 AI Instructions                      │
│  ├── Advising personality & style        │
│  ├── Financial principles                │
│  └── Memory protocols                    │
│                                          │
│  🧠 Memory                               │
│  ├── Financial profile (income, debts)   │
│  ├── Preferences (risk, budgeting style) │
│  └── Spending patterns                   │
│                                          │
│  📚 Knowledge Base                       │
│  ├── Budgeting methods                   │
│  ├── Investment basics                   │
│  ├── Debt payoff strategies              │
│  └── Tax fundamentals                    │
│                                          │
│  🎯 Active Projects                      │
│  ├── Current budget                      │
│  └── Financial goals                     │
│                                          │
│  📝 Templates                            │
│  ├── Monthly budget                      │
│  ├── Net worth snapshot                  │
│  └── Financial review                    │
│                                          │
└──────────────────────────────────────────┘
```

### The Magic Context Difference

Traditional AI is **stateless** — it forgets everything between conversations. Magic Context gives AI specialists **persistent memory** through structured workspaces. This means:

- **Session 1:** Finn learns your income, debts, goals, and financial philosophy
- **Session 5:** Finn adjusts your budget because your dining spending keeps exceeding the plan
- **Session 20:** Finn knows your patterns — you overspend around holidays, you're more disciplined when you review weekly, and the snowball method keeps you motivated
- **Session 50+:** Finn is a financial advisor who knows your complete financial picture better than anyone

**Your context is yours.** It's stored as plain markdown files you can read, edit, or export anytime. No black box. No vendor lock-in.

## Quick Start

### Import to AI Specialists Hub

```bash
# Via the Magic Context import feature
import_specialist github.com/magic-context/finn-finance-tracker
```

Or use the import tool in [AI Specialists Hub](https://aispecialistshub.com) with:
```
https://github.com/magic-context/finn-finance-tracker
```

### First Session

Finn will guide you through a financial intake:
1. Your income sources
2. Fixed and variable expenses
3. Current debts (type, balance, rates)
4. Savings and investment accounts
5. Financial goals
6. Your money mindset and preferences

Then he'll build your first personalized budget.

### Ongoing Use

- **Start of month:** Review and set the monthly budget
- **Throughout month:** Log expenses, ask questions, get guidance
- **End of month:** Financial review — what worked, what didn't
- **Quarterly:** Net worth snapshot, goal recalibration
- **Anytime:** Debt strategy, investment questions, tax planning

## Repository Structure

```
finn-finance-tracker/
├── configuration/
│   └── module.json              # Specialist metadata
├── content/
│   ├── README.md               # Workspace guide
│   ├── ai-instructions/        # Finn's financial brain
│   │   ├── core-instructions.md
│   │   ├── getting_started.md
│   │   └── memory-protocols.md
│   ├── memory/                 # Your financial profile
│   │   ├── user-profile.md
│   │   └── preferences.md
│   ├── knowledge/              # Financial expertise
│   │   ├── budgeting-methods.md
│   │   ├── investment-basics.md
│   │   ├── debt-strategies.md
│   │   ├── tax-basics.md
│   │   └── templates/
│   │       ├── monthly-budget.md
│   │       ├── net-worth-snapshot.md
│   │       └── financial-review.md
│   ├── active-projects/        # Current financial plan
│   │   └── current-goals.md
│   ├── historical/             # Past budgets and reviews
│   └── feedback/               # Improvement notes
└── README.md
```

## Who This Is For

- **Young professionals** getting serious about money for the first time
- **Families** juggling multiple financial goals and competing priorities
- **People in debt** who need a consistent strategy and accountability partner
- **Anyone tired of re-explaining their financial situation** to AI every single time

## Suggested MCP Skill Pairings

Finn works with any MCP-compatible AI agent (Claude, GPT, Gemini, etc.). These integrations enhance the experience:

- **Email Integration** — Monitor bank statements, bill notifications, and financial alerts
- **Project Management & Notes** — Rich visual dashboards for financial data
- **Kanban / Task Boards** — Track financial goals with progress checklists
- **Visual Display** — Display budget summaries and spending charts
- **Conversation History** — Recall past financial decisions and adjustments

## Important Note

Finn is a financial coaching AI, not a licensed financial advisor. For complex tax situations, estate planning, or specific investment recommendations, consult a qualified professional. Finn will tell you when it's time to do that.

## Requirements

- [AI Specialists Hub](https://aispecialistshub.com) account (or any Magic Context-compatible platform)
- ChatGPT Plus/Pro/Team/Enterprise OR Claude with MCP support

## Contributing

Feedback and improvements welcome via issues. This is a showcase specialist for Magic Context — if Finn helps you get control of your money, imagine what a persistent AI specialist could do for *your* domain.

## License

MIT

---

Built with [Magic Context](https://magiccontext.ai) — Context as a Service for AI
