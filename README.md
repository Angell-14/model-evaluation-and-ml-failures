# Model Evaluation and ML Failures

This repository contains applied case studies focused on **how and why machine learning models fail** even when traditional evaluation metrics appear strong.

Rather than optimizing for accuracy alone, these case studies examine the gaps between:
- model performance and real-world decision quality
- correlation and true causal signals
- offline evaluation and deployment behavior

The goal is to develop better judgment around **when models should be trusted and when they should not**.

---

## Case Study Themes

### 1. Correlation vs Causation
Understanding how seemingly strong features can lead to misleading conclusions when causal structure is ignored.

📁 `correlation_and_causality/`  
- **When Features Lie**  
  Explores how correlated inputs can inflate model performance while providing no real decision value.

---

### 2. Metrics vs Decisions
Evaluating why strong predictive accuracy does not necessarily translate into better outcomes.

📁 `metrics_and_decisions/`  
- **Prediction Is Not the Decision**  
  Examines the disconnect between prediction quality and downstream decision-making.

---

### 3. Bias and Data Issues *(in progress)*
Future case studies will focus on:
- data leakage
- sampling bias
- proxy variables
- evaluation blind spots

📁 `bias_and_data_issues/`

---

## Why This Repository Exists

Many real-world ML failures are not caused by poor models, but by:
- flawed evaluation assumptions
- misuse of metrics
- incorrect interpretation of model outputs
These case studies aim to make those failure modes explicit.

