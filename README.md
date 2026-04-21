# Mohsin Belam
**Electronics & Communication Engineering** · 20 · VGEC '26  
Cryptography · Network Security · Embedded Systems · Full-Stack Engineering

[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/marsthepreacher)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohsin-belam-b82abb279/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohsinbelam@gmail.com)

---

Final-year ECE student who builds things end to end. From custom encryption algorithms and VPN tunnels to NLP platforms, gesture-controlled instruments, and adaptive learning apps. If it involves breaking something down to first principles and building it right, that is the work.

---

## Freelance

### [AJ71 Events](https://moonpie.art) *(in progress)*
Designing and building the web presence for AJ71 Events, a Daman-based event management firm operating since 1971. The site covers their full service range across weddings, corporate events, and private celebrations, with a gallery, blog, enquiry flow, and team pages. Clean, editorial aesthetic built to match the tone of a company that has run 500+ events over five decades.  
`React` `TypeScript` `Vite` `Tailwind CSS`

---

## Projects

### [Deimos Cipher](https://github.com/MohsinCell/Deimos-Cipher) · [Live Demo](https://deimoscipher.space)
Symmetric-key encryption algorithm achieving **6.24 bits/byte entropy** for short plaintexts, outperforming AES (4.00) and ChaCha20 (2.58). Built around XChaCha20, HKDF-BLAKE2b, and HMAC-SHA256. Ships as a CLI, a reusable C++ API, and a browser app supporting text, image, and video encryption. Published in the *Journal of Electrical and Computational Innovations*.  
`C++` `Python` `OpenSSL` `libsodium` `Cryptography`

---

### [SALSA - Encrypted Tunnel](https://github.com/MohsinCell/SALSA-Encrypted-Tunnel)
Research-grade VPN built on the Deimos Cipher. Python control plane loads a compiled C++ cipher DLL via ctypes, handling handshake, session key negotiation, per-packet framing, keepalive, and bandwidth telemetry. Includes a SOCKS5 proxy layer over the encrypted tunnel and a Tkinter GUI for server/client management and live traffic monitoring.  
`Python` `C++` `Socket Programming` `Network Security` `SOCKS5`

---

### [ReviewIQ](https://github.com/MohsinCell/NLP-Review-Authenticity-Analysis) · [Live Demo](https://reviewiq.website)
Full-stack NLP platform for detecting fake, AI-generated, and manipulated product reviews. Runs a multi-model fusion pipeline across three independently fine-tuned transformers: a BERT sentiment classifier, a BERT star-rating predictor, and a RoBERTa AI-detection model. Produces a composite 0-100 authenticity score per review. Product-level trust reports add statistical anomaly detection, near-duplicate identification via TF-IDF cosine similarity, and temporal burst detection. Covers Amazon (10 regional domains), Flipkart, Myntra, Ajio, and Nykaa through a stealth-capable Playwright scraper. Ships with a Chrome extension for one-click in-browser analysis.  
`Java 21` `Spring Boot` `React` `TypeScript` `PyTorch` `BERT` `RoBERTa` `PostgreSQL` `Redis` `Playwright`

---

### [Sepia - Air Instruments](https://github.com/MohsinCell/SEPIA-Air-Instruments) · [Live Demo](https://sepia.website)
Touchless music performance system that maps finger gestures to all 120 General MIDI instruments via webcam. MediaPipe Hands tracks 21 landmarks per hand in real time; a debounced finger-state algorithm triggers note events through the Web Audio API. Each instrument category has tailored note mappings: chord voicings for piano and guitar, low-register single notes for bass, pentatonic modes for ethnic instruments. Includes live skeleton visualization, particle effects, performance recording, and full mobile support. All processing happens client-side with no data leaving the device.  
`TypeScript` `React` `MediaPipe` `Web Audio API` `Vite` `Docker`

---

### [Zensei - Study Garden](https://github.com/MohsinCell/Zensei-Study-Garden) · [Live Demo](https://zensei.study)
Adaptive learning platform that personalizes AI-generated explanations to each user's role, education level, interests, and preferred style. Onboarding captures a learning profile; every subsequent explanation is shaped by it. Topics are structured into TL;DR, core explanation, analogy, deeper dive, and example sections, with follow-up conversation history preserved per topic. A gamification layer tracks XP, streaks with multipliers up to 2x at 30+ days, six progression ranks (Seed to Elder Tree), and tiered achievements across exploration, depth, mastery, and consistency categories.  
`Next.js` `TypeScript` `Prisma` `PostgreSQL` `Docker`

---

### [Creeks - Intelligent Solar Tracker](https://github.com/MohsinCell/Creeks-Intelligent-Solar-Tracking-System) · [Dashboard](https://creeks.netlify.app/)
Dual-axis solar tracker simulating location-specific sun path cycles across 12 positioning steps (azimuth 25-175 deg, elevation 35-135 deg). The Arduino firmware supports AUTO and MANUAL modes via a clean serial command interface, with live position reporting and a calibration routine. Controllable directly from the web dashboard through the Web Serial API.  
`Arduino` `C` `Embedded Systems` `Web Serial API`

---

## Publication

**Deimos Cipher: A High-Entropy, Secure Encryption Algorithm with Strong Diffusion and Key Sensitivity**  
*Journal of Electrical and Computational Innovations*, 2(1), 2025 · [Read Paper](https://www.opastpublishers.com/open-access-articles/deimos-cipher-a-highentropy-secure-encryption-algorithm-with-strong-diffusion-and-key-sensitivity.pdf)

---

## Skills

**Languages:** `C++` `Python` `Java` `JavaScript` `TypeScript` `Bash`  
**Cryptography:** `Symmetric/Asymmetric Encryption` `HKDF` `PBKDF2` `HMAC` `SHA-256` `BLAKE2b` `XChaCha20` `Cryptanalysis`  
**Networking:** `VPN Tunneling` `TCP/IP` `SOCKS5` `Packet Routing` `Socket Programming` `Wireshark` `OpenSSL`  
**ML/NLP:** `PyTorch` `BERT` `RoBERTa` `HuggingFace Transformers` `KeyBERT` `scikit-learn` `MediaPipe`  
**Backend:** `Spring Boot` `Flask` `Node.js` `PostgreSQL` `Redis` `Prisma` `JWT` `REST APIs`  
**Frontend:** `React` `Next.js` `TypeScript` `Tailwind CSS` `Vite` `Web Audio API`  
**Hardware:** `Arduino` `Signal Processing` `ADC/DAC` `Embedded Systems` `Servo Control`  
**Tools:** `Git` `Docker` `Linux` `Nginx` `LaTeX` `Playwright`

---

> *"Know Thyself"* — Socrates
