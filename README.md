# Gerard Gonzalez

**ML researcher · cybersecurity student · homelab engineer**

Cybersecurity undergrad at PUCPR (Curitiba, Brazil). I do computer vision research under PIBIC, build mobile and web apps for real people with real problems, and self-host most of my infrastructure.

---

## Research — PIBIC @ PUCPR

- **Deepfake detection via latent representations** *(2026–27, ongoing)* — VAEs, lightly fine-tuned CNNs and ensembles for cross-dataset generalization (FaceForensics++ → DFDC). PyTorch · Hydra · MLflow.
- **Ultrasound diagnosis in dogs and cats** *(ongoing)* — Deep learning classifier for renal ultrasound (normal vs. altered) on ethics-approved clinical data.
- **[Equine resting-posture detection](https://github.com/TarsorCasePucpr/pibic-resultados)** *(2024–25)* — YOLOv11 on CCTV and night IR footage, subject-wise cross-validation, distributed training over SSH. **mAP50 = 0.995** on held-out animals.

## Apps

- **Dekiru** — Expo / React Native apps for daily life: an offline-first nutrition and training plan (SQLite, notifications, camera), and a Brussels edition with batch-cooking planning on real supermarket prices, GPS stop alarms and early strike alerts. Supabase + Edge Functions + pg_cron. [Privacy policy](https://github.com/TarsorCasePucpr/dekiru-legal)
- **Finanças** — Personal finance app on Open Finance (Pluggy): cards, invoices, installments, cash flow, spending limits. Bank credentials stay in Supabase Edge Functions, never on the device.
- **Preuniversitario** — University entrance exam prep platform: 1,700-question bank across 17 subjects, mock exams, progress tracking. PHP 8 + MySQL web app plus an Expo mobile client.

## Web & security

- **[SNGuard — Property registry portal](https://github.com/TarsorCasePucpr/Portal-para-Registro-de-Propriedade)** — Register belongings by serial number and check whether an item is reported stolen. Plain PHP + MySQL with TOTP MFA, bcrypt, CSRF, rate limiting and LGPD account deletion.
- **[Amazon price tracker](https://github.com/TarsorCasePucpr/scrapping-amazon-prices)** — Daily scraping with GitHub Actions, Turso (libSQL) storage and an Astro dashboard.
- **Supermarket price comparator** — Tracks a basket across Curitiba supermarkets (Carrefour, Muffato, Atacadão, Angeloni), matches products by EAN and tells you where to shop. Python stdlib + SQLite in Docker.

## Coursework

- **[Java Tycoon Capital](https://github.com/TarsorCasePucpr/Java-Tycoon-Capital)** — Adventure Capitalist–style tycoon game in Java (OOP).
- **[Morse code & flood fill](https://github.com/TarsorCasePucpr/Codigo_Morse_-_Flood_Fill)** — Data structures in Java.

## Homelab

Oracle Cloud, AWS and GCP instances plus a Raspberry Pi, reachable only through **Twingate** zero trust and **Cloudflare Tunnel** — no exposed ports. **Wazuh** for SIEM, Docker for services, self-hosted photo backups, and remote GPU servers for training.

## Stack

Python · PyTorch · TypeScript · React Native / Expo · Java · PHP · Rust · Bash · SQL (Postgres, MySQL, SQLite) · Supabase · Docker · Linux

## Get in touch

[gerard.gonzalez@pucpr.edu.br](mailto:gerard.gonzalez@pucpr.edu.br)  
[LinkedIn](https://www.linkedin.com/in/gerard-gonzalez-8778a9338/)

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TarsorCasePucpr/TarsorCasePucpr/output/github-snake-dark.svg">
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/TarsorCasePucpr/TarsorCasePucpr/output/github-snake.svg">
</picture>

Open to collaborations in CV research, cybersecurity, and infrastructure across Latin America.
