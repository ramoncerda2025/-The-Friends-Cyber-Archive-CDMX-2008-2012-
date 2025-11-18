# -The-Friends-Cyber-Archive-CDMX-2008-2012-
github.com/RAMON_CERDA/the-friends-cyber-archive/
README.md (ÉPICO, estilo rockstar-nerd)markdown



# The Friends Cyber Archive – CDMX (2008-2012)  
**"Donde el internet costaba $10/hora y el ciber era iglesia"**

![cyber](docs/cyber_friends.jpg)

---

## Contenido del CD Original
- 145 APKs (F-Droid, Titanium, Telegram old)
- Programas Windows (Winamp, Nero, CCleaner)
- Drivers, cracks, tutoriales en TXT

---

## APKs destacados
| App | Versión | Año | Notas |
|-----|--------|-----|-------|
| Titanium Backup | 3.5.7.1 | 2013 | Cracked, necesita root |
| F-Droid | 1.23.1 | 2012 | 100% open source |
| Telegram | 12.1.1 | 2011 | Pre-historia de los bots |

---

## ¿Cómo usarlo hoy?
```bash
# En Termux
git clone https://github.com/RAMON_CERDA/the-friends-cyber-archive
cd APKS/titanium-backup
termux-open TitaniumBackup_3.5.7.1.apk



Advertencia: Algunas apps no funcionan en Android 14. Usa emulador (F-Droid + Anbox).

Escaneo de seguridad (GitHub Actions)yaml



# .github/workflows/scan.yml
name: Escanear APKs
on: [push]
jobs:
  scan:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Escanear con VirusTotal
        uses: crazy-max/ghaction-virustotal@v3
        with:
          files: APKS/**/*.apk



Autor@RAMON_CERDA

 – Ex-dueño de ciber, DJ, DevOps, cripto-nerd  "Este CD sobrevivió 3 mudanzas, 2 formateos y 1 inundación."

LicenciaCC-BY-NC-SA – Comparte, pero no vendas mi nostalgia.


---

## 6. PASOS AHORA MISMO (en tu cel)

```bash
# 1. Abre Termux
pkg update
pkg install git python

# 2. Crea el repo
gh auth login
gh repo create RAMON_CERDA/the-friends-cyber-archive --public

# 3. Clona y sube el CD
git clone https://github.com/RAMON_CERDA/the-friends-cyber-archive
cd the-friends-cyber-archive

# Copia todo del CD (conecta por USB)
cp -r /sdcard/CD_TheFriends/* .

git add .
git commit -m "feat: subo el CD completo del ciber The Friends"
git push


