# Optimizing Short Volatility Strategies

**Authors**:  
- Joudy Benkaddour (FIC ETD Product R&D, Eurex)  
- Leon von Essen (FIC ETD Product R&D, Eurex)  

## 📝 Overview

This project explores how to enhance returns from fixed income ETFs through short volatility strategies, such as selling calls and puts on a U.S. Treasury Bond ETF (20+ years maturity). The strategy aims to systematically capture volatility risk premia while managing downside through various techniques like stop-losses, strike selection, and selling frequency. 

## 📊 Methodology

- **Underlying Asset**: iShares USD Treasury Bond 20+yr (ODTL) ETF  
- **Strategy Components**: Covered calls, protective puts, daily/monthly selling, strike variation (ITM/ATM/OTM), target yield calibration, and stop-loss thresholds  
- **Backtesting Period**: 2021–2023 across three market scenarios: positive, neutral, and negative  

## 📈 Key Findings

- **Daily selling** offers smoother cash flows and better Sharpe ratios than monthly selling  
- **OTM options** perform best in volatile environments; **ATM** strikes provide more stable alpha  
- **Stop-loss** mechanisms significantly improve alpha and reduce drawdowns  
- **Variable weight strategies** outperform fixed strike selections in volatile markets  
- Combining **calls and puts** enhances alpha, especially in negative markets  

## 📂 Contents

- `Short Volatility Strategies 5.1.pdf`: Complete presentation with results, graphs, and scenario-based insights
