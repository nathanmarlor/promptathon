# Sample Decision Scenario: Vendor Selection

Use this scenario to practise decision analysis prompts.

---

## The Decision

You need to select a customer relationship management (CRM) platform for your organisation. You've narrowed it down to two finalists.

---

## Option A: Enterprise Suite (Established Vendor)

**Vendor:** GlobalTech Solutions (Fortune 500 company, 25+ years in market)

**Pricing:**
- £180,000 annual license (3-year contract required)
- £75,000 implementation
- £30,000 annual support

**Strengths:**
- Comprehensive feature set—covers 95% of requirements out of the box
- Strong integration with your existing ERP system
- 24/7 global support with guaranteed 4-hour response time
- Extensive training resources and certification programmes
- Used by 3 of your competitors

**Concerns:**
- Interface is dated—users describe it as "functional but clunky"
- Customisation requires expensive professional services
- Mobile experience is weak compared to newer platforms
- Vendor has reputation for aggressive upselling
- Implementation timeline: 6-9 months

---

## Option B: CloudFirst CRM (Growth-Stage Vendor)

**Vendor:** CloudFirst (Series C startup, 8 years in market, strong growth)

**Pricing:**
- £95,000 annual license (annual contracts available)
- £40,000 implementation
- £15,000 annual support

**Strengths:**
- Modern, intuitive interface—users consistently rate UX highly
- Strong mobile app
- Flexible customisation via low-code tools
- AI-powered features for forecasting and next-best-action
- Faster implementation: 3-4 months
- Customer success team assigned to your account

**Concerns:**
- Missing 2 features you need (planned for Q3 release, not guaranteed)
- Smaller company—some risk around long-term viability
- Integration with your ERP requires middleware (additional £25K)
- Support hours: business hours only in your timezone
- Only 1 reference customer in your industry

---

## Context for Your Decision

**Budget:** Approved for up to £350,000 first year, preference to stay under £300K

**Timeline:** Go-live needed by September (8 months away)

**Team:** 150 users, mix of tech-savvy and tech-resistant

**Priorities (as stated by your leadership):**
1. User adoption—previous CRM failed due to low usage
2. Total cost of ownership over 3 years
3. Integration reliability
4. Vendor stability

**Political considerations:**
- IT department prefers Option A (they know the platform)
- Sales leadership prefers Option B (they saw the demo)
- CFO is focused on the 3-year cost comparison

---

## Your Task

Use this scenario to practise:

1. **Options analysis:** Get Copilot to structure a comparison
2. **Devil's advocate:** If you lean toward one option, have Copilot argue against it
3. **Risk assessment:** Identify what could go wrong with each option

---

## Sample Prompt

```
Context: I'm deciding between two CRM vendors for my organisation.

Option A: Enterprise Suite - £285K first year, established vendor, 
comprehensive features but dated UX, 6-9 month implementation

Option B: CloudFirst - £175K first year, modern UX and AI features, 
but missing 2 features and smaller vendor, 3-4 month implementation

Key factors: 150 users (adoption is critical), September go-live deadline, 
leadership prioritises user adoption and 3-year TCO.

Language: Analytical and direct. Don't hedge—give me a clear recommendation.

Request: 
1. Create a comparison table across these criteria: cost (3-year), 
   implementation risk, adoption likelihood, vendor stability, feature fit
2. Rate each option on each criterion (1-5)
3. Identify the top 3 risks for each option
4. Give me your recommendation with clear rationale
```

