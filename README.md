# ⚡ Firm Power, Recovered Heat

### 15 MW Gas-Fired CCHP Plant with Absorption Cooling for a Nigerian Data Center

🏆 **2nd Place, SPE Energython 2026 (Africa Region)**
Team **Byte & BTU** · SPE Student Chapter · Track: *From Molecule to Megabyte*

A techno-economic model for powering a 15 MW data center at the Lekki Free Trade Zone, Lagos. Recovered engine heat drives an absorption chiller that offsets about 95% of cooling electricity, improving facility PUE from 1.45 to 1.04. Power is priced at a 31% discount to the customer's current grid-plus-diesel cost.

## 📊 Headline results

| Metric | Value |
|---|---|
| Firm capacity | 15 MW (N+1), 19.8 MW installed |
| Total CAPEX | $47.9M ($2,418/kW) |
| NPV @ 16% WACC | **$23.1M** |
| Project IRR (unlevered) | **24.36%** |
| LCOE | 10.7 ¢/kWh (PPA: 14.5 ¢/kWh) |
| Simple payback | 3.19 years |
| Capacity factor | 92% |
| Availability | 99.99% (N+1) |
| Facility PUE | 1.04 (vs 1.45 gas-only) |
| Monte Carlo (5,000 runs) | P10 $13.2M · P50 $20.5M · P90 $28.8M · P(NPV>0) = 100% |

## The problem

Nigeria's grid suffers 10+ national collapses a year, and diesel backup costs about 2× grid power. Data centers need firm, affordable, 24/7 power, and the grid alone cannot provide it.

## The design

- **Site:** Lekki Free Trade Zone, Lagos. Screened for gas proximity (ELPS Lekki terminal), fibre access, zoning and water.
- **Fuel:** pipeline gas via the Escravos-Lagos Pipeline System (ELPS) under a take-or-pay Gas Supply Agreement.
- **Generation:** 6 × Jenbacher J620 (3.3 MW each), 5 duty + 1 standby. 45.8% electrical efficiency, 92.9% total efficiency.
- **Heat recovery:** 47.1% of fuel energy recovered from exhaust and jacket water, driving a double-effect Li-Br absorption chiller (COP 1.2) with a 4-hour thermal storage tank.
- **Backup:** 8-hour CNG ride-through with SCADA auto-failover in under 15 seconds.
- **Climate resilience:** closed-loop adiabatic cooling for Lekki's 85%+ humidity.
- **Scalability:** grows to 20 MW without re-permitting, with a fuel pathway to biomethane and hydrogen blends.

## Commercials

- **PPA:** $0.145/kWh, indexed 1.5%/yr
- **Cooling services:** $0.025/kWh-equivalent
- **Gas:** $2.18–3.10/MMBtu take-or-pay band, modeled at $3.50/MMBtu
- **Financing:** 80% debt ($38.30M) / 20% equity ($9.58M)

## Risk analysis

Tornado sensitivity (WACC and construction cost dominate NPV variance) plus a 5,000-run Monte Carlo on gas price, CAPEX, PPA price, capacity factor, WACC and O&M.

## Team

- **Benjamin Martins**: Project Lead, pitch and financial deck
- **Osasenaga Evbaguehita**: Technical design / CCHP
- **Stanley Joshua**: Risk and sensitivity analysis
- **Great Ojenike**: Commercial and regulatory

## 📁 Files

- 📄 [Round 1 presentation]([BYTE & BTU_Nigeria_Presentation.pptx](https://github.com/user-attachments/files/33583511/BYTE.BTU_Nigeria_Presentation.pptx)
)
- 📄 [Shark Tank finals deck]([BYTE AND BTU PTTS.pptx](https://github.com/user-attachments/files/33583512/BYTE.AND.BTU.PTTS.pptx)
)
- 📊 [Techno-economic model]([ENERGYTHON_GAS_CCHP_15MW_PLANT_TECHNO_ECONOMIC_MODEL_DATA_UPDATED1.xlsx](https://github.com/user-attachments/files/33583554/ENERGYTHON_GAS_CCHP_15MW_PLANT_TECHNO_ECONOMIC_MODEL_DATA_UPDATED1.xlsx))
)
)

---
*Built for the SPE Energython 2026, Africa Region. All figures are from the team's 20-year techno-economic model.*
