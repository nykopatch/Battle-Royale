# BR Manager — Battle Royale Demi-fond

Application web progressive (PWA) pour gérer les séances Battle Royale.

## Déploiement sur GitHub Pages (5 minutes)

1. **Crée un nouveau dépôt GitHub** (public) : https://github.com/new  
   → Nom suggéré : `br-manager`

2. **Upload les fichiers** dans ce dépôt :
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/icon-192.png`
   - `icons/icon-512.png`

   *(Menu "Add file" → "Upload files" sur GitHub)*

3. **Active GitHub Pages** :  
   Réglages du dépôt → Pages → Source : **main** / **root** → Save

4. **Ton URL** sera :  
   `https://TON-PSEUDO.github.io/br-manager/`

## Installation sur iPhone / iPad

1. Ouvre l'URL dans **Safari**
2. Tape l'icône **Partager** (carré avec flèche)
3. → **Sur l'écran d'accueil**
4. L'app s'installe et fonctionne hors-ligne 📱

## Fonctionnalités V1

- ✅ Multi-classes (5ème, 6ème, etc.)
- ✅ Import élèves par CSV / saisie manuelle
- ✅ Gestion des absents par course
- ✅ Saisie du classement par ligue (tap-to-assign)
- ✅ Chasseur automatique (+2 pts/élimination)
- ✅ Barème linéaire dynamique : 1er = N présents → dernier = 1 pt
- ✅ Promotions / relégations (configurables, par course ou fin de leçon)
- ✅ Tableau de classement cumulé avec filtres
- ✅ Ajustements manuels de points
- ✅ Export CSV + partage texte
- ✅ Sauvegarde JSON (backup local)
- ✅ Missions configurables (activables par classe)
- ✅ Fonctionne hors-ligne

## Barème

Linéaire par ligue : si N élèves sont présents dans une ligue ce jour-là,  
le 1er = N points, le 2e = N-1, ..., le dernier = 1 point.  
Chasseur : +2 points par élimination.

## Format CSV pour l'import

```
NOM,Prénom,Ligue
DUPONT,Marie,1
MARTIN,Paul,2
```
La 3e colonne (ligue) est optionnelle, défaut = Ligue 1.
