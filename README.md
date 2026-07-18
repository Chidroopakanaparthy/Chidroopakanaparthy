# **Hi there, I'm Chidroopa Kanaparthy**

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=24&pause=1000&color=3670A0&center=true&vCenter=true&width=700&lines=AI+Safety+%26+Alignment+Researcher;Vision-Language+Model+Fairness+%26+Explainability;Building+Toward+Trustworthy+Multimodal+AI" alt="Typing SVG" />
  </a>
</div>

---

## About Me

I'm a Computer Science undergrad working on the intersection of vision-language models, fairness, and adversarial robustness. I'm currently interning at DRDO's Scientific Analysis Group, where my work spans adversarial attacks on face verification pipelines and — more centrally right now — auditing whether open-weight VLMs produce demographically disparate hallucinations when explaining face verification decisions.

I care about the gap between what models do and what they say they're doing — and I think that gap is where a lot of real-world AI harm hides. That's the thread connecting my current research: not "is the model accurate," but "is the model's explanation of itself honest, calibrated, and fair across groups."

Longer-term, I'm building toward research or engineering work in AI safety and mechanistic interpretability.

---

## Current Research

VLM Hallucination Fairness Audit (NeurIPS 2026 Workshop, in progress)
An explainability-layer fairness audit — asking whether VLMs (Qwen2.5-VL-7B-Instruct, InternVL3-8B) hallucinate differently across demographic groups when explaining decisions from separate face-verification models (ArcFace, AdaFace R50). Metrics: Hallucination Rate (primary), Calibration Disparity, Refusal/Hedging Rate, validated via Cohen's kappa across annotators. Built on RFW and DemogPairs, with resolution confounds controlled via regression covariates.

Adversarial Transfer Attacks on Face Verification (DRDO SAG)
Implemented and benchmarked PGN (Ge et al., NeurIPS 2023) and DHF (BMVC 2023) transfer attacks across face verification pipelines — finished 2nd of 8 on the internal leaderboard, with a notable impersonation/dodging performance split as a headline finding.

---

## Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,c,bash,gcp,docker,git,github,vscode&theme=dark&perline=10" alt="Skill Icons" />

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace%20Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-013243?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

</div>

Focus areas: VLM evaluation & explainability · adversarial robustness · fairness auditing · multi-agent systems · classical ML (RF, XGBoost, SHAP)

---

## Selected Projects

- VLM Fairness Audit — hallucination disparity across VLM explanations of FV decisions (RFW, DemogPairs) — in progress, NeurIPS 2026 workshop target
- Adversarial Robustness on Face Verification — PGN/DHF transfer attacks, ArcFace/AdaFace, IR152 — 2nd/8, DRDO internal leaderboard
- Anomalous Kinematic Detection & Safety Pipeline — Random Forest on IMU telemetry
- Lead-Flow AI — multi-agent lead qualification system (LangGraph, Gemini)
- Customer Churn Prediction — XGBoost + SHAP for interpretable churn modeling
- Open-source contributions: SymPy, KubeEdge Ianvs

---

Contribution City

<div align="center">
  <img src="./profile-3d-contrib/profile-season-animate.svg" alt="3D GitHub Commits" width="100%" />
</div>

---

## Connect with Me

<div align="left">
  <a href="mailto:chidroopak10@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://linkedin.com/in/chidroopa-kanaparthy-/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://x.com/Chidroopa07">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" />
  </a>
</div>
