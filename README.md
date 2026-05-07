<div align="center">
  
# 👋 Hi, I'm Virgile Roumens

**Freight & Dry Bulk Markets | Quantitative Finance Engineer | Python Developer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/virgile-roumens)
[![Email](https://img.shields.io/badge/Email-virgile.roumens@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:virgile.roumens@gmail.com)
[![Location](https://img.shields.io/badge/Geneva-Switzerland-red?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

## 🚀 About Me

Financial Engineer (ESILV, Paris) working at the intersection of **physical commodity markets** and **quantitative analysis**. I bridge the gap between financial theory and real-world trading through hands-on Python development and market intelligence — currently focused on dry bulk freight markets, where macro, geopolitics, and fundamentals collide every day.

🚢 **Currently:** Graduate Trainee · Freight Trading Platform · Global Agricultural Commodity Merchant  
🌍 **Based in:** Geneva, Switzerland  
🎓 **Background:** ESILV — MEng Financial Engineering (Paris)  
🚲 **Recent Adventure:** Solo cycled **4,400 km from France to Greece** with just a bike and tent  
⚡ **Fun Fact:** Competed in CME Group & Bloomberg Trading Challenges

---

## 🛠️ Tech Stack

### Languages & Tools
![Python](https://img.shields.io/badge/Python-Expert-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Proficient-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-Proficient-F05032?style=flat-square&logo=git&logoColor=white)
![VBA](https://img.shields.io/badge/VBA-Proficient-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![C++](https://img.shields.io/badge/C++-Intermediate-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![R](https://img.shields.io/badge/R-Intermediate-276DC3?style=flat-square&logo=r&logoColor=white)

### Financial & Data Science
![Bloomberg](https://img.shields.io/badge/Bloomberg_Terminal-BMC_Certified-000000?style=flat-square&logo=bloomberg&logoColor=white)
![Dash](https://img.shields.io/badge/Plotly_Dash-00CC96?style=flat-square&logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-Machine_Learning-orange?style=flat-square)

---

## 📊 Featured Projects

### 🚢 [FreightIQ — Dry Bulk Intelligence Platform](https://github.com/Virgile-Roumens/freight-intelligence)
**Production-grade freight market intelligence workspace built with Plotly Dash**

A comprehensive platform aggregating live and historical freight market data into a Bloomberg-style trading workspace:
- 🛰️ **Live AIS vessel tracking** via aisstream.io WebSocket — fleet utilisation, slow-steaming detection, chokepoint traffic
- 🔮 **5TC Capes FFA forward curve** derived from BDRY options via put-call parity, with implied BDI calibration
- 📈 **10 dedicated pages**: Market Dashboard, Freight Analysis, Supply & Demand, Geopolitical Intel, Macro Overlay, FFA Derivatives, Cross-Commodity, TCE Calculator, Intelligence Feed
- 📧 **Automated daily morning briefing email** delivered at 07:30 CET via GitHub Actions cron — overnight market context, key levels, FFA curve, supply/demand drivers, news with relevance scoring
- ⚖️ **TCE Calculator** with sensitivity analysis and breakeven freight rate solver
- 🌍 **Chokepoint monitoring** (Suez, Hormuz, Red Sea, Panama, Malacca) with live vessel counts

**Tech:** Python, Plotly Dash, yfinance, FRED API, AIS WebSocket, GitHub Actions, SMTP

---

### 🏆 [Commodity Trading System](https://github.com/Virgile-Roumens/commodities_trading_platform.git)
**ML-Powered Trading Desk with Black-Litterman Portfolio Optimization**

Professional commodity trading platform featuring:
- 🤖 **XGBoost forecasting** with 40+ engineered features
- 📈 **Black-Litterman optimization** combining ML forecasts with market equilibrium
- 🎯 **Profile-adaptive strategies** (16 risk/horizon combinations)
- ⚡ **Numba-accelerated** computations (5-20x speedup)
- 📊 **Interactive Streamlit dashboard** with multi-page analysis

**Tech:** Python, XGBoost, Streamlit, Plotly, Numba, Yahoo Finance API

---

### ⚓ [Freight Dispersion Trading](https://github.com/Virgile-Roumens/freight_dispersion_trading.git)
**Capesize Dispersion Intelligence & 5TC Price Prediction**

Quantitative trading tool for freight derivatives markets:
- 📍 **Vessel positioning analysis** using dispersion metrics
- 💹 **Forward Freight Agreement (FFA)** trading signals
- 🧪 **Granger causality tests** for predictive validation
- 📊 **Institutional metrics** (dynamic Sharpe ratio via FRED API)
- 🎲 **Walk-forward backtesting** with transaction costs

**Tech:** Python, Pandas, Statsmodels, Plotly, FRED API

---

## 💼 Professional Experience

**🌾 Global Agricultural Commodity Merchant** | *Graduate Trainee — Freight Trading Platform* | 2026 - Present  
*Geneva, Switzerland*
- Joined an 18-month rotational graduate programme on the dry bulk freight trading desk
- Coverage spans freight execution, trading and marketing across **Panamax / Supramax** (grains, oilseeds, minor bulks) and **Capesize** (industrial bulks)
- Building expertise in physical chartering, FFA derivatives, voyage economics (TCE), and supply-chain risk in a global agricultural value chain

**🏦 Robeco** | *Multi Asset Solutions, Summer Intern* | Jun 2025 - Aug 2025  
*Rotterdam, Netherlands*
- Developed **Python dashboard** to price index options and generate multi-leg strategies using live volatility skew and Greeks
- Structured **Carry & Roll-down trade** on AUD yield curve (IRS + bond futures) backed by RBA policy and commodity-linked inflation analysis
- Optimized **$750M position entry** with Head of Fixed Income Trading via algorithmic execution (TWAP), minimizing market impact
- Analyzed **Chinese A-Shares futures arbitrage**, evaluating A/H premiums through macro/technical analysis
- Collaborated with portfolio managers in **€4.5Bn AUM** quantitative framework, refining alpha generation via tracking error and market depth

**🏦 Société Générale CIB** | *IT Quant Intern* | Sep 2024 - Mar 2025  
*Paris, France*
- Optimized financial models (Python) for cross-asset trading desks (Commodities, Equities, FICC)
- Built automated **P&L attribution reports** (RP/PVA/IPV) enhancing transparency for traders and risk managers
- Led migration of sensitivity requests, coordinating with offshore IT teams for real-time delivery scalability

**🏦 BNP Paribas** | *ALM Treasury Intern* | Apr 2024 - Sep 2024  
*Paris, France*
- Managed liquidity, interest rate, and FX risk models executing IRS hedges (Python, VBA)
- Conducted **Basel III stress tests** for balance sheet flow forecasting
- Built statistical tool explaining subsidiaries' pricing behavior vs. rate dynamics

**📊 Ginjer AM** | *Causal Investment Strategy Research* | Sep 2023 - Mar 2024  
*Paris, France*
- Led team of 6 developing systematic BTC trading strategy with Random Forest forecasting
- Applied **Granger causality tests** to validate influential market factors (Python, Bloomberg)

---

## 🎯 Areas of Expertise

**Freight & Commodity Markets**  
Dry Bulk Freight (Capesize · Panamax · Supramax) • FFA Derivatives & Forward Curves • Voyage Economics (TCE) • Energy & Agricultural Commodities • Physical Trading Fundamentals

**Quantitative Methods**  
Machine Learning (XGBoost, Random Forest) • Stochastic Calculus • Black-Litterman Portfolio Optimization • Risk Management (VaR, Stress Testing) • Time Series Analysis • Granger Causality

**Trading Systems**  
Real-Time Market Intelligence Platforms • Algorithmic Trading • Backtesting Frameworks • AIS Vessel Tracking • Signal Generation • Performance Attribution

---

## 🚴 Beyond the Code

When I'm not building trading systems or analyzing freight markets, you'll find me:
- 🚴‍♂️ **Bikepacking across continents** (recently solo cycled 4,400 km from France to Greece)
- ⛷️ **Freeride skiing** in the Alps
- ✈️ **Exploring new cultures** (Asia, Africa, Americas, LATAM)
- 📚 **Reading commodity market literature** and tracking trade-flow developments

---

## 📫 Let's Connect

Always happy to exchange with fellow **commodity traders**, **quants**, and **freight market practitioners** — whether to discuss dry bulk fundamentals, FFA strategies, or the latest in market intelligence tooling.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Let's_Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/virgile-roumens)
[![Email](https://img.shields.io/badge/Send_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:virgile.roumens@gmail.com)

---

</div>
