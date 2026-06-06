# Secure Volatility & Expected Move Analyzer

A single-page analytical dashboard executing browser-side WebAssembly data pipelines via Pyodide. Handled by a secure GitHub Actions deployment pipeline to shield sensitive API keys.

## ⚙️ Automated Deployment
This repo utilizes a `.github/workflows/deploy.yml` pipeline configuration. The action automatically injects the repository secret variable `FINANCIAL_API_KEY` directly into `index.html` at compile time and updates GitHub Pages securely.