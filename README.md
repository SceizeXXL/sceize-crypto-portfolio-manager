# 🚀 Sceize Crypto Portfolio Manager

Gestionnaire de portfolio crypto personnel, multi-exchange et multi-blockchain, auto-hébergé.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-blue.svg)
![Python](https://img.shields.io/badge/Python-3.11-green.svg)

## ✨ Fonctionnalités

- 📊 **Multi-Exchange** : Binance, Bitget, BingX, Hyperliquid, Lighter
- ⛓️ **Multi-Blockchain** : Ethereum, Bitcoin, Solana, Polygon, BSC, Base, et plus
- 💎 **DeFi** : AAVE, Morpho, Aerodrome, Pendle
- 📈 **Analyse Technique** : Supports/Résistances, Fibonacci
- 🔔 **Alertes** : Prix, S/R, APR/APY, ordres exécutés
- 💼 **Trading** : Historique complet, P&L en temps réel
- 🔒 **Confidentialité** : Auto-hébergé, vos données restent chez vous

## 🏗️ Architecture

- **PostgreSQL 16** : Base de données
- **Python 3.11** : Backend et collecteurs
- **Streamlit** : Interface web (à venir)
- **Docker** : Déploiement via Portainer

## 🚀 Installation

### Prérequis

- Docker + Docker Compose
- PostgreSQL 16
- Python 3.11+

### Étapes

1. Clonez le repo
```bash
git clone https://github.com/votre-username/sceize-crypto-portfolio-manager.git
cd sceize-crypto-portfolio-manager
```

2. Créez la base de données
```bash
# Via pgAdmin ou psql
psql -U crypto_user -d crypto_tracker < database/schema.sql
```

3. Configurez l'environnement
```bash
cp .env.example .env
nano .env  # Modifiez avec vos identifiants
```

4. Lancez le collecteur de prix
```bash
cd scripts
pip install -r requirements.txt
python price_collector.py
```

## 📊 Cryptos suivies

- Bitcoin (BTC)
- Ethereum (ETH)
- Bittensor (TAO)
- Hyperliquid (HYP)
- BNB (BNB)
- Aave (AAVE)

## 🔐 Sécurité

⚠️ **Important** : Ce projet est conçu pour un usage personnel auto-hébergé.

- Clés API en **lecture seule** uniquement
- **Restriction IP** sur toutes les clés API
- **Pas d'exposition publique** sans VPN
- Chiffrement des clés sensibles

## 📝 Licence

MIT License - Voir [LICENSE](LICENSE)

## 👤 Auteur

**Sceize**

## 🤝 Contribution

Ce projet est personnel, mais les suggestions sont les bienvenues !

---

⭐ Si ce projet vous aide, n'hésitez pas à mettre une étoile !
