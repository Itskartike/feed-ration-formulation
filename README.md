# 🐄 Feed Ration Formulation for Indian Farmers

## 📌 Overview

**Feed Ration Formulation** is a web-based platform designed to assist Indian farmers in determining the optimal and cost-effective diet for their livestock (Cattle, Poultry, Goat). This system uses linear programming techniques to generate a feed plan that meets daily nutritional requirements while minimizing overall feed cost.

The platform also provides valuable insights, government scheme updates, SMS notifications (future), and educational resources to empower farmers.

---

## 🚀 Features

- ✅ **Nutritional Requirement Calculator** – Determine the daily dietary needs for cattle, poultry, or goat.
- ✅ **Cost Optimization** – Uses Linear Programming to suggest the most cost-effective feed combination.
- ✅ **Feed Ingredient Database** – Preloaded with common feed ingredients and their nutritional values.
- ✅ **Farmer-Friendly UI** – Simple interface with support for regional language labels (future).
- ✅ **Government Scheme Updates** – Informative section on current subsidies and benefits for farmers.
- ✅ **Learning Hub** – Guides and tutorials on livestock nutrition and feeding practices.
- 🔜 **SMS Alerts** – (Planned) Send feed suggestions and scheme updates directly to farmer phones.

---

## 🧮 Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js / Python Flask (depending on final implementation)
- **Database:** MongoDB / Firebase / MySQL (based on deployment)
- **Optimization:** PuLP (Python Linear Programming Library) or similar
- **Hosting:** Render.com (Database & Web App)

---

## 🔍 How It Works

1. **User Input:** Farmer selects animal type and provides animal details (age, weight, productivity).
2. **Requirement Calculation:** System calculates nutritional needs (Protein, Energy, Fiber, etc.)
3. **Ingredient Selection:** System presents available feed options.
4. **LP Solver:** Linear programming model finds the lowest-cost mix satisfying all nutrition constraints.
5. **Output:** User receives detailed feed plan and cost estimate.

---

## 📸 Screenshots

*(Add images of your UI if available)*

---

## 📁 Project Structure

```
feed-ration-formulation/
│
├── index.html             # Landing page
├── calculate.html         # Nutrient calculator & feed input
├── result.html            # Optimized feed plan result
│
├── css/
│   └── style.css          # Styling
│
├── js/
│   └── script.js          # Logic and interactivity
│
├── python/
│   └── optimizer.py       # LP Solver using PuLP (optional)
│
├── data/
│   └── feed_db.json       # Sample feed ingredients & nutrient values
│
└── README.md              # Project info
```

---

## 🛠 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/feed-ration-formulation.git
   cd feed-ration-formulation
   ```

2. Run locally (if Python backend used):
   ```bash
   pip install -r requirements.txt
   python app.py
   ```

3. Open `index.html` in browser if frontend-only version.

---

## 📈 Future Scope

- 🌐 Multi-language support for rural areas
- 📱 Android app version
- 📤 SMS-based feed plan delivery
- 📚 AI-based recommendation system
- 🧮 Integration with government data on feed prices

---

## 🧑‍💻 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

---

## 📃 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👨‍🌾 Built For

- Indian livestock farmers
- Agriculture students and researchers
- NGOs and organizations in animal husbandry

---

## 🤝 Acknowledgements

- PuLP Python Library
- Indian Council of Agricultural Research (ICAR) – For reference nutrition data
- College Faculty & Mentors for guidance
```

---

Let me know if you'd like it personalized with your name, team members, college, or specific deployment link!
