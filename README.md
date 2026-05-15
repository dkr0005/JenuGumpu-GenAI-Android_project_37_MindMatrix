# Jenu-Gumpu – GenAI Powered Honey Producer’s Collective

## 📌 Project Overview

**Jenu-Gumpu** (Honey Group) is an Android-based AgriTech application developed under the **MindMatrix VTU Internship Program**. The app is designed to empower tribal and rural honey hunters by transforming their local harvest into a recognized brand.

By utilizing **Generative AI**, the platform bridges the gap between forest-dwelling communities and the retail market. It provides tools for quality grading, price transparency, and collective stock management, ensuring hunters can command fair market prices and bypass exploitative middlemen.

---

# 🚀 Features

* **Harvest Log:** Digital ledger to record the date, precise location, and quantity of honey collected.
* **GenAI Grading Tool:** A visual and AI-assisted guide to check honey quality (color and moisture checks) using simulated tests.
* **Real-time Price Monitor:** Comparison tool showing real-time retail prices vs. local wholesale prices in major cities.
* **Batch Tracker:** Automated "Batch ID" assignment for every honey jar to ensure full traceability from forest to table.
* **Profit Calculator:** Integrated logic to show actual earnings after accounting for filtering and logistical costs.
* **Collective Stock View:** A unified dashboard showing the sum of all individual entries for better negotiation with large retailers.
* **Multilingual Support:** Full UI availability in **Kannada** to ensure accessibility for rural users.

---

# 🛠️ Technologies Used

* **Kotlin & Jetpack Compose:** Modern Android development stack for a responsive and intuitive user interface.
* **Gemini AI (GenAI) Integration:** Used for the "Honey Grading Guide" to analyze floral sources and provide sustainable harvesting advice.
* **Room Database:** Local SQLite abstraction for secure, offline-first storage of harvest history and batch records.
* **Material 3 & CardViews:** Implementation of specialized CardViews for distinct honey grades and easy-to-read dashboards.
* **Localization (L10n):** Android string resource management for native Kannada language support.

---

# 📱 Application Workflow

1.  **Harvest Entry:** User logs the quantity and selects the **Floral Source** (e.g., Coffee Blossom, Wildflower).
2.  **Quality Check:** The GenAI Grading Tool assists the user in assessing moisture and color.
3.  **Batching:** System generates a unique **Batch ID** for the jars.
4.  **Price Check:** User compares the city retail price against local wholesale offers.
5.  **Collective Sync:** Individual logs are aggregated to show the "Total Collective Stock" for the group.
6.  **Sale:** The group negotiates better prices with retailers based on verified quality and volume.

---

# 💹 Business Logic (Profit Calculator)

The app uses the following formula to calculate the "Value Add" for the honey hunters:

$$Profit = (Q \times P_{retail}) - (Q \times P_{wholesale} + C_{filter})$$

Where:
* $Q$ = Quantity of honey
* $P_{retail}$ = Current market price in cities
* $P_{wholesale}$ = Price offered by middlemen
* $C_{filter}$ = Cost of filtering and packaging

---

# 🎯 Objectives & Impact Goals

* **Tribal Empowerment:** Improving the livelihoods of forest-dwelling communities through direct market access.
* **Organic Growth:** Promoting chemical-free, "Forest-to-Table" products with verified traceability.
* **Sustainable Harvest:** Providing AI-driven guidelines on how to harvest honey without harming bee colonies.
* **Price Transparency:** Ending the exploitation of rural hunters by providing real-time market data.

---

# 🌍 SDG Mapping

### SDG 1 – No Poverty
By eliminating middlemen and increasing the "Value Add" knowledge, Jenu-Gumpu directly increases the income of marginalized tribal communities.

### SDG 8 – Decent Work and Economic Growth
The app promotes self-employment and formalizes the informal honey-hunting trade into a structured collective.

### SDG 12 – Responsible Consumption and Production
Through sustainable harvest guidelines and traceability, the project ensures the protection of forest ecosystems.

---

# 📂 Project Structure

* **UI Components:** CardView-based grading system and Kannada localized layouts.
* **Harvest Module:** Logic for logging, Batch ID generation, and Room DB persistence.
* **GenAI Engine:** Integration for moisture simulation and sustainable harvesting tips.
* **Economics Engine:** Real-time price monitoring and Profit Calculator logic.

---

# 👨‍💻 Developed By

**Devanshu Kumar** **USN:** 1MV22CS192  
**College:** Sir M Visvesvaraya Institute of Technology  
**Department:** Computer Science and Engineering  
**Internship Project:** MindMatrix VTU Internship Program (Project ID: 37)

---

# 📄 License

This project is developed for academic requirements and as part of the MindMatrix VTU Internship Program.
