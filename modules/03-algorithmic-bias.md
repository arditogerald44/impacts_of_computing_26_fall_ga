# Module 3: Algorithmic Systems & The Optimization Trap

## 📖 Core Readings This Week
* **Cathy O'Neil**, *Weapons of Math Destruction* (Chapters 1–3) 
    👉 [Internet Archive Open Community Library](https://archive.org/details/weaponsofmathdes0000onei)
* **AlgorithmWatch**, *Managed by the Algorithm: How AI is Changing the Way We Work* (Workplace Automation Index) 
    👉 [AlgorithmWatch NGO Platform](https://algorithmwatch.org/en/automated-decision-making-workplace/)
* **Alkhathlan et al.**, *"Exploring 'Just Noticeable' Group Fairness in Rankings"* (Proceedings of the AAAI/ACM Conference on AI, Ethics, and Society) 
    👉 [AAAI Digital Library Open Access](https://ojs.aaai.org/)

---

## 🧠 1. Theoretical Context: Micro-Biasing and Workplace Panopticons

We expand Cathy O'Neil’s structural analysis of automated models by exploring how algorithms systematically reshape modern labor. Independent investigations by **AlgorithmWatch** demonstrate that automated decision-making (ADM) systems are actively deployed to continuously log employee performance data, track physical movement telemetry, and generate automated retention scores that predict which workers to target for termination.

Furthermore, we confront a subtle technical threat highlighted in recent **AAAI/ACM (AIES)** proceedings: **"Just Noticeable" Bias**. Optimization models rarely present a massive, easily detectable failure vector. Instead, deep ranking networks frequently introduce tiny, incremental downward adjustments to marginalized groups within employment pipelines or search queries. These shifts are invisible to standard compliance checkers but systematically segregate outcomes at scale.

---

## 🛠️ Weekly Lab Evaluation Options

### 💻 Option A: The Developer Track (The Just-Noticeable Ranking Audit)
1. Write a script to simulate an institutional recruitment portal that ranks 1,000 applicants based on a synthetic performance score variable.
2. Introduce a hidden "Just Noticeable" loop: inject a minor 1.5% performance-score penalty that targets candidates passing a non-protected proxy data point (e.g., graduated from a specific array of zip codes).
3. **Deliverable:** Submit your script. Generate an output distribution graph showing how a standard, macro-level compliance audit completely misses this 1.5% deviation, while your timeline analysis proves the targeted demographic is entirely stripped of top-10 ranking positions by the end of the pipeline.

### 🔍 Option B: The Analyst Track (The Macro-Compliance Forensic Audit)
1. Open `labs/03-bias-simulation.html` in your browser. 
2. **Test Run 1:** Click the "Run Standard Baseline Array" button. Record the Disparate Impact Ratio and the output demographic distribution in the top 15 ranks.
3. **Test Run 2:** Click the "Deploy Opaque Optimization Model" button. Record the new Disparate Impact Ratio. Observe the Audit Compliance status box. Note the change in how many purple Group Beta candidates manage to retain placement flags inside the top 10 positions.
4. **Deliverable:** Submit an audit analysis report (`LAB-SUBMISSION.md`). Using **Alkhathlan et al. (AIES)**, explain how the hidden 1.6-point reduction acts as a *Just Noticeable Bias*—passing legal regulatory checklist formulas perfectly, while completely executing structural exclusion at the pipeline's peak.