<div align="center"> 
  
# Algorithmic-Trading-Strategy-for-Ultra-Bond-UB-
</div>

## Overview
This project aims to develop a high performance trading algorithm designed for the Ultra Bond (UB) futures market. The strategyis based on Smart Money Concepts (SMC), volume spikes, time-based execution windows, economic news filtering basics elements that I have already used for passing rigorous propfirm challenge. 
The core innovation lies in the integration of multiple AI agents, each responsible of replicating key elements of discretionary trading. The goal is to progressively evolve the systemfrom a semi-automated assistant to a fully autonomous algorithm.
This repository documents the design, architecture, agent roles and the logic of the system. The algorithm is under **under active development** and will be refined in progressive stages.

## AI Agents and Their Interactions

### 🔹 Core AI Agents
- **SMC Agent:** Identifies key supply and demand zones, liquidity pools, and smart money footprints.  
- **Volume Spike Agent:** Detects abnormal volume peaks signaling potential reversals or breakouts.  
- **News Monitoring Agent:** Filters out trading during high-impact economic events to reduce slippage risk.  
- **Order Flow Agent:** Analyzes real-time order book dynamics to enhance entry and exit precision.  
- **Execution Agent:** Responsible for timely, efficient order placement and management to minimize slippage and execution risk.  

### 🔹 Additional Intelligent Agents
- **Position Sizing Agent:** Applies game-theory-based probability calculations to optimize position sizes.  
- **Noise Filtering Agent:** Utilizes statistical filtering, signal processing, multi-timeframe analysis, and machine learning to reduce market noise.  
- **Market Regime Detector Agent:** Classifies market conditions to ensure robustness and adaptability of the strategy.  


### 🔄  Agent Interaction Overview

The agents continuously share data and insights. For example, the Order Flow Agent refines signals from the SMC and Volume Agents, while the Market Regime Detector adjusts parameters used by all agents depending on current market conditions. The Execution Agent acts on combined signals ensuring smooth order management, and the Noise Filtering Agent helps reduce false signals before decisions are made.



## 🛠 Development Stages

1. **Semi-Automatic Version:** Initial implementation with manual trade execution and basic agent support.  

2. **Partial Automation:** Algorithm suggests trades with human oversight for entry and exit.  

3. **Full Automation with Feedback Loop:** Fully automated execution with continuous performance feedback and self-adjustment.  

4. **Cloud/Cluster Optimization:** Scalability improvements via cloud computing or distributed clusters.  

5. **Future Multi-Asset Extension:** Adapting the core algorithm to correlated markets for portfolio diversification.  



## 🧩 Pattern Recognition Agents

Specialized AI modules trained to detect short-term recurring price and volume patterns, order flow signatures, and liquidity shifts to anticipate probable market moves in real-time.



## 🛡️ Overfitting and Performance Agent

A dedicated agent monitors the algorithm’s performance metrics, detects signs of overfitting during training and live deployment, and implements cross-validation and regularization techniques to maintain model robustness.



## ⏱️ Advantage of Defined Trading Time Window

Trading is restricted to a two-hour time window (14:30–16:30 Spain time), strategically chosen to capture one hour before and one hour after the US market open. This period provides high liquidity, volatility, and reliable price action patterns. **This temporal window also helps concentrate the intelligence of the AI agents on the most relevant part of the session** 

## 🧬 Machine Learning Roadmap for AI Agents

The algorithmic system will progressively integrate machine learning (ML) capabilities across its agents to enhance performance, adaptability, and robustness.

### Phase 1: Local ML per Agent  
Each agent will incorporate dedicated machine learning models tailored to its unique role:  
- **Pattern Recognition Agent:** Deep learning models (CNNs, LSTMs) to identify complex price and volume patterns.  
- **Noise Filtering Agent:** Statistical filters combined with ML classifiers (SVM, Random Forests) and multi-timeframe analysis to separate signal from noise.  
- **Sizing Agent:** Probabilistic modeling and reinforcement learning to dynamically size positions based on risk and expected returns.  
- **Market Regime Detector Agent:** Unsupervised clustering and classification models to detect market regimes and adapt strategy accordingly.  
- **Order Flow Agent:** Sequence models and anomaly detection to interpret order book dynamics for optimal entry/exit timing.  
- **News Filter Agent:** Natural language processing (NLP) models to analyze economic news sentiment and filter high-impact events.  
- **Execution Agent:** Adaptive ML-driven execution algorithms to minimize slippage and transaction costs.

This distributed ML approach ensures each agent specializes in its domain while enabling improvements.

### Phase 2: Agent Coordination  
Define clear communication protocols and data exchange between agents to allow information sharing and combined decision making. 

### Phase 3: Centralized Meta-Agent  
Develop a meta-agent that aggregates outputs from all agents, learns inter agent relationships, and optimizes overall trading decisions. 

### Phase 4: Continuous Improvement and Scalability  
Expand datasets, test across multiple correlated markets, and iteratively improve ML models for better generalization and robustness.


## 🤝 Contribution & Contact

Contributions are currently not accepted to maintain confidentiality.  
For collaboration inquiries (teamwork or partnerships) or more information, please contact:  

**Cheick Paul Gbon Coulibaly**  
Email: cheick.coulibaly@stonectp.com



---

## License

This project is licensed under a custom license. Please refer to the `LICENSE` file for details.

