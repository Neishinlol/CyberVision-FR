# CyberVision – Journal des modifications (FR)

Tous les changements notables du projet sont documentés ici.  
Pour des résumés rapides, consultez Discord et Nexus.  
Ce fichier fait office de source principale et complète.

## [1.1.1] – Refonte Visuelle

### ⚙️ Rework de l'ENV et Reshade
- Les valeurs de l'exposition avaient des problèmes en path tracing pour une raison que j'ignore, j'ai retravaillé CyberVisionENV.
-  Visuels beaucoup plus beaux et moins de yoyo sur les valeurs d'exposition.
- Avant de mettre à jour, pensez à sauvegarder votre UserSettings.json afin d’éviter de refaire tous vos binds.
-  Chemin : CyberVision → Profiles → Profil choisi → UserSettings.json
- Pas de problème pour vos sauvegardes.

---

## [1.1.0] – Mise à jour majeure d’optimisation

### ⚙️ Optimisations générales
- Passage d’optimisation majeur ciblant les mods dépendants de CET.
- Réduction importante des stutters réguliers, en particulier sur les configurations low et medium.
- Les stutters ont été quasiment éliminés au prix de la suppression de plusieurs mods non essentiels.
- ⚠️ **Probablement pas save-friendly** : une nouvelle partie est fortement recommandée.

**Important**
- Avant de mettre à jour, pensez à sauvegarder votre `UserSettings.json` afin d’éviter de refaire tous vos binds.  
  Chemin : `CyberVision → Profiles → Profil choisi → UserSettings.json`

---

### 🔄 Mise à jour des mods & ajouts

**Nouveau**
- Non-Intrusive Minimap

**Correctifs**
- Deceptious Bug Fix

**Tenues & Armes**
- The RVCOON Dumpster 3  
- Virtual Atelier  
- Veegee Shop 3  

**Véhicules**
- Void Lotus Esprit  

**Ajout**
- Rent a Motel  

**Traductions françaises**
- Virtual Car Dealer  
- APEX Sonora Canyon  

---

### ❌ Mods supprimés (stabilité des performances)
- Autoloot  
- Clean Effects  
- CorruptNCPD  
- CustomBlackWall  
- CyberwareStatsControl  
- No Cyberware Cost  
- Ricochet  
- Skip Anything  
- Smart Aim for Head  
- Stealth Runner  
- Taxi Work in Night City  
- Lean Anywhere / Sit Anywhere  
- Unlock Night City  
- SongBird Apartment  
- Vehicle Customizer  
- Time and Weather Aware – River Ward  
- Time and Weather Aware – Goro Takemura  
- Time and Weather Aware – Jackie Welles  
- Sexual Encounters – Clouds Nude Patch  
- Game v2.0 Patch – Quick Message Exit  
- Filter Saves by Lifepath and Type  
- Sandevistan Customization – Time Dilation  
- 1995 Porsche 993 RWB Rotana  

---

### 🔄 Remplacements pour améliorer la stabilité
- Ultra Plus **8.2 → 7.6**  
- Better Sleeves → Sleeves  
- Realistic Traffic Density **Very High → Ultra preset**  

---

### 🚗 Optimisation des véhicules (nettoyage des bin)
Désactivation de fichiers `.bin` inutiles sur certains mods de véhicules afin de réduire l’empreinte CET.  
Les couleurs sont désormais gérées via **CrystalCoat**.

Véhicules concernés :
- BMW M4 CS 2018  
- Porsche 911 Targa 4 GTS 2025  
- 2019 Toyota Corolla  
- Ferrari F40 ZEPHYR  
- Ferrari F40 LB Works  
- Genesis X Gran Berlinetta  
- Mazda RX7 Fortune (Fast & Furious)  
- Mazda RX7 Initial D Stage 5  
- Mazda RX7 WBK  
- Mazda RX7 FD  
- 2021 Mercedes AMG  
- Nillu 27  
- Porsche 996 GT3  
- Porsche Singer 911 Armored  
- Volkswagen Super Beetle  
- Quadra Type-66 Phantom  

---

### 📦 Tweaks & Presets
- Ajustements de la caméra des pistolets et de certains véhicules.
- Preset **RT/PT ShadowFix** appliqué en véhicule (corrige les ombres sur les bras).
- Ajustement ReShade : réduction de la valeur des highlights.
- Nettoyage des dossiers du load order.
- Mise à jour de tous les profils pour correspondre aux nouveaux FOMODs.

---

## [1.0.1] – Correctifs & stabilité

### ⚙️ UserSettings
- Activation de **Color Precision** par défaut dans les `UserSettings`.  
  - Corrige les problèmes de fondu en cutscene et l’écran blanc type flashbang.
- Il s’agit de la **dernière mise à jour modifiant les UserSettings**.  
  Pensez à sauvegarder votre fichier pour les futures versions.

---

### 🔄 Mise à jour des mods

**Correctifs**
- CET NPC Body Tweaks  
- Autoloot  

**Graphismes**
- Improved Vegetation LOD  
- General Shadow Fix  

**Tenues & Armes**
- Yusei's Virtual Atelier  
- NC Fashion Virtual Atelier  
- Sabbath Virtual Atelier  

**Lieux**
- Pacifica Apartment  
- Downtown Yacht  
- Corpo Rooftop Bar  
- Dogtown Car Meet  

**Ajouts**
- Lizzie Braindance  
- HotScenes  

---

### ❌ Supprimés
- Immersive Shooting AI (équilibrage & performances)
- Enemy Aggro Improvements (mauvaise intégration globale)
- Enemy Rarity Fixes (déjà géré ailleurs)
- Suppression de nombreux téléchargements oubliés afin de réduire le poids global de la modlist

---

### 🚀 Performances
- Ajustements mineurs pour améliorer les performances globales
- Réduction des micro-saccades sur les configurations faibles et moyennes
