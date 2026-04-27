# Comparateur de prix medicament.ma - J5/30 #PythonEmployable

Scraper Python pour récupérer le prix des médicaments sur medicament.ma avec gestion anti-bot Cloudflare.

## Leçon J5 : 100% de disponibilité
Quand Cloudflare bloque 30% des requêtes, un bon dev ne force pas. Il prévoit un fallback.

Ce script renvoie toujours une réponse : soit le prix live, soit depuis le cache local.

## Stack
Python, Selenium, undetected-chromedriver, Regex

## Fonctionnalités
- WebDriverWait pour DOM dynamique
- Bypass Cloudflare avec undetected-chromedriver  
- Fallback local si site bloqué → Zéro crash
- Pattern Circuit Breaker

## Lancer
```bash
pip install selenium undetected-chromedriver
python comparateur_selenium.py