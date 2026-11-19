# Evidence-Aware Digital Forensic Timeline Reconstruction
MEng-Cybersecurity Capstone, Project 4

## Team and roles
- Nidal: planning, documentation, integration
- Omar: evidence collection and data preparation
- Abdulrahman: Python development and event analysis
- Abdullah: dashboard development and testing

## Scope (Semester 1)
Python tool that correlates Windows Event Logs (EVTX) and Prefetch artifacts,
detects timestamp discrepancies, and assigns explainable evidence confidence
levels. Results are shown in a traceable timeline dashboard (Streamlit) linked
to the raw evidence, and missing artifacts are treated as unverified rather

than proof that an event did not occur.
## Repository structure
- docs/: scope, schema, A1 proposal
- src/: Python code
- data/: sample evidence (non-sensitive)
- dashboard/: Streamlit app
- tests/: test cases and results
