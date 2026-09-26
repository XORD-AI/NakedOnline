# NakedOnline

XORD NakedOnline — Browser Privacy Exposure Scanner  
See exactly what websites can extract from your device — in real-time, from inside your own browser.

---

## What It Scans

## BASIC MODE — Core Exposure Vectors

- Public IP address, ISP, city/country  
- User agent, OS platform, browser language, timezone  
- Screen resolution, CPU cores, device memory  
- Canvas fingerprint (2D hash)  
- WebGL vendor/renderer fingerprint  
- Audio signal fingerprint  
- Local/session/IndexedDB availability  
- Installed fonts (glyph width-based detection)

## DEEP NAKED MODE — High-Entropy Fingerprints

- WebRTC IP leak test (STUN via ICE candidates)  
- Speech synthesis voice profiles (extremely unique)  
- Media devices enumeration (mics, cameras, speakers)  
- Battery API exposure (charge state, depletion)  
- Motion sensors (accelerometer, gyroscope, etc.)  
- Timing attacks (micro-benchmark speed, time origin)

Each fingerprint contributes to your Exposure Score (in bits).  
The higher the score, the more uniquely trackable you are.

---

## Live Demo

[https://xord.io/intelligence/naked-online.html](https://xord.io/intelligence_r66h32d54/naked-online.html)

---

## Who Is This For

- Privacy-conscious users measuring browser fingerprint exposure  
- Researchers exploring entropy vectors in real-world environments  
- Developers building or testing fingerprinting mitigation tools  
- Activists, journalists, whistleblowers assessing anonymity weaknesses  

No gimmicks. No phone-home. No analytics beyond your local session — unless you want to inspect those too.

---

## How It Works

- Runs as a single self-contained HTML file  
- Executes entirely in the client browser  
- Requires no server, no login, no data transmission  
- Works offline (IP fallback stubs trigger gracefully)  
- JavaScript only — compatible with all Chromium and Firefox variants  

---

## License

MIT License — Free for personal, academic, and commercial use.  
No restrictions. Fork it, audit it, improve it.

---

## XORD Intelligence

Modular tools for privacy, security, and cognitive defense.

The modern web is not neutral. It observes. It remembers. It fingerprints.  
NakedOnline shows you what it sees.
