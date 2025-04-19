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
- **Backend:** Python Flask 
- **Database:** MySQL 
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
![file_2024-12-07_18 50 29](https://github.com/user-attachments/assets/3b04dba9-5b92-4bb9-ab81-ef857f0ed428)
![file_2024-12-07_18 52 44](https://github.com/user-attachments/assets/52bad324-c671-4da7-b1e3-f448f70d622c)
![file_2024-12-07_18 58 31](https://github.com/user-attachments/assets/0f012b8b-81e5-43dd-99a1-96d30b34fdc4)
![file_2024-12-07_19 00 31](https://github.com/user-attachments/assets/b25ffa03-4687-4d19-b2a7-eea5e9cdfe8a)
![file_2024-12-07_19 01 31](https://github.com/user-attachments/assets/9b824249-3361-4935-baab-43d3a8d18fcf)



## 📁 Project Structure

feed-ration-formulation/
│
├── app.py                        # Main backend (Flask) application
├── requirements.txt              # Python dependencies
├── README.md                     # Project documentation
│
├── public/
│   └── index.html                # Entry point / landing page (static)
│
├── static/
│   ├── css/
│   │   └── style.css             # Custom styles
│   └── images/
│       ├── cow2.jpeg
│       ├── cow3.jpg
│       ├── img.jpg
│       └── nutrition.jpg        # Used across templates
│
├── templates/
│   ├── home.html                 # Main dashboard/homepage
│   ├── animal_requirements.html # Form for animal details
│   ├── feed_options.html        # Feed ingredient selection
│   ├── cost_estimation.html     # Result page with optimized cost output
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

