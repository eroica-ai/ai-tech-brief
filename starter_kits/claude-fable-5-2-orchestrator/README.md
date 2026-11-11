# 🚀 Claude Fable 5.2 Cost-Efficient Orchestrator Starter Kit

Practical multi-agent orchestration boilerplate that unlocks **Anthropic's flagship Claude Fable 5.2** while **cutting token costs by over 90%**.

---

## 📌 Architecture Philosophy
- **Fable 5.2 (Architect / Orchestrator)**: Used strictly for root-cause analysis, complex reasoning, and structural code reviews.
- **Sonnet / Haiku (Workers)**: Handles repetitive code generation, unit test execution, and file I/O.
- ➔ Reduces overall token expenses from **\$40/M down to under \$5/M** compared to brute-force Fable queries.

---

## 🛠️ Quick Start

### 1. Setup
```bash
git clone https://github.com/eroica-ai/ai-tech-brief.git
cd starter_kits/claude-fable-5-2-orchestrator
pip install -r requirements.txt
cp .env.example .env
# Enter your ANTHROPIC_API_KEY in .env (or use --dry-run for zero-cost simulation)
```

### 2. Run Orchestrator
```bash
# Default run
python fable_orchestrator.py

# Custom coding task
python fable_orchestrator.py --task "JWT authentication with Redis blacklist" --out auth_service.py

# Zero-cost pipeline simulation & benchmark
python fable_orchestrator.py --dry-run
```

---



---
⭐ If this helped your workflow, please leave a **Star** on GitHub!
