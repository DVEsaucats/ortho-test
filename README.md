# Orthophotographies SOMECA – Callas

Ce dépôt contient des orthomosaïques générées par drone, consultables en ligne via Leaflet ou intégrables dans QGIS via XYZ Tiles.

## 🔗 Accès rapide

- **Visualisation web** : [leaflet.html](https://dvesaucats.github.io/ortho-test/leaflet.html)
- **URL XYZ QGIS** : `https://dvesaucats.github.io/ortho-test/tiles/{z}/{x}/{y}.png`

## 🛠️ Utilisation dans QGIS

1. Ouvrir le panneau `Explorateur`
2. Clic droit sur `XYZ Tiles` > `Nouvelle connexion`
3. Nom : `Orthomosaïque`
4. URL : `https://dvesaucats.github.io/ortho-test/tiles/{z}/{x}/{y}.png`
5. Valider > glisser dans la carte

## 📁 Structure

```
📂 tiles/
   ├─ 16/
   ├─ 17/
   └─ ...
📄 leaflet.html
📄 tilemapresource.xml
```
