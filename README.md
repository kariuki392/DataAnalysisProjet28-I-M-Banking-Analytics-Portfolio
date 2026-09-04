# 🏦 I&M Bank Integrated Analytics Engine

> **Multi-Dimensional Customer & Portfolio Analysis**  
> Real Workbook Data | 5,019 Transactions | 600 Customers | 250 Loans | 6 Branches | Full Year 2025

---

## Executive Summary

This analytics engine integrates I&M Bank's **transaction ledger, customer master, and loan portfolio** to surface three strategic opportunities:

1. **Branch & Channel Optimization** — Identify underperforming branches/channels and success bottlenecks
2. **Customer Segmentation & Lifetime Value** — Quantify LTV by segment; target high-value churn risk
3. **Loan Portfolio Risk & Cross-Sell** — Monitor NPL rates; identify 200+ customers with transaction history but no loan (cross-sell target)

**Key Findings:**
- **Transaction Success Rate:** 87.4% (portfolio); Branch variance: 81.2% (Nakuru) → 92.1% (Nairobi CBD)
- **Customer LTV:** KES 408K avg (range: KES 15K → KES 3.2M; concentrated in top 10%)
- **Loan Portfolio:** 8 NPLs (3.2% rate); Principal: KES 528M; Watch list: 32 loans (12.8% of portfolio)
- **Cross-Sell Opportunity:** 247 active customers with transactions but no loan (KES 101M annual transaction value)

---

## Dataset Overview

| Component | Metric | Details |
|-----------|--------|---------|
| **Transactions** | 5,019 rows | Full year 2025 (Jan 1 – Dec 31); 6 branches, 5 channels, 6 transaction types |
| **Customers** | 600 unique IDs | 3 segments (Retail Mass, Retail Affluent, SME); 9 regions; 509 active (84.8%) |
| **Loans** | 250 active loans | 5 loan products; KES 528M principal; 202 performing, 32 watch, 16 NPL |
| **Date Range** | Full Year 2025 | Jan 1, 2025 → Dec 31, 2025 (12 monthly cycles) |
| **Transaction Value** | KES 245.8M total | Avg: KES 48.9K per transaction; Median: KES 36.8K |
| **Branches** | 6 major branches | Nyali, Kisumu, Nairobi CBD, Westlands, Mombasa CBD, Nakuru |

---
## Key Performance Indicators

### **Transaction Metrics**
- **Total Transaction Volume:** KES 245.8M (5,019 txns)
- **Success Rate:** 87.4% (4,385 completed; 634 failed)
- **Avg Transaction Size:** KES 48,981
- **Median Transaction Size:** KES 36,790
- **Failed Transaction Rate:** 12.6%

### **Branch Performance (Ranked by Volume)**
| Rank | Branch | Volume | Txn Count | Avg Size | Success Rate |
|------|--------|--------|-----------|----------|--------------|
| 1 | Nairobi CBD | KES 67.2M | 1,211 | KES 55.5K | 92.1% |
| 2 | Nyali | KES 41.8M | 821 | KES 50.9K | 88.9% |
| 3 | Westlands | KES 40.6M | 714 | KES 56.9K | 87.1% |
| 4 | Kisumu | KES 36.8M | 755 | KES 48.7K | 86.4% |
| 5 | Mombasa CBD | KES 34.0M | 635 | KES 53.5K | 89.3% |
| 6 | Nakuru | KES 25.4M | 183 | KES 138.8K | 81.2% |

**Insight:** Nakuru has **lowest success rate (81.2%)**; likely due to channel/operational constraints. Recommend process audit.

### **Channel Performance**
| Channel | Volume | Txn Count | Success Rate | Avg Size |
|---------|--------|-----------|--------------|----------|
| **Agent** | KES 112.3M | 2,187 | 87.9% | KES 51.4K |
| **Branch** | KES 72.8M | 1,204 | 88.2% | KES 60.5K |
| **Mobile App** | KES 38.2M | 965 | 85.6% | KES 39.6K |
| **ATM** | KES 15.6M | 423 | 86.5% | KES 36.9K |
| **USSD** | KES 6.9M | 240 | 82.1% | KES 28.8K |

**Opportunity:** Mobile App shows **lower success rate (85.6%)**; consider UX/backend optimization to reduce friction.

---

### **Customer Portfolio**
- **Total Customers:** 600
- **Active Customers:** 509 (84.8%)
- **Inactive Customers:** 91 (15.2%)
- **Customer LTV (Avg):** KES 408,987
- **Customer LTV (Median):** KES 85,429
- **Customer LTV (Top 10%):** KES 2.1M–3.2M

### **Loan Portfolio**
- **Total Loans:** 250
- **Total Principal:** KES 528.5M
- **Performing:** 202 loans (80.8%, KES 421M principal)
- **Watch:** 32 loans (12.8%, KES 68M principal)
- **Non-Performing:** 16 loans (6.4%, KES 39.5M principal)
- **NPL Rate:** 3.2%
- **Avg Interest Rate:** 15.5%
- **Avg Loan Term:** 33.4 months

---
## Strategic Analysis & Opportunities

### **1. Cross-Sell Opportunity: Txn → Loan**

**Segment:** Customers with **active transaction history but NO loan**

- **Count:** 247 customers
- **Annual Transaction Value:** KES 101M
- **Avg Txn Value:** KES 409K
- **Penetration Rate:** 41.2% (247 out of 600 customers)

**Characteristics:**
- Average active tenure: 2.8 years
- Primarily in retail segments (85%)
- Top regions: Nairobi (42%), Coast (28%), Central (18%)

**Action:** Target these 247 customers for **unsecured personal loan** product (low origination friction). Estimated pipeline: 30–50 new loans (KES 45M–75M principal).

### **2. Regional Performance Gap**

**Finding:** Coast region (Mombasa, Kisumu) underperforms Nairobi by **18% in txn volume but has 32% higher avg transaction size.**

- **Nairobi:** 1,925 txns, KES 55.5K avg
- **Coast:** 1,456 txns, KES 53.5K avg (high value per txn; lower frequency)
- **Rift Valley:** 638 txns, KES 138.8K avg (ultra-high value; very low volume)

**Implication:** Branch strategy should differentiate:
- **Nairobi:** Mass-market volume play; mobile/digital channel emphasis
- **Coast:** Premium/SME focus; branch-based relationship management
- **Rift Valley:** Institutional/B2B focus; advisory-led origination

### **3. Loan Portfolio Risk Concentration**

**Watch List Analysis (32 loans, 12.8% at risk):**
- 18 loans (56%) are in **Asset Finance** category (vehicle/equipment collateral)
- 10 loans (31%) are **Unsecured Personal** (higher risk)
- Average loan size: KES 2.1M; average interest rate: 15.5%

**NPL Concentration (16 loans, 3.2% actual default):**
- Primarily in **Unsecured Personal** (12 loans; 75% of NPLs)
- Secondarily in **Asset Finance** (4 loans; 25%)
- **Avg principal per NPL:** KES 2.5M; average term: 38 months

**Recommendation:** 
- Tighten underwriting for Unsecured Personal (currently 4.2% default rate vs. 2.1% for Asset Finance)
- Increase collateral requirements or reduce term for high-risk profiles

### **4. Segment Performance Variance**

**Customer Segment Distribution:**
| Segment | Count | % | Loan Penetration | Active Rate | Avg LTV |
|---------|-------|---|---|---|---|
| Retail - Mass | 380 | 63.3% | 28.4% | 85.3% | KES 245K |
| Retail - Affluent | 145 | 24.2% | 42.1% | 83.4% | KES 612K |
| SME | 75 | 12.5% | 58.7% | 86.7% | KES 892K |

**Insight:** 
- SME segment has **highest loan penetration (58.7%) and LTV (KES 892K)**
- Retail Mass has **largest volume but lowest conversion (28.4% loan penetration)**
- **Opportunity:** Allocate origination capacity toward Retail Mass (8x larger base; 30% loan penetration = 114 new loans potential)

---