
### ✅ File: `README.md`

````markdown
# 🎴 Balatro Strategy Simulator — CLI Edition

A terminal-based tool that helps you simulate, optimize, and explore strategies in the game **Balatro**.

> Predict your total score, explore joker and modifier synergy, and get intelligent recommendations on your best moves.

---

## 🧠 Features

- ✔️ Input and normalize poker hand types (e.g., "Full House", "Flush")
- ✔️ Add jokers, modifiers, and hand multipliers
- ✔️ Estimate final score based on active effects
- ✔️ Suggest optimal jokers or combos
- ✔️ Warn about unrecognized jokers/tags
- ✔️ Built-in typo/error correction for inputs
- ✔️ Future plans: AI recommendations, deck analysis, synergy explorer, game history

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/balatro-strategy-simulator.git
cd balatro-strategy-simulator
````

### 2. Set up a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🕹️ Running the Simulator

```bash
python main.py
```

You'll be guided through:

* Entering your **hand type**
* Inputting your **base score**
* Applying a **multiplier**
* Adding **jokers** and **modifiers**
* Receiving a **total score estimate** and strategic suggestions

---

## 💡 Example Use

```bash
Enter your poker hand type: Two Pair
Enter base score: 120
Enter multiplier: 3
Enter jokers used (comma-separated): Mime, Scary Face
Enter hand modifiers: Played Twice

🧮 Simulation Result
-------------------
Estimated Score: 1080
Suggested Jokers: DNA, Bull
Recommendation: Focus on doubling plays and combo jokers
```

---

## 📁 Project Structure

```
balatro-strategy-simulator/
├── core/
│   ├── simulator.py         # Scoring engine + strategy logic
│   ├── normalize.py         # Input normalization & aliases
│   └── data/                # Predefined jokers, modifiers, hands
│
├── main.py                  # CLI interface
├── requirements.txt         # Python dependencies
└── README.md                # You're here!
```

---

## ⚠️ Known Limitations

* Does not simulate full decks (yet)
* Joker/modifier synergy is rule-based, not AI-enhanced
* Only CLI mode (no GUI)

---

## 🔮 Roadmap

* [ ] 💡 AI-powered strategy recommendations
* [ ] 🔁 Combo chaining detection
* [ ] 🧠 Deck analyzer
* [ ] 🧪 Sandbox mode (simulate multiple outcomes)
* [ ] 🗃️ Game history + save/load
* [ ] 🎯 Full synergy explorer (joker ➜ best hand suggestions)

---

## 👨‍💻 Contributing

Pull requests are welcome! Open an issue first to discuss your ideas.

---

## 📝 License

MIT License

---

## ❤️ Credits

Inspired by the card roguelike game **Balatro** by LocalThunk.

Made with love (and a lot of discarded flushes).

```

---

Would you like a matching `requirements.txt`, `.gitignore`, or sample data files too? I can scaffold those next.
```
