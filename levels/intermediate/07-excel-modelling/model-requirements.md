# Model Building Requirements

Use these specifications to practise building models with Copilot assistance.

---

## Model 1: Monthly Operating Review Template

**Purpose:** Track monthly performance vs budget with variance analysis

**Required Components:**

### Inputs Tab
- Budget figures (by line item)
- Actual figures (by line item)
- Prior year figures (for comparison)
- Key assumptions (FX rates, headcount, etc.)

### Calculations Tab
- Variance calculations (absolute and %)
- Year-to-date totals
- Run rate projections (Q4 forecast based on trends)
- Variance explanations (text fields)

### Dashboard Tab
- Traffic light indicators (green/amber/red based on variance %)
- Key metrics summary (revenue, margin, EBITDA)
- Trend charts (monthly actuals vs budget)
- Top 5 variances table

**Sample Prompt:**
```
Create a monthly operating review template with:
1. Input section for budget, actual, and prior year by line item
2. Calculations for variance ($ and %), YTD, and run rate
3. Dashboard with traffic lights (green <5%, amber 5-10%, red >10% variance)
4. Include data validation for inputs
```

---

## Model 2: Investment ROI Calculator

**Purpose:** Evaluate proposed investments and calculate payback

**Required Components:**

### Inputs
- Initial investment amount
- Annual cost savings or revenue increase
- Implementation costs by year
- Discount rate
- Project timeline (years)

### Calculations
- Annual net cash flow
- Cumulative cash flow
- Payback period (years and months)
- NPV calculation
- IRR calculation

### Outputs
- Summary metrics box
- Cash flow chart
- Sensitivity table (NPV at different discount rates)
- Go/No-Go recommendation logic

**Sample Prompt:**
```
Build an investment ROI calculator with:
- Inputs: investment amount, annual benefits, costs, discount rate, timeline
- Calculations: NPV, IRR, payback period
- Sensitivity table showing NPV at discount rates from 5% to 15%
- Visual cash flow chart
- Automatic recommendation based on NPV and payback thresholds
```

---

## Model 3: Scenario Planning Model

**Purpose:** Compare three scenarios with different assumptions

**Required Components:**

### Inputs
- Base case assumptions
- Upside assumptions (toggle)
- Downside assumptions (toggle)
- Scenario selector dropdown

### Calculations
- Revenue projections by scenario
- Cost projections by scenario
- Profit calculations
- Key ratios

### Outputs
- Scenario comparison table
- Variance between scenarios
- Probability-weighted outcome
- Risk indicators

**Sample Prompt:**
```
Create a scenario planning model with:
- Dropdown to select Base/Upside/Downside scenario
- Each scenario has different assumptions for: revenue growth, margin, costs
- Automatic recalculation when scenario changes
- Summary comparison showing all three scenarios side by side
- Probability-weighted expected outcome (assign probability to each scenario)
```

---

## Tips for Model Building with Copilot

1. **Start with structure** — Describe the overall architecture before details
2. **Request best practices** — Ask for named ranges, formatting, documentation
3. **Build incrementally** — Get one section working before adding the next
4. **Verify formulas** — Always spot-check AI-generated calculations
5. **Add documentation** — Request comments and instructions for users

