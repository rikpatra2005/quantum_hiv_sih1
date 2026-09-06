# QuantumAI-HIV | SIH 2026

A hybrid Classical ML + 4-Qubit Quantum-inspired risk assessment demo for HIV screening, built with Streamlit.

## Features
- Secure login portal (demo-only auth)
- Patient demographics + simulated Edge-IoT (ESP32/Pico 2W) telemetry
- Clinical biomarker intake (leakage-proof: no HIV RNA/viral load as input)
- Hybrid Classical (XGBoost/CatBoost-style) + Quantum VQC risk engine
- SHAP-style explainability chart
- Zonal Vulnerability Index (ZVI) heatmap
- CSV patient report download

## Run locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Deploy for free (Streamlit Community Cloud)
1. Push this repo to GitHub.
2. Go to https://share.streamlit.io and sign in with GitHub.
3. Click **New app** → select this repo → branch `main` → main file `app.py`.
4. Click **Deploy**. You'll get a live URL in ~2 minutes.

## Disclaimer
This is a hackathon demo. Risk scores are simulated for illustration and are **not** a medical diagnostic tool.
