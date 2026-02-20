# tonparcours.fr • Aide pour l'orientation sur parcoursup

TonParcours.fr est un outil interactif conçu pour aider les lycéens à explorer les formations post-bac. À travers un questionnaire simple, l'utilisateur reçoit une sélection de formations Parcoursup compatibles avec son profil, ses centres d'intérêt et ses résultats scolaires.

![Image description](https://github.com/YoussefBechara/tonparcours.fr/blob/main/indeximage.jpeg)
🔒 Aucune donnée personnelle n'est collectée ou stockée. Tout fonctionne en local, dans le navigateur.

---

## ✨ Fonctionnalités

- **Questionnaire dynamique** pour affiner les souhaits d'orientation
- **Moteur de recommandation** basé sur un système de scoring JSON
- **Affichage des formations compatibles** avec intitulé, université, ville, et taux d'admission (simulé)
- **100% statique** – Pas de serveur, pas de base de données externe
- **Aucune collecte de données** – Tout reste sur votre machine

---

## 🛠️ Technologies utilisées

- HTML5 / CSS3 / JavaScript (Vanilla)
- JSON pour les données et les règles de scoring
- Hébergement : GitHub Pages

---

## 🧠 Comment ça marche ?

1. L'utilisateur répond à une série de questions (type de bac, spécialités, centres d'intérêt...)
2. Les réponses sont comparées à une base de données locale (fichier JSON intégré au code)
3. Un algorithme de scoring attribue un niveau de compatibilité avec chaque formation
4. Les formations les plus pertinentes sont affichées dynamiquement

---

## 🚀 Installation / Utilisation locale

```bash
# Cloner le dépôt
git clone https://github.com/youssefbechara/parcoursup-guidance.git

# Se rendre dans le dossier
cd parcoursup-guidance

# Ouvrir directement index.html dans votre navigateur
# ou lancer un serveur local (ex: Live Server)
```

Aucune dépendance à installer. Aucune clé API à configurer.

---

## 📌 À venir (idées d'évolution)

- Filtrer par région / académie
- Ajouter des statistiques sur les débouchés
- Interface plus ludique (cartes, sliders...)

---

## 👤 Auteur

**Youssef Bechara**  
Étudiant en double licence eco/info/ia.

- GitHub : [@youssefbechara](https://github.com/youssefbechara)
