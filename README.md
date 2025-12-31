##  Motivation

Medication errors often occur not because people forget to take medicines, but because they take them **incorrectly**—with wrong food, wrong timing, or without understanding interactions. Existing apps focus on reminders, not safety.

MediAware is built to bridge this gap by providing **context-aware medication guidance** using AI, OCR, and feedback-driven improvement.

---

##  Project Goals

- Provide safe, understandable medication guidance
- Reduce food–drug interaction risks
- Automate prescription understanding via OCR
- Learn from user feedback to improve advice quality
- Keep the system transparent and auditable

---

##  How It Works (End-to-End)

1. User inputs medication manually or uploads prescription
2. OCR extracts medication details (name, dose)
3. Drug name is validated using fuzzy matching
4. Drug–food interaction rules are applied
5. AI generates structured safety advice
6. User feedback is analyzed via sentiment model
7. Dashboard aggregates insights in real time

---

##  Design Principles

- **Safety-first AI**: AI assists, never prescribes
- **Explainability** over black-box output
- **Modular architecture** for easy extension
- **Minimal dependencies** for reliability
- **Hackathon-ready but production-aware**

---

##  Disclaimer

MediAware does **not** provide medical diagnosis or replace professional medical advice.

All recommendations are informational and meant to support awareness. Users must consult licensed healthcare professionals before making medical decisions.

---

##  Future Enhancements

- Drug–drug interaction detection
- Multi-user authentication
- PostgreSQL migration
- Mobile app support
- Reminder and refill tracking
- Multilingual OCR and NLP
- Offline mode with cached rules

---

##  Limitations

- OCR accuracy depends on image quality
- Drug database requires manual updates
- English language only
- Not designed for emergency or critical-care usage
- SQLite not suitable for high-concurrency production

---

##  Why This Project Matters

This project demonstrates:
- Real-world AI system design
- OCR + NLP + backend integration
- Responsible AI boundaries
- Feedback-driven improvement loops
- Practical healthcare-oriented software engineering

---

## 📥 Clone the Repository
```bash
git clone https://github.com/HESleagacy/MediAware.git
cd MediAware
