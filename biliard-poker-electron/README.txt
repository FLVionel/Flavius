BILIARD POKER — Aplicatie Desktop (Electron)
=============================================

CERINTE:
  - Node.js (descarca de la https://nodejs.org) — versiunea LTS

PASII PENTRU RULARE:
  1. Instaleaza Node.js
  2. Deschide un terminal (Command Prompt / PowerShell) in acest folder
  3. Ruleaza:  npm install
  4. Ruleaza:  npm start
     → Aplicatia se deschide ca fereastra desktop

PASII PENTRU A FACE UN INSTALLER .EXE (Windows):
  1. Dupa "npm install", ruleaza:
       npm run build-win
  2. Fisierul .exe apare in folderul  dist/
  3. Distribuie acel .exe — nu mai are nevoie de Node.js

PENTRU MAC:
  npm run build-mac  →  fisier .dmg in dist/

PENTRU LINUX:
  npm run build-linux  →  fisier .AppImage in dist/

DATE SALVATE:
  Datele (liga, jucatori, setari) sunt salvate in IndexedDB
  al aplicatiei Electron, separat de browser.
  Locatia pe Windows: %APPDATA%\biliard-poker\
