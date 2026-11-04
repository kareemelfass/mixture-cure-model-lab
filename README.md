# Mixture Cure Model Lab

An interactive HEOR tutorial on mixture cure models for survival extrapolation and health technology assessment.

## Live interactive tutorial

**[Open the Mixture Cure Model Lab](https://kareemelfass.github.io/mixture-cure-model-lab/)**

The tutorial is designed for **learning by seeing and doing**: change the cure fraction, the latency curve, the certainty level and the background death rate, and watch the survival curves, cure probabilities and cure points update.

## Topics covered

- When to use a mixture cure model: a decision process, not a checklist
- How the cure fraction is estimated: plateau formula, maximum likelihood, profile-likelihood intervals, informed (outside-evidence) approach, covariates
- How the model defines a patient as cured: latent label, Bayes' rule, EM algorithm
- How a cure point is derived (the model has none): probability, hazard and clinical rules, with an interactive calculator
- Whether the cure fraction accounts for general population survival: background mortality and relative survival, with an interactive chart
- Data needed, R and Python code with line-by-line explanations
- Worked calculations, including the cost of a hard single cure point and a simulation showing how follow-up length changes the estimate
- Published examples (including NICE TA975), pitfalls, and a reporting checklist for HTA submissions
- Glossary and sources

The numerical examples are illustrative or simulated for teaching. The R code was not executed when the tutorial was written, so check package argument names on your machine.

## Earlier version

The previous version of this lab (Lab 01, with the treatment-group cure-model calculator) is kept at [/original/](https://kareemelfass.github.io/mixture-cure-model-lab/original/).

## Part of HEOR Interactive Labs

This tutorial is part of the **[HEOR Interactive Labs](https://github.com/kareemelfass/HEOR-Interactive-Labs)** collection.

## Educational use

This tool is intended for methodological education and demonstration. It is not a substitute for case-specific survival modelling, clinical validation, HTA guidance, or validated analytical software.

---

Created by **Kareem Elfass**