# The GAME Computational Psychology Pipeline

This repository describes the **GAME protocol** – a four-stage pipeline for doing psychology research that integrates theory, simulation, and empirical testing in a continuous cycle.  
The acronym **GAME** stands for:

- **G – Goals:** Define and ground your objectives  
- **A – Algorithms:** Build mechanistic models  
- **M – Measurements:** Validate empirically & via interventions  
- **E – Evolution:** Iterate continuously with feedback  

---

## 1. Goals – Define & Ground Objectives
- **Frame the problem:** Specify inputs, outputs, constraints, and a normative cost or utility function (e.g., maximise reward rate, minimise error).  
- **Philosophical commitments:** Make your theoretical stance explicit (e.g., predictive processing, dynamical systems, allostasis).  
- **Empirical seeding:** Use behavioural or naturalistic data to initialise model parameters.  
- **Translational focus:** Identify stakeholders (clinicians, educators, policymakers) and flag “knobs” in the system that can be tuned in real-world interventions.

---

## 2. Algorithms – Mechanistic Instantiation
- **Representation & algorithms:** Choose representations (e.g., latent states, neural dynamics) and algorithms (e.g., accumulation models, control loops) that solve the normative problem.  
- **Prototyping in Python/Colab:** Run parameter sweeps, Monte Carlo simulations, and cross-validation on open datasets.  
- **Intervention-ready design:** Prioritise mechanisms with parameters that can be feasibly tuned (e.g., cognitive biases, neural gain).  
- **Simulation experiments:** Perturb model parameters to predict applied impacts (“what happens if we reduce bias X by 20%?”).

---

## 3. Measurements – Empirical Validation & Intervention
- **Model testing:** Generate quantitative predictions (RT distributions, neural dynamics, representational geometries).  
- **Model comparison:** Use likelihoods, AIC/BIC, Bayes factors, posterior predictive checks.  
- **Targeted manipulations:** Design causal interventions (stimulus variations, reward schedules, TMS/pharmacology) to “turn the knobs.”  
- **Dual outcomes:** Evaluate both scientific metrics (fit, predictive accuracy) and applied metrics (symptom reduction, behaviour change).  

---

## 4. Evolution – Continuous Iteration
- **Adaptive objectives:** Update goals and cost functions as new data or stakeholder needs emerge.  
- **Mechanism refinement:** Re-fit, re-simulate, and prune models based on new evidence.  
- **Theory–practice alignment:** Ensure the evolving models remain coherent with your high-level
