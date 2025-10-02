# ⚾ MLB Team Performance Analysis

### 📌 Big Question  
Which team statistics most strongly correlate with wins in Major League Baseball (MLB)?

---

## 📊 Dataset  
**Source:** Baseball-Reference.com  
**Scope:** 2021–2022 MLB regular seasons  
**Size:** 60 rows × 56 columns (team-year averages)  
**Teams:** 30 teams × 162 games per season  
**Tools:** SAS Enterprise Guide 8.3, SAS Enterprise Miner 15.2  

---

## 🔬 Methods  
- Multiple Linear Regression (backward elimination)  
- Decision Tree Analysis  
- Cluster Analysis (K-means)  
- ANOVA (Analysis of Variance)  
- StatExplore (descriptive analytics and visualization)  

---

## 📈 Key Findings  

### Regression  
- **Most significant predictors (|β| > 0.5)**  
  - ✅ Positive: Runs (0.58), Slugging % (1.11)  
  - ❌ Negative: Runs Against (-0.58), Home Runs (-0.79), Hits (-0.51)  
- Adjusted **R² = 0.9967** → near perfect model fit  

### Decision Tree  
- Runs ≥ 4.55 AND Runs Against < 4.25 → ~97 wins (playoff level)  
- Runs Against ≥ 4.8 → ~67 wins  

### StatExplore & Clusters  
- **Top Offensive Metrics:** Slugging %, Home Runs, Walks (BB)  
- **Top Defensive Metrics:** Hits Allowed, HR Allowed, Batters Faced  
- Clusters confirmed high win teams excel in these areas  

### ANOVA  
- **F = 920.9, p < 0.0001** → Model highly significant  
- Residual error < 0.3%  

---

## ✅ Conclusions & Recommendations  
- **Winning Formula:** High Slugging %, strong run production, and minimizing Runs Against  
- **Team Strategies:**  
  - If scoring <4.55 runs per game → boost SLG, HR, BB  
  - If allowing ≥4.25 runs per game → strengthen pitching (reduce Hits/HR allowed, increase BF)  
- **Suggested Free Agents (2024):**  
  - Offense: Shohei Ohtani, J.D. Martinez  
  - Defense: Kyle Gibson, Lucas Giolito  

---

 
