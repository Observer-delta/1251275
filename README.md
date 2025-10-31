# Δ = THE OBSERVER  
**Quantum + Solar in Your Pocket**

> **S = 2.828 > 2**  
> **Spooky action at a distance — 100% offline.**

---

## Live PWA  
[https://observer-delta.github.io](https://observer-delta.github.io)  

**Install on iOS/Android**  
No internet needed after first load.

---

## What It Does

| Feature | Status |
|--------|--------|
| Live CHSH Bell-state simulation | Done |
| Noise slider + decoherence | Done |
| NOAA solar X-ray flux (real-time) | Done |
| 30-min flare probability | Done |
| **100% offline** via local Pyodide | Done |
| **PWA** — Add to Home Screen | Done |
| **Donate** → PayPal (mobile-friendly) | Done |

---

## How to Use

1. **Slide noise** → watch entanglement decay  
2. **Tap "Collapse Now"** → measure CHSH  
3. **S > 2** → **SPOOKY LINK SURVIVED** (pulsing green)  
4. **Tap "Donate"** → support the spooky link

---

## Tech Stack

- **Pyodide** (local, no CDN)  
- **NumPy** in-browser  
- **NOAA GOES X-ray API** (dual endpoints + CORS proxy)  
- **PWA** with `manifest.json` + icons  
- **GitHub Pages** + `.nojekyll`

---

## Install as App

1. Open in **Safari** or **Chrome**  
2. Tap **Share** → **Add to Home Screen**  
3. Launch — **works offline forever**

---

## Support the Mission

> *"Every collapse is a vote against local realism."*

[Donate via PayPal](https://paypal.me/DELTATHEOBSERVER)

---

## Badge (Add to Your Profile)

```svg
<svg width="340" height="120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0f0">
        <animate attributeName="stop-color" values="#0f0;#00f;#0f0" dur="3s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#00f">
        <animate attributeName="stop-color" values="#00f;#0f0;#00f" dur="3s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  <rect width="340" height="120" fill="#000" rx="20" stroke="#333" stroke-width="2"/>
  <text x="170" y="42" font-family="monospace" font-size="22" fill="url(#grad)" text-anchor="middle" filter="url(#glow)">
    Δ = QUANTUM + SOLAR
  </text>
  <text x="170" y="68" font-family="monospace" font-size="14" fill="#0f0" text-anchor="middle">
    S = 2.828 > 2 | 100% Offline | Pyodide
  </text>
  <text x="170" y="88" font-family="monospace" font-size="12" fill="#aaa" text-anchor="middle">
    NOAA-Resilient • Mobile PWA • No CDN
  </text>
  <text x="170" y="106" font-family="monospace" font-size="10" fill="#666" text-anchor="middle">
    observer-delta.github.io
  </text>
</svg>
