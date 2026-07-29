# SOC Alert Triage Optimization

Technical project report and executed notebook for an Optimization Algorithms course.

## Summary

This project models SOC alert triage as a constrained scheduling problem. The goal is to decide which alerts should be handled, which analyst should handle them, and when they should be handled during one shift.

The project combines:

- MILP optimization
- Gurobi exact solving
- ML-based risk, skill, and duration prediction
- ML-guided Simulated Annealing as a metaheuristic comparison
- SOC shift constraints such as deadlines, analyst availability, skill requirements, breaks, and on-call escalation

## Portfolio Label

Best public label:

> Technical project report / applied optimization project

This is stronger and more accurate than calling it a formal research paper because the artifact is an applied implementation with mathematical modeling, experiments, and a working notebook.

## Security Relevance

Security Operations Centers face alert overload and analyst fatigue. This project connects optimization and ML to a practical SOC planning problem:

- Prioritize high-risk alerts.
- Respect SLA deadlines.
- Match alerts to analyst skills.
- Avoid unrealistic workload assumptions.
- Compare exact optimization with faster approximate search.

## Artifacts

Public artifacts included:

- Sanitized technical report summary
- Executed notebook after identity/path review
- Pipeline GIF if confirmed safe
- Interactive SOC shift wallboard prototype

Do not publish employer data, real alerts, ticket data, or private SOC screenshots.

## Interface Prototype

The repository includes an interactive SOC shift wallboard prototype that demonstrates how the project interface could look if the optimization workflow were presented as a live operational dashboard.

The prototype visualizes:

- Shift roster and break planning
- Alert stream simulation
- ML-based alert risk and routing decisions
- Analyst workload and coverage status
- L3 on-call escalation visibility

Live demo path after GitHub Pages is enabled:

<https://yasir-alharbi.github.io/soc-alert-triage-optimization/demo/soc-shift-wallboard/>

## Methods

- Mixed Integer Linear Programming
- Gurobi
- Simulated Annealing
- Logistic Regression risk scoring
- Skill prediction
- Duration prediction
- Synthetic SOC alert generation

## Public Release Notes

Before publishing, remove student ID values from the paper and notebook. Review the wallboard prototype because it contains themed character imagery and should not be published as a professional artifact unless redesigned neutrally.
