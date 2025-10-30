# Δ = Observer Delta

**Einstein was wrong — in your browser. No internet. No install.**

Live **Bell-state CHSH simulation** in a noisy cavity — **100% offline** using local Pyodide.

Slide noise → click **Collapse Now** → **S > 2.79** → **Spooky action survives**.

---

## Features

- **Quantum CHSH Inequality**  
  - Bell state: `(|00⟩ + |11⟩)/√2`  
  - Lindblad amplitude damping (γ)  
  - **S > 2.0** → **Einstein loses**  
  - **S ≤ 2.0** → classical limit

- **100% Offline**  
  - Local Pyodide + NumPy (no CDN)  
  - Works on planes, subways, Mars  
  - <200 lines of code

- **Physics-Accurate**  
  - Coherence decay: `exp(-γ t)`  
  - Analytical correlation: `cos(θ₁ - θ₂)`  
  - Max S = 2.828 at γ = 0

---

## How to Use

1. **Slide noise (γ)** → watch S decay  
2. Click **"Collapse Now"** → run quantum simulation  
3. **S > 2 + green pulse** → **double win**

> **Screenshot your S > 2.79 → tag @ObserverDelta**

---

## Live Demo (Works Offline)

**Try it now:**  
[https://observer-delta.github.io/Delta-Observer-Solar](https://observer-delta.github.io/Delta-Observer-Solar)

---

## Tech Stack

- **Frontend**: HTML + CSS + JS  
- **Backend**: Pyodide (Python in browser)  
- **Hosting**: GitHub Pages  
- **No CDN. No server. No excuses.**

---

## Commit History

```text
OFFLINE: Local Pyodide — no CDN, no white page, S > 2
Launch: Δ = Observer Delta — Quantum + Solar Live
