# Networking, Linux & Security — Practical Lab

📘 Dokumentasi praktis lab untuk memahami *networking fundamental*, administrasi Linux, dan pemahaman awal *security/ethical hacking* secara bertahap.

Repositori ini dirancang sebagai panduan lengkap dari dasar hingga teknik eksploitasi awal.

---

## 🧠 Overview

Lab mencakup:

✔️ Networking fundamental (OSI, TCP/IP, subnetting, DNS, HTTP)  
✔️ Administrasi Linux & Bash  
✔️ Hardening SSH  
✔️ Security basics — hashing, encryption, firewall  
✔️ Reconnaissance & OWASP Top 10 pemahaman awal  
✔️ Nmap & Netcat untuk eksplorasi dan test

---

## 📂 Table of Contents

1. [Week 1 — Networking Fundamental](#week-1--networking-fundamental)  
2. [Week 2 — Linux & Bash Lab](#week-2--linux--bash-lab)  
3. [Week 3 — Linux Security, OWASP & Exploitation Basics](#week-3--linux-security-owasp--exploitation-basics)  
4. [Lab Environment](#lab-environment)  
5. [Tools Used](#tools-used)  
6. [Next Roadmap](#next-roadmap)  
7. [Author](#author)

---

## 🌐 Week 1 — Networking Fundamental

**Dokumentasi:** `Week1-Networking-Fundamental.txt`

### 🧩 Fokus Materi

- OSI & TCP/IP Model  
- IPv4 Addressing & Subnetting  
- DNS workflow & HTTP vs HTTPS  
- Nmap scanning dasar (port, service, versi)  
- Pengenalan troubleshooting dasar jaringan :contentReference[oaicite:1]{index=1}

### 🎯 Hasil Pembelajaran

- Memahami cara data berpindah dalam layer jaringan
- Hitung subnet & host usable
- Kenali port & service umum
- Lakukan basic scanning dengan Nmap

---

## 🐧 Week 2 — Linux & Bash Lab

**Dokumentasi:** `Week2-Linux-Bash-Lab.txt`

### 🧩 Fokus Materi

- Struktur file system Linux & direktori penting
- Permission & ownership (chmod, chown)
- Process management (`ps`, `top`, `kill`)
- Networking command (`ss`, `netstat`, `curl`, `telnet`)
- Bash scripting dasar
- SSH server setup & hardening (key authentication) :contentReference[oaicite:2]{index=2}

### 🎯 Hasil Pembelajaran

- Navigasi filesystem Linux
- Kelola permission & proses
- Automasi dasar dengan Bash
- Konfigurasi SSH yang lebih aman

---

## 🔐 Week 3 — Linux Security, OWASP & Exploitation Basics

**Dokumentasi:** `Week 3 – Linux Security, OWASP & Network Exploitation Basics.txt`

### 🧩 Fokus Materi

1. **CIA Triad & Sniffing HTTP**  
   - Bandingkan plaintext HTTP vs terenkripsi HTTPS  
2. **Hashing & Encryption**  
   - Perbedaan dan praktik hashing/enkripsi  
3. **UFW Firewall (Rules & Logging)**  
   - Konfigurasi block/allow, log aktif  
4. **OWASP Top 10 (Simulasi Metasploitable)**  
   - Identifikasi kategori kerentanan umum  
5. **Advanced Nmap Scan**  
   - Port/service/version/OS detection  
6. **Netcat Practice & Reverse Shell**  
   - Listener, connect, upgrade shell :contentReference[oaicite:3]{index=3}

### 🎯 Hasil Pembelajaran

- Pahami celah *confidentiality* HTTP
- Maknai hashing vs encryption
- Implementasi firewall dasar
- Simulasi rekonstruksi OWASP Top 10
- Penggunaan Nmap lanjutan
- Praktik Netcat connect & reverse shell

---

## 🧪 Lab Environment

Lab dijalankan dengan jaringan internal VirtualBox:

- **Kali Linux** — Attacker  
- **Ubuntu Server** — Target  
- **Metasploitable** — Target rentan (Week 3)  
- Network: `192.168.100.0/24` :contentReference[oaicite:4]{index=4}

---

## 🛠️ Tools Used

### 🔹 Networking / Recon

- `nmap`, `ss`, `netstat`, `tcpdump`  
- `curl`, `telnet`, DNS tools

### 🔹 Linux Administration

- `chmod`, `chown`, `ps`, `top`, `kill`  
- Bash scripting

### 🔹 Security / Exploitation

- UFW (firewall)
- Netcat (`nc`)
- OWASP awareness

---

## 👤 Author

**Dryex** — Dokumentasi lab praktis membangun pondasi kuat cybersecurity.

---
