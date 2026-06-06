# Volatility & Expected Move Analyzer

A clean, single-page client-side dashboard utilizing WebAssembly via Pyodide to process live financial metrics, running calculations inside the browser environment.

**Live at**: https://changjulian.cloud/volatility/

## Features
- Historical Volatility (30-day)
- GARCH / EWMA Forecast Volatility
- Implied Volatility from option chains
- Expected One-Day Move calculation
- 1 Standard Deviation Down Move Target

## Tech
- Pyodide (Python WASM)
- Yahoo Finance API
- Tailwind CSS (CDN)
