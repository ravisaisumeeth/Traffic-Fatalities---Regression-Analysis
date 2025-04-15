# 🚦 Traffic Fatalities Analysis – A Regression-Based Study

**An empirical policy analysis examining the relationship between traffic fatalities and various legislative and infrastructural factors across U.S. states.**

---

## 📊 Project Overview

This project investigates the impact of **traffic laws**, **speed limits**, and **infrastructure quality** on **traffic fatality rates** using **panel data regression models**. The findings offer data-driven insights for **policymakers**, **urban planners**, and **public health advocates** looking to improve road safety.

---

## 🧪 Methodology

The core econometric model used is:

dthrate_it = β₀ + β₁⋅Law_it + β₂⋅Speed_it + δ_i + γ_t + ϵ_it


- **Dependent Variable**: `dthrate_it` (traffic fatalities per 100,000 people in state _i_ at time _t_)
- **Independent Variables**:
  - `Law_it`: Binary indicator for presence of specific traffic laws (e.g., admin penalties, open container bans)
  - `Speed_it`: Maximum legal speed limit
- **Fixed Effects**: State-level (`δ_i`) and year-level (`γ_t`) effects
- **Residual**: `ϵ_it`, capturing unobserved influences

---

## 📌 Key Results

### ✅ Effect of Laws (`β₁`)
- **Coefficient**: ~ −0.225  
- **Interpretation**: Statistically significant (p < 0.05)  
- **Implication**: Each additional law correlates with a reduction in fatalities by **0.225 per 100,000 population**.

### ⚠️ Effect of Speed Limits (`β₂`)
- **Coefficient**: ~ +0.174  
- **Interpretation**: Not statistically significant (p > 0.05)  
- **Implication**: Higher speed limits are weakly associated with higher fatalities, but the evidence is inconclusive.

### 🔁 Interaction Term (`β₃`)
- `dthrate_it = β₀ + β₁⋅Law_it + β₂⋅Speed_it + β₃⋅(Law × Speed)_it + ϵ_it`
- **Effect**: Not statistically significant  
- **Interpretation**: No strong evidence for interaction between laws and speed in affecting fatalities

---

## 📍 Insights from Comparative Analysis

- States with higher enforcement of **traffic laws** tend to have **lower fatality rates**.
- Some states (e.g., with weak infrastructure or high default speed limits) show **persistently high death rates**.
- Visual comparison between 1985 and 1990 highlights how policy changes influenced fatality trends over time.

---

## 💡 Recommendations

### 🛡️ Stricter Laws & Enforcement
- Enforce open-container bans and administrative penalties
- Increase law adoption and funding for enforcement agencies

### 🚧 Infrastructure Upgrades
- Separate pedestrian/bike infrastructure  
- Improve lighting and road quality in high-risk areas

### 🎯 Targeted Policy
- Prioritize high-fatality states (identified via fixed effects) for interventions
- Explore reduced speed zones in urban or high-incident corridors

### 📢 Public Health Campaigns
- Launch education efforts against distracted and impaired driving
- Promote behavior change via testimonials and success stories

---

## 📈 Broader Impact

This study supports a **data-driven policy framework** that balances enforcement, infrastructure, and education. Stakeholders include:
- 🏛️ **Policymakers** (e.g., DOT, State Legislatures)
- 🧠 **Urban Planners**
- 🩺 **Public Health Advocates**



