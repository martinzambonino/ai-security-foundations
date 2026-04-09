# AI Security Foundations

![GitHub Actions Status](https://img.shields.io/github/actions/workflow/status/martinzambonino/ai-security-foundations/ci.yml?branch=main)
![License](https://img.shields.io/github/license/martinzambonino/ai-security-foundations)

## What It Does

An educational exploration of security challenges, threats, and defenses in Artificial Intelligence and Machine Learning systems:

- **Adversarial Attacks:** Implementations of FGSM, PGD, and other perturbation techniques against image classifiers to understand model robustness.
- **Differential Privacy:** Practical examples of applying ε-differential privacy to training pipelines to protect sensitive data.
- **Model Fairness & Bias:** Auditing ML models for demographic bias using synthetic datasets and fairness metrics.
- **AI Threat Modeling:** Applying MITRE ATLAS and OWASP ML Top 10 frameworks to identify threats in ML pipelines.
- **Prompt Injection & LLM Security:** Educational demonstrations of prompt injection vulnerabilities in language model applications.

## Skills Demonstrated

| Skill | Details |
|---|---|
| AI/ML Security | Adversarial robustness, evasion attacks, defense mechanisms |
| Privacy Engineering | Differential privacy (ε-DP), data minimization |
| Threat Modeling | MITRE ATLAS, OWASP ML Top 10 |
| Python (ML Stack) | PyTorch/TensorFlow, NumPy, scikit-learn |
| Responsible AI | Fairness metrics, bias detection, explainability |

## How to Run

```bash
# Clone the repository
git clone https://github.com/martinzambonino/ai-security-foundations.git
cd ai-security-foundations

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/macOS
# venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt

# Run an example
python src/adversarial_fgsm.py --help
```

## Methodology

- **OWASP Machine Learning Top 10:** Security risks specific to ML systems.
- **MITRE ATLAS:** Adversarial Threat Landscape for AI Systems — a knowledge base of adversary tactics.
- **NIST AI RMF (AI 100-1):** AI Risk Management Framework for trustworthy AI development.
- **IEEE Ethically Aligned Design:** Guidelines for responsible AI.

## Limitations

- Adversarial attack implementations are **educational only** — simplified for understanding, not optimized for real attacks.
- All training data is synthetic or from public academic datasets (e.g., MNIST, CIFAR-10).
- Differential privacy implementations demonstrate concepts but are not production-grade.
- LLM security examples use local models or API sandboxes only.

## ⚖️ Ethical & Legal Disclaimer

> [!WARNING]
> **This repository is strictly for academic and educational purposes.**
> Adversarial attack techniques must **not** be used against ML systems without explicit, written authorization from the system owner.
> Prompt injection demonstrations are for educational awareness only and must not be used to exploit commercial AI services.
> The author assumes no liability for misuse.

### 🇪🇨 Compliance Note (Ecuador — LOPDP/SPDP)

This project adheres to Privacy by Design and Default principles.
**No real personal data is used in model training, evaluation, or testing.** All datasets are purely synthetic (generated via `Faker`) or officially public academic datasets (MNIST, CIFAR-10, etc.). Differential privacy techniques are applied as an additional safeguard. This is compliant with the *Ley Orgánica de Protección de Datos Personales (LOPDP)* and auditable by the *Superintendencia de Protección de Datos Personales (SPDP)*.
