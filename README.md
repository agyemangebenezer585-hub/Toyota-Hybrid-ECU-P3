# Toyota-Hybrid-ECU-P3
# Toyota Hybrid ECU - P3 SOC Battery Protection

Author: Ebenezer - Ghana to Japan Hybrid Engineer
Goal: MEXT Scholarship / Toyota Japan

## What is P3?
P3 builds on P2 EV Mode. This adds SMART battery protection:

- SOC Management: Keeps battery 40%-80% (Toyota real logic)
- Protects battery from over-charge and over-discharge
- Prevents EV Mode when battery low - switches to Engine
- Regenerative Braking with SOC limit

## Why this matters
Real Toyota Prius does this to make battery last 10+ years!

## How to run
python p3_hybrid.py
