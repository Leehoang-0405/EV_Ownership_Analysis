# EV_Ownership_Analysis

# ⚡ Electric Vehicle Ownership Analysis – Sustainable Futures Research Centre  

## 🌟 Highlights  
- Analysed survey data from **102 Australian EV owners** to understand travel patterns, charging habits, and cost savings.  
- Found **metro EV owners drive ~793 km more annually** than regional owners.  
- Identified **significant differences** in fuel cost savings by household type, with couples with children saving the most.  
- Observed **positive shifts in public attitudes** towards EV charging infrastructure between 2022 and 2023.  
- Provided **data-driven insights** for EV policy, infrastructure design, and consumer engagement.  

---

## ℹ️ Overview  
This project was developed for the **Sustainable Futures Research Centre** as part of **MIS771 – Descriptive Analytics and Visualisation** at Deakin University.  
The study explores **electric vehicle (EV) ownership in Australia**, focusing on travel distances, household savings, towing usage, and charging behaviour.  

Using inferential and descriptive analytics, the project aimed to answer key research questions from the Centre’s Director, including:  
- Do metropolitan EV owners travel further than regional owners?  
- Are towing behaviours different across localities?  
- Do household types experience varying levels of fuel savings?  
- Does charging frequency depend on the reason for purchasing an EV?  
- Has public attitude toward charging infrastructure changed over time?  

---

## 📈 Key Analytical Components  

### **1. Travel Distance Comparison**  
- Metro owners travel **≈ 12,091 km/year**, regional owners **≈ 11,298 km/year**.  
- Independent t-test confirms metro drivers travel **significantly farther** (p < 0.05).  
- Finding suggests **urban EV users** take more short, frequent trips due to higher accessibility to charging stations.  

### **2. EV Towing Usage**  
- **55 %** of metro owners and **71 %** of regional owners use EVs for towing.  
- Z-test found no statistically significant difference, implying the variance is likely random.  

### **3. Fuel Cost Savings by Household Type**  
- Average annual savings:  
  - Couples with Children – $3,653  
  - Couples without Children – $3,465  
  - Single Parents – $3,208  
  - Single Persons – $3,383  
- One-way ANOVA shows **significant differences** (p < 0.05), driven mainly by couples with children vs single parents.  

### **4. Charging Frequency vs Motivation**  
- Chi-square test found **no significant difference** in charging frequency across purchase motivations (economic, environmental, fuel security, health, technology).  
- Indicates charging habits are **consistent across motivations**.  

### **5. Locality × Trip-Type Interaction**  
- Two-way ANOVA found **interaction effects** between locality and trip type.  
- For **private trips**, regional owners travelled farther; for **work trips**, metro owners did.  
- No locality difference for holiday trips.  

### **6. Public Attitude toward Charging Infrastructure (2022 → 2023)**  
- Mean attitude improvement = **+1.27 points**, 95 % CI [ 0.41 , 2.15 ].  
- Z-test confirms **significant positive shift** (p < 0.05).  
- Indicates growing confidence in national EV-charging initiatives.  

---

## 💡 Insights & Implications  
- **Infrastructure Planning:** Higher metro travel intensity highlights the need for dense urban charging networks.  
- **Policy Design:** Couples with children benefit most financially → targeted incentives could maximise adoption.  
- **Market Education:** Positive attitude trends suggest readiness for broader EV integration programs.  
- **Behaviour Understanding:** Regional vs metro trip differences can guide regional transport planning.  

---

## 🧩 Limitations  
- Small sample (n = 102) limits generalisability.  
- Self-reported travel data may include recall bias.  
- Future work should expand datasets and integrate telemetry data for higher accuracy.  

---

## 🧰 Tools & Techniques  
- **Microsoft Excel** – Data cleaning, visualisation, inferential testing.  
- **Statistical Methods:** t-test, Z-test, One-way ANOVA, Two-way ANOVA, Chi-square test.  
- **Data Visualisation:** Histograms, boxplots, clustered bar charts for pattern exploration.  
- **Confidence Level:** 95 %, α = 0.05.  

---

## 👤 Author  
**Ba Huy Hoang Le**  
📧 huyhoangle040502@gmail.com  
---

## 📜 Acknowledgement of AI Use  
Some grammar refinement and structural editing were supported by AI tools.  
All statistical analyses, interpretations, and report content were independent
