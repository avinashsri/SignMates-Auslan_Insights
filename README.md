# SignMates — Auslan Insights & Data Analysis Project

A data-driven exploration of Auslan (Australian Sign Language) users, visual storytelling, and accessible design choices behind **SignMates**, an educational platform created to support Deaf awareness and Auslan learning for primary school students.

This repository showcases:

- Data analysis & visualisations  
- Demographic insights about Auslan users  
- UI/UX elements of the SignMates learning platform  
- Data Management Plan (DMP)  
- Data wrangling & cleansing process  
- Educational reasoning behind design decisions  


---

# Repository Structure
SignMates-Auslan-Insights/
│
├── docs/
│ └── Data Management Plan.pdf
│
├── visualisations/
│ ├── signmates_homepage.png
│ └── auslan_users_map.png
│
├── README.md
└── VISUALISATIONS.md

---

# Visualisation Gallery

Full gallery available here:  
👉 **[VISUALISATIONS.md](VISUALISATIONS.md)**

Includes:

- SignMates Homepage UI  
- Auslan Users by State & Territory map  
- Additional educational design elements  

---

# Data Sources Used

These datasets were referenced in the Data Management Plan and informed iterations of design, demographic analysis, and accessibility reasoning.

| Dataset | Type | Source | License |
|--------|------|---------|---------|
| Auslan Cultural Diversity (ABS) | CSV | ABS Census Data | ABS Copyright |
| PB Hearing Data | XLSX | NDIS Hearing Impairment Dashboard | CC BY 4.0 |
| National Health Survey | XLSX | Australian Bureau of Statistics | ABS Copyright |
| Burden of Disease Data | CSV | ACT Government Open Data | CC0 1.0 |
| Auslan Daily Dataset | Images/Videos | UQ CVLab | CC BY 4.0 |
| Auslan Fingerspelling Dataset | Images | Kaggle | CC0 |
| Word Validation Dataset | CSV | Kaggle | CC0 |

> Full details available inside the **Data Management Plan**.

---

# Data Wrangling & Cleansing Summary

The project involved multiple iterations of data cleaning from the Cultural Diversity dataset, PB Hearing dataset, and word-validation dataset.

### **1. Cultural Diversity Data — Auslan by State**
- Selected “LANGUAGE USED AT HOME BY STATE AND TERRITORY (Table 5)”
- Filtered for the row labelled **“Auslan”**
- Converted values to integers  
- Extracted the following states:
  - NSW, VIC, QLD, SA, WA, TAS, NT, ACT
- Verified totals and cleaned column names

### **2. PB Hearing Data (NDIS)**
- Selected key sheet: **24_Outcome_children**
- Removed non-data header rows
- Renamed columns for clarity
- Converted percentage fields to float
- Removed placeholder columns
- Exported as a clean CSV for further analysis

### **3. Word Validation Dataset**
- Removed duplicates
- Trimmed whitespace
- Filtered empty or invalid entries

These steps ensured a **clean, analysis-ready dataset** for generating insights such as the Auslan user distribution map.

---

# Key Insights & Findings

### 1. **Victoria & Queensland have the highest Auslan user populations**
These states showed significantly higher Auslan usage compared to others, shaping where educational content could be most impactful.

### 2. **NT & Tasmania hold the smallest Auslan user groups**
Useful for understanding accessibility gaps and areas requiring community engagement.

### 3. **Visual design choices were informed by demographic distribution**
UI/UX components in SignMates align with:
- simple colour palettes  
- primary-school readability levels  
- Deaf accessibility principles  

### 4. **LocalStorage enables child-friendly learning continuity**
No accounts, no logins — progress is stored privately and safely on the learner’s device.

### 5. **Educational flow is mapped to real-world Auslan learning needs**  
Games unlock only when comprehension meets thresholds, reinforcing retention.

---

# UI / UX Design Rationale

The SignMates homepage and interactive tools were designed to be:

- child-friendly  
- accessible to Deaf/Hard of Hearing users  
- visually motivating  
- progress-based  
- game-supported  

Screenshots included in the repo help communicate this design.

---

# Data Ethics, Privacy & Security

The system is designed with:

- No personal data collection  
- Local-only storage for learning progress  
- Compliance with dataset usage licenses  
- Clear separation between open data and proprietary assets  

Full ethics & privacy documentation is included in the DMP.

---

# Skills Demonstrated

This project highlights:

### **Data Analysis**
- Data cleaning, wrangling, validation  
- Reading multi-sheet Excel datasets  
- Handling government open data  
- Creating demographic visualisations  

### **Data Management & Documentation**
- Structured DMP  
- Metadata handling  
- Backup planning  
- Data lifecycle understanding  

### **UX/UI & Educational Design**
- Visual language construction  
- Accessibility & inclusivity principles  
- Figma/screenshot integration  

### **Clean Repository Practices**
- Clear folders  
- Markdown documentation  
- Recruiter-friendly presentation  

---

# 🔗 Project Files

- 🎓 **Data Management Plan** (PDF) – full analysis, ethics, wrangling steps  
- 🖼 **Visualisation Gallery** – screenshots of UI and data outputs  
- 📘 **README** – project overview and case study  

---

# 🔍 Author

**Avinash Sridhar**  
Master of Data Science, Monash University  
Australia  

This project was created as part of the **Monash FIT5120 Industry Experience Studio** unit (Team TP32 HexaRangers).

---

# 📌 License
Open for educational and portfolio purposes under the MIT License.

