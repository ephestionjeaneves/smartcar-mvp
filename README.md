# 🚗 SmartCar-MVP – Projet connecté auto (Jean-Eves)

## 🎯 Objectif
Développer un module embarqué **légal et sûr** permettant de :
- Lire les données OBD-II (RPM, vitesse, température, tension batterie)
- Envoyer les infos vers une application mobile (Bluetooth / Wi-Fi)
- Tester plus tard l’intégration d’un **démarrage à distance autorisé**
- Servir de base à un futur produit local (diagnostic + confort)

## 📅 Étapes principales
| Étape | Description | Statut |
|:--|:--|:--:|
| 1 | Initialisation du projet et du repo Git | ✅ |
| 2 | Premier test ESP32 (Blink + Serial) | ⬜ |
| 3 | Commande des composants AliExpress | ⬜ |
| 4 | Test lecture OBD sur véhicule (avec Autel) | ⬜ |
| 5 | Lecture PID sur ESP32 via OBD | ⬜ |
| 6 | Envoi BLE/Wi-Fi vers appli mobile simple | ⬜ |
| 7 | Documentation / vidéo démo | ⬜ |

## 🔧 Stack & outils
- **Matériel** : ESP32 DevKit V1, MCP2515 CAN + TJA1050, câble OBD-II mâle
- **Langages** : C++ (Arduino), Python (scripts)
- **Logiciels** : Arduino IDE, VS Code + PlatformIO, Git/GitHub
- **Mobile (plus tard)** : Flutter / React Native

## 📁 Arborescence
smartcar-mvp/
├── README.md
├── docs/
│ └── notes_tests_autel.md
├── src/
│ ├── main.cpp
│ └── obd_test.cpp
└── data/
├── logs/
└── csv/

markdown
Copier le code

## 🧠 Idée business
À moyen terme, proposer localement un **kit de télémétrie & confort auto** :
- Diagnostic simple via téléphone
- Historique maintenance
- (Option) Démarrage à distance légal
- Service d’installation local (garages partenaires)

## ✅ Règles du projet
- Toujours avec autorisation du propriétaire du véhicule  
- Aucune désactivation d’immobiliser / antivol  
- Sécurité réseau : communication chiffrée (TLS/BLE secure)  
- Documentation rigoureuse de chaque test  

---

## 🏁 Suivi de progression
- [ ] Initialisation OK  
- [ ] Premier blink ESP32  
- [ ] Achat AliExpress validé  
- [ ] Lecture OBD simple réussie  
- [ ] Comparaison Autel / module  
- [ ] Envoi data vers mobile  
- [ ] Présentation projet (PowerPoint + démo vidéo)
