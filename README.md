# 🧠 Agentic Venue Planning (CrewAI Notebook Prototype)

This Jupyter notebook demonstrates a basic **CrewAI multi-agent system** for identifying and reviewing potential venues for a conference in Las Vegas.

It simulates a two-agent workflow:
- 🔍 **Venue Finder Agent:** searches online to gather top 5 venues
- ✅ **Venue QA Agent:** evaluates the venues for quality, amenities, and suitability

---

## 🚀 Try It in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/YOUR_USERNAME/agentic-venue-notebook/blob/main/Building_Crew.ipynb)

---

## 🧰 Stack

- **CrewAI**: LLM-powered multi-agent framework
- **SerperDevTool**: (Search tool – API key required)
- **Python**: Notebook format for simplicity

---

## ⚙️ Requirements

1. A **Serper.dev API key** for Google search
2. (Optional) An **OpenAI API key** for advanced agent prompts

To run locally:
```bash
pip install crewai crewai[tools]
