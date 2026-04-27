# Comparateur de prix medicament.ma - J5/30 #PythonEmployable

Scraper Python pour récupérer le prix des médicaments sur medicament.ma avec gestion anti-bot Cloudflare.

## Leçon J5 : 100% de disponibilité
Quand Cloudflare bloque 30% des requêtes, mieux vaut prévoir un fallback.

## Fonctionnalités
- WebDriverWait pour DOM dynamique
- Bypass Cloudflare avec undetected-chromedriver  
- Fallback local si site bloqué → Zéro crash
- Pattern Circuit Breaker

## Stack
Python, Selenium, undetected-chromedriver, Regex

## Lancer
```bash
pip install selenium undetected-chromedriver
python comparateur_selenium.py