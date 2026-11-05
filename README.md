# Fixed Income Risk Analytics & Backtesting Platform 


<img width="432" height="13" alt="image" src="https://github.com/user-attachments/assets/45d6302b-4cd1-4f6e-83a9-c8a3d304b269" />


Production-style fixed income market risk engine implementing Hull-White and Vasicek interest-rate models, Monte Carlo simulation, VaR/CVaR analytics, Basel backtesting, and SR 11-7 model validation.

---

## Project Highlights

- Hull-White & Vasicek Short Rate Models
- Nelson-Siegel Yield Curve Fitting
- Monte Carlo Simulation (10,000 Paths)
- Fixed Income Portfolio Repricing
- 99% VaR / CVaR
- Stress Testing
- Key Rate Duration (KRD)
- Kupiec & Christoffersen Backtesting
- Basel Traffic Light Framework
- SR 11-7 Model Governance
- Automated Risk Reporting

---

## System Architecture

```text
Market Data
      │
      ▼
Yield Curve Construction
      │
      ▼
Hull-White / Vasicek Models
      │
      ▼
Monte Carlo Simulation
      │
      ▼
Portfolio Repricing
      │
      ▼
VaR / CVaR
      │
      ▼
Stress Testing
      │
      ▼
Model Validation
      │
      ▼
Automated Risk Report
```

---

## Validation Summary

| Validation Item | Result |
|-----------------|--------|
| Monte Carlo Paths | 10,000 |
| VaR Confidence Level | 99% |
| Kupiec POF Test | PASS |
| Christoffersen Test | PASS |
| Basel Traffic Light | Green Zone |
| Model Governance | SR 11-7 |

---

---
## 📸 Screenshots


* **Yield Curve Simulation**: Short Rate Simulations & Yield Curve Fitting.
* **VaR Distribution** 
* Portfolio P&L Distribution and VaR Thresholds 
* Stress Testing 
* Sensitivity analysis 
  
 <img width="2248" height="1657" alt="var_report_light" src="https://github.com/user-attachments/assets/3c81a0ad-b31e-4b13-bc82-2cf573403d8f" />



* Heat map (Hull-white)
  
<img width="1523" height="881" alt="heatmap_alpha_sigma_light" src="https://github.com/user-attachments/assets/3708e226-4da3-4a4f-a49a-b89069c9d579" />



## Technology Stack

**Programming**

Python • NumPy • Pandas • SciPy • Matplotlib

**Quantitative Models**

Hull-White • Vasicek • Nelson-Siegel • Monte Carlo

**Risk Analytics**

VaR • CVaR • Stress Testing • KRD

**Model Validation**

Kupiec • Christoffersen • Basel III • SR 11-7

---

## Repository Structure

```text
Fixed-Income-VaR-Backtesting-Engine/

├── src/
├── output/
├── reports/
├── figures/
├── README.md
└── requirements.txt
```

---

## Future Enhancements

- Multi-Factor Hull-White Model
- CIR Interest Rate Model
- Historical VaR
- Expected Shortfall (FRTB)
- Parallel Monte Carlo Simulation
- Streamlit Risk Dashboard
- Bloomberg / FRED Data Integration
- Docker Deployment

---

## References

- Vasicek (1977)
- Hull & White (1990)
- Nelson & Siegel (1987)
- Brigo & Mercurio (2006)
- Basel III Internal Models Approach
- SR 11-7 Supervisory Guidance on Model Risk Management


---


## 🚀 How to Run

### Prerequisites
Ensure you have Python 3.8+ installed. Install the essential quantitative stack:
```bash
pip install numpy pandas scipy matplotlib
