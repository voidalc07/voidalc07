### Hi, I'm Pranav 👋

Data Science graduate (First Class Honours, Northumbria University, 2026), heading into an MSc in Advanced Data Science with Health at Newcastle. I build ML systems end to end - from raw NumPy autograd engines to production-shaped retrieval pipelines - with a focus on healthcare applications and rigorous model evaluation.

📍 Newcastle upon Tyne, UK &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/pranav-naveen-kumar)

### Featured projects

**[Nephrotoxicity Predictor](https://github.com/voidalc07/Nephrotoxicity-Predictor_AI)**
Live SMILES-to-toxicity screening dashboard comparing 5 model families - stacked ensembles, Tanimoto-kernel Gaussian Process, an autoencoder, and a fine-tuned ChemBERTa transformer - with consensus scoring across engines. Best external-test ROC-AUC 0.860. Dissertation project.
`Python` `scikit-learn` `RDKit` `HuggingFace Transformers` `Streamlit`

**[AV2 Multimodal Trajectory Prediction](https://github.com/voidalc07/Multimodal-vehicle-trajectory-prediction-on-Argoverse-2)**
VectorNet-style encoder with winner-takes-all loss, forecasting 6 seconds of vehicle motion on Argoverse 2. minADE₆ 1.19 m, beating constant-velocity and constant-yaw-rate baselines - trained end-to-end on a MacBook Air M2.
`PyTorch` `NumPy`

**[Bare Metal ML](https://github.com/voidalc07/NumPy-only-ML-library)**
A from-scratch ML library - autograd engine, MLP, and four classical algorithms - proven equivalent to scikit-learn with automated parity tests and CI-verified gradient correctness (finite-difference check, ≤1e-4 error).
`NumPy` `pytest` `GitHub Actions`

**[AI Document Intelligence](https://github.com/voidalc07/AI-Document-Intelligence)**
Grounded document Q&A and risk review for contracts and PDFs. Hybrid retrieval (pgvector + Postgres full-text), OCR fallback for scanned documents, and every answer traced back to a page-coordinate citation.
`FastAPI` `pgvector` `PostgreSQL` `Tesseract OCR`

**[QueryPilot](https://github.com/voidalc07/Adaptive-Join-Engine)**
Describe a join in plain English - QueryPilot picks the optimal algorithm, explains why, and switches strategy mid-execution if its cost estimates turn out wrong.
`Python` `CI`

**[CSV Predictor](https://github.com/voidalc07/csv-predictor)** · [live demo](https://huggingface.co/spaces/voidalc07/csv-predictor)
Upload a CSV, auto-detect the ML task, train a Random Forest, and see test-set metrics and feature importances - deployed on Hugging Face Spaces.
`Streamlit` `scikit-learn` `pytest`
