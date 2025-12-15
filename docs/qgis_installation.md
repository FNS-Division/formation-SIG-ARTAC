# Désinstallation de QGIS

Instructions pour désinstaller proprement QGIS selon votre système d’exploitation.

## 🪟 Windows

### Désinstallation
1. Fermez **QGIS**
2. Ouvrez **Paramètres → Applications → Applications installées**
3. Recherchez **QGIS**
4. Cliquez sur **Désinstaller**
5. Suivez l’assistant

## 🍎 macOS

### Désinstallation
1. Fermez **QGIS**
2. Ouvrez le dossier **Applications**
3. Faites glisser **QGIS.app** vers la **Corbeille**
4. Videz la corbeille

# Installation de QGIS

QGIS est un logiciel libre et gratuit de système d'information géographique (SIG). Pour cet atelier, nous utiliserons **QGIS version 3.34.11 'Prizren LTR'** (version à long terme).

## Téléchargement

### Windows
1. Téléchargez [QGIS Standalone Installer Version 3.34 (LTR)](https://drive.google.com/file/d/1ZM7Tb_ZV5cQ8_stJ30UP7jHk0tsJTPf1/view?usp=sharing)
2. Suivez les instructions d'installation (acceptez les paramètres par défaut)

### macOS
1. Téléchargez [QGIS macOS Installer Version 3.34 (LTR)](https://qgis.org/downloads/macos/qgis-macos-pr.dmg)
2. Glissez l'icône QGIS dans le dossier Applications

# Installation des plugins QGIS

Les plugins étendent les fonctionnalités de QGIS. Pour cet atelier, nous utiliserons trois plugins essentiels.

## Comment installer un plugin

1. Ouvrez QGIS
2. Allez dans le menu **Extensions > Installer/Gérer les extensions**
3. Cliquez sur l'onglet **Tout** dans la fenêtre qui s'ouvre
4. Utilisez la barre de recherche pour trouver le plugin
5. Sélectionnez le plugin dans la liste
6. Cliquez sur **Installer l'extension**
7. Attendez la fin de l'installation (une barre de progression apparaît en bas)

## Plugins requis pour l'atelier

### 1. QuickMapServices
**Utilité :** Ajoute rapidement des fonds de carte (Google Maps, OpenStreetMap, etc.)

**Installation :**
1. Recherchez `QuickMapServices`
2. Installez le plugin

### 2. QuickOSM
**Utilité :** Télécharge et importe des données d'OpenStreetMap directement dans QGIS

**Installation :**
1. Recherchez `QuickOSM`
2. Installez le plugin
3. Le plugin apparaîtra dans le menu **Vecteur > QuickOSM**

### 3. QNEAT3
**Utilité :** Analyse de réseaux et calcul d'itinéraires optimaux

**Installation :**
1. Recherchez `QNEAT3`
2. Installez le plugin
3. Le plugin apparaîtra dans le menu **Traitement** (Processing)