# Kali-Linux-DVWA-in-Docker

Acest proiect creează un mediu de testare pentru securitate folosind Kali Linux și Damn Vulnerable Web Application (DVWA) într-o rețea Docker izolată.

# 🔥 Caracteristici :

  🌐 Rețea izolată pentru testare fără acces extern
  
  🐧 Kali Linux gata de utilizare

  💥 DVWA pentru practică în securitatea web

  🔄 Repornire automată a serviciilor

# 📦 Configurare :

## 1️⃣ Instalează Docker & Docker Compose

## 2️⃣ Clonează acest repository:
```
git clone https://github.com/AlexandruEmil/Kali-Linux-DVWA-in-Docker
cd Kali-Linux-DVWA-in-Docker
```
## 3️⃣ Pornește containerele:
```
docker-compose up -d
```
## 4️⃣ Accesează serviciile:
```
Kali Linux: Atașează-te la container: docker exec -it kali-linux /bin/bash
DVWA: Deschide http://localhost:8080
```
# ⚙️ Configurare suplimentară

Pentru acces GUI în Kali, poți folosi `x11docker`

Modifică `docker-compose.yml` pentru a adăuga tool-uri suplimentare
