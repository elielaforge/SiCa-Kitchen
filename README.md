<h1 align="center">🍳 SiCa Kitchen</h1>
<h3 align="center">AI-powered meal planning that saves time, cuts waste, and makes your kitchen smarter</h3>

<p align="center"><strong>Elie LAFORGE, Noé GERWIG, Yunan WANG</strong><br>
Albert School – 2024
</p>

---

## 🚀 Why SiCa Kitchen?

> 40% of French students were identified as having a “Western diet” with poor nutritional quality&#8203;:contentReference[oaicite:0]{index=0}.

And it’s no surprise. Students and professionals alike face the same daily cooking challenges:
- Lack of time
- Budget constraints
- Ingredient waste
- Culinary monotony

SiCa Kitchen is here to solve that — intelligently.

---

## 🧠 What It Does

SiCa Kitchen is an AI-powered meal planning and grocery assistant that lets users:

- 🧺 **Enter ingredients they already have**
- 🧠 **Receive personalized, budget-friendly recipe suggestions**
- 🛒 **Generate optimized shopping lists**
- ♻️ **Minimize food waste through smart ingredient scalability**
- 🍜 **Break routine with variety-enhancing recommendations**
- 🤖 **Chat interactively with the app to discover ideas, recipes, or meal plans**

It’s your personal sous-chef, but smarter.

---

## 🛠️ How It Works

- **Input**: User enters available ingredients (via chatbot or UI)
- **AI Matching**: Recipes are fetched from APIs and matched via NLP and cosine similarity
- **Optimization**:
  - Missing ingredients identified
  - Grocery list optimized to minimize cost (API pricing integration)
- **Scalability**: Recipes are adjusted based on servings, preferences, or existing pantry stock
- **Output**: Clean interface displays recipes, cost estimate, and next steps

---

## 💼 Business Value

### 🎯 Target Users
- Students with limited time & budget
- Professionals looking to streamline cooking
- Eco-conscious households

### 📈 Value Proposition

| Stakeholder       | Benefit                                                  |
|-------------------|----------------------------------------------------------|
| **Users**         | Save time, reduce waste, eat better                      |
| **Retailers**     | Boost relevant product sales via API & product matching |
| **API Providers** | Increased usage & data reach                             |
| **Investors**     | High ROI potential in the food-tech automation space     |

---

## 🧩 Tech Stack

- **Python / Streamlit / LLM integration**
- **OpenAI API** for smart NLP-based recommendation
- **Spoonacular + Kroger APIs** for recipes & pricing
- **PostgreSQL** for inventory management (planned)
- **Chatbot POC** using conversational AI

---

## 🧪 Proof of Concept

We developed a prototype notebook and chatbot that:
- Accepts natural language input (e.g. “I have potatoes and tuna”)
- Outputs:
  - List of possible dishes
  - Ingredients still needed
  - Cost-minimized shopping list

Check the `SiCa Kitchen Elie-Noe.ipynb` notebook for a hands-on demo.

---

## 📍 Roadmap Highlights

- ✅ MVP: Ingredient-based recommendations, chatbot, cost estimation
- 🔜 Next: API integration, UI buildout, recipe scaling, user onboarding
- 🧪 Future: Beta testing, analytics, performance optimization

---


## 📌 Risks & Opportunities

**Risks**
- API dependency (downtime, pricing changes)
- GDPR/data protection compliance
- Scaling costs of AI features

**Opportunities**
- Partner with grocery chains & health institutions
- Scale into dietary tracking, meal kit planning, delivery
- Expand to multilingual global markets



