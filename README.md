<h1 style="font-family: Arial, sans-serif; font-size: 36px; color: #4F46E5; display: flex; align-items: center; border-bottom: 3px solid #4F46E5; padding-bottom: 5px;">
    <img src="screenshots/hero.jpg" alt="FORSEEN Logo" style="width: 50px; height: 50px; margin-right: 15px; object-fit: cover;">
    FORSEEN: Data-Driven Forecasting for DTC Brands 🔮
</h1>

FORSEEN is an intelligent, AI-powered platform built to help Direct-to-Consumer (DTC) businesses forecast sales, optimize inventory, collaborate with compatible brands, and make smarter decisions using real-time + historical data.

Built with **React**, **Tailwind**, **Supabase**, **Snowflake**, and a robust **RAG architecture** powering insights, forecasts, and strategy generation.

---

## Tech Used 🧑‍💻

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge\&logo=react\&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge\&logo=tailwindcss\&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge\&logo=supabase\&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge\&logo=snowflake\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_AI-8A2BE2?style=for-the-badge)

---

## Core Features ⚡

* 📊 **Smart Sales Forecasting**
  Detects trends, predicts demand, and alerts businesses about overstock and understock.

* 🔁 **Client Matching Engine**
  Connects overstocked businesses with understocked partners for inventory balancing.

* 🤖 **AI Assistant (RAG-Powered)**
  Answers sales questions, builds marketing plans, and provides personalized strategic advice.

* 🎯 **Recommendation Engine**
  Suggests best-selling items and cross-client strategies proven to generate results.

* 🧠 **BI & Historical Analytics**
  Snowflake-powered dashboards combining real-time and aggregated multi-client data.

---

## Screenshots 📸

<br>
<img src="screenshots/hero.jpg" alt="Hero Section" width="70%"/>

**Landing / Hero:** High-level overview of the platform’s value.

<br>
<img src="screenshots/login.jpg" alt="Login Screen" width="70%"/>

**Login:** Clean and simple authentication for business owners.

<br>
<img src="screenshots/calendar.jpg" alt="Sales Calendar" width="70%"/>

**Sales Calendar:** Visualize trends and demand across time.

<br>
<img src="screenshots/exchange.jpg" alt="Inventory Exchange" width="70%"/>

**Inventory Exchange:** Peer-to-peer product balancing between DTC brands.

<br>
<img src="screenshots/map.jpg" alt="Map View" width="70%"/>

**Market Map:** Geographic matching and trend visualization.

<br>
<img src="screenshots/pricing.jpg" alt="Pricing Plans" width="70%"/>

**Pricing:** Clear subscription tiers.

<br>
<img src="screenshots/about.jpg" alt="About Page" width="70%"/>

**About:** Mission, purpose, and background.

---

## Data Architecture 🏗️

```plaintext
Supabase (Recent Data, Real-time)
        │
        ├── Incremental Sync
        ▼
Snowflake (Historical + Cross-Client Data)
        │
        ├── RAG Retrieval Layer
        ▼
AI Models (Forecasting, Marketing Strategies, Q&A)
```

* **Supabase** → Fast-access recent memory
* **Snowflake** → Scalable warehouse for long-term BI
* **RAG Layer** → Retrieves the right chunks of data
* **AI Models** → Generate forecasts, strategies, insights

---

## Project Structure 📂

```plaintext
src/
├── components/       # UI components
├── pages/            # Screens and routes
├── hooks/            # Forecasting, RAG, logic
├── services/         # AI, recommendations, API
├── db/               # Supabase & Snowflake utils
└── styles/           # TailwindCSS

ai/
├── forecasting/      # Demand prediction models
├── rag/              # Retrieval system
└── strategies/       # Marketing & sales generators
```

---

## Setup & Development 🛠️

1. **Clone:**

   ```sh
   git clone https://github.com/mohaneddz/Dev-Camp.git
   cd forseen
   ```

2. **Install:**

   ```sh
   pnpm install
   ```

3. **Run dev:**

   ```sh
   pnpm run dev
   ```

4. **Configure environment (.env):**

   * Supabase URL & keys
   * Snowflake credentials
   * Model endpoints

---

## Roadmap 🗺️

### Phase 1 — MVP

* [x] Forecasting
* [x] Alerts
* [x] RAG Assistant
* [x] Dashboard


---

## License ⚖️

MIT License — see `LICENSE`.

---

## Contact 📬

**GitHub:** mohaneddz
**Email:** [mohaned.manaa.dev@gmail.com](mailto:mohaned.manaa.dev@gmail.com)