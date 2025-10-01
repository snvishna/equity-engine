# ⚙️ EquityEngine: The Financial Independence Simulator

A professional-grade, strategic simulator for achieving Financial Independence (FI) through a hybrid portfolio of real estate and stock market investments. Like its companion tool, [PropertyLens](https://nivas.homes/calculators/property-lens), it runs entirely in your browser. No ads, no subscriptions, no data collection. **100% private and secure.**

---

## 🤔 Why EquityEngine?

While **PropertyLens** answers the critical question, *"Is this a good deal?"*, serious investors must answer a bigger question: ***"What is my strategic path to financial independence?"***

Answering this requires looking beyond a single property and modeling an entire portfolio over decades. Most FI tools fall short:
1.  **Oversimplify Real Estate:** They treat real estate as a simple asset with an average return, ignoring the powerful mechanics of leverage, debt paydown, and tax benefits.
2.  **Ignore Opportunity Cost:** They fail to compare a real estate strategy against the simpler, passive alternative of just investing in the stock market.
3.  **Lack Integration:** They force you to manually input data, creating a disconnect between your detailed deal analysis and your long-term life plan.

**EquityEngine** was built to be the definitive bridge between analyzing deals and architecting your future. It's a sophisticated simulation engine that models your entire financial journey, allowing you to compare a hybrid real estate strategy against a traditional stock portfolio with analytical rigor.

---

## ✨ Key Features

EquityEngine is designed to provide deep, strategic insights that empower you to build a concrete, data-driven plan for financial independence.

-   **🎯 Hybrid Portfolio Simulation:** The core of the application. It runs two parallel simulations year-by-year:
    1.  A **Real Estate Portfolio**, funded by a portion of your savings and its own cash flow.
    2.  A **Stock Portfolio (S&P 500)**, funded by the remaining portion of your savings.
    This provides a true "apples-to-apples" comparison of your chosen strategy against the market benchmark.

-   **🔗 Seamless `PropertyLens` Integration:** Don't just simulate with averages. Import your real, fully analyzed deals from `PropertyLens` to form the foundation of your starting portfolio. Your meticulous deal analysis flows directly into your long-term life plan.

-   **♟️ Strategic FIRE Modeling:** This is not a simple retirement calculator. The engine is built on core Financial Independence, Retire Early (FIRE) principles:
    -   **Inflation-Adjusted Goals:** Your target income isn't static; it grows with inflation, reflecting real-world purchasing power needs.
    -   **"Coast FIRE" Scenarios:** Model a post-W2, lower-stress job. The engine shows how even a small amount of "Coast FIRE" income can dramatically accelerate your timeline to freedom.
    -   **Smart Capital Allocation:** Use the "Strategic Allocation" slider to decide how to deploy your annual savings between real estate and stocks, or choose a pre-set allocation based on your risk profile.

-   **🔒 100% Private & Standalone:** All calculations happen in your browser. Your personal financial data—your income, savings, and portfolio details—never leaves your computer.

-   **📈 Advanced Visualization & Analytics:** The UI is designed to tell a clear financial story through three purpose-built charts:
    -   **Net Worth Trajectory:** The 30,000-foot view, comparing the growth of your Real Estate Equity against your Stock Portfolio.
    -   **Path to Financial Independence:** The most important chart, tracking your portfolio's passive cash flow against your inflation-adjusted income target.
    -   **Capital Composition:** A breakdown of how your net worth is allocated between illiquid real estate equity and your liquid investment accounts over time.

-   **🧠 Sophisticated Financial Engine:** Each property, whether imported or a future archetype, is an independent entity in the simulation. It ages, appreciates, and amortizes its own specific loan based on the unique terms you defined, providing a far more accurate portfolio projection than simple averages.

---

## 🔬 A Deep Dive: Understanding the Metrics

### ➤ Input Metrics (The "Levers" of Your Strategy)

#### Personal Finances & Goals
-   **Current W2 Income:** Your primary annual income before taxes.
-   **Total Annual Savings:** The total cash you set aside each year for *all* investments.
-   **Initial Investment Capital:** The lump sum you're starting with today.
-   **Post-W2 'Coast FIRE' Income:** The income you plan to earn after leaving your primary career.
-   **Marginal Tax Rate (%):** Your blended tax rate, used for calculating the after-tax cash flow of your portfolio.
-   **Inflation Rate (%):** The expected long-term inflation rate, used to create a realistic, rising income target.

#### Strategic Allocation
-   **Risk Profile:** Choose a profile (Conservative, Moderate, Aggressive) to get a suggested allocation for your annual savings, or select "Custom."
-   **Annual Savings Allocation (%):** The slider that lets you manually define how much of your savings goes to your "RE War Chest" vs. your Stock Portfolio each year.

#### Starting Portfolio
-   **Import from PropertyLens:** The core integration feature. Load your saved scenarios, specify how many years you've owned each, and check which ones to include in the simulation's starting point.

#### Future Acquisitions Plan
-   **Acquisition Cadence:** How often you plan to buy a new property (e.g., every 2 years).
-   **Deal Archetype:** The profile of a *typical* future property you plan to buy. This includes purchase price, financing, rent, expenses, and growth rate assumptions.

### ➤ Output Metrics (The "Gauges" of Your Journey)

#### The Financial Independence Dashboard
This is the command center, giving you the final verdict on your strategy.
-   **Freedom Year:** The year your portfolio's passive income is projected to meet or exceed your inflation-adjusted income target.
-   **Total Properties:** The size of your real estate portfolio in your "Freedom Year."
-   **RE Net Worth:** The total equity across all your properties at your FI date.
-   **S&P 500 Value:** The value of your stock portfolio at your FI date.
-   **Total Cash Invested (RE):** The total out-of-pocket capital deployed into your real estate portfolio over the entire timeline.
-   **Portfolio IRR:** The "true" annualized return of your entire real estate strategy, accounting for all cash inflows and outflows.

---

## 🚀 Getting Started

1.  Download the `equityengine.html` file.
2.  Open it in any modern web browser.
3.  For the best experience, first analyze and save several deals in **PropertyLens**. Then, use the import feature in **EquityEngine** to build your simulation.

---

## 🗺️ Contributing & Future Roadmap

This is the first version of a powerful new tool. Contributions are welcome! Some features on the roadmap:
-   Modeling property sales and 1031 exchanges.
-   Allowing for multiple, different deal archetypes in a single acquisition plan.
-   More complex debt modeling (e.g., refinancing events).

---

## 📜 License

This project is licensed under the **MIT License**.
