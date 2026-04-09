# 📚 Système de Gestion de Cours en Ligne
### Conception Orientée Objet — UML

> Mini-projet de modélisation UML d'une plateforme d'e-learning intelligente et sécurisée.

---

## 🎯 Présentation

Ce projet propose la **conception complète** d'une plateforme d'apprentissage en ligne intégrant l'intelligence artificielle à tous les niveaux. L'objectif est de répondre aux limites des plateformes éducatives actuelles : contenus non contrôlés, parcours standardisés, communications non sécurisées.

La solution conçue offre un environnement **éducatif, sécurisé et personnalisé**, modélisé à l'aide d'UML (Unified Modeling Language).

---

## 👥 Acteurs du système

| Acteur | Rôle |
|--------|------|
| **Apprenant** | Consulte les cours, passe des quiz, suit sa progression |
| **Formateur** | Crée et gère les formations, suit les apprenants |
| **Administrateur** | Supervise la plateforme, gère les infractions |
| **Système IA** | Analyse les contenus, surveille les communications, personnalise l'apprentissage |

---

## ⚙️ Fonctionnalités principales

- 🎓 Gestion des formations gratuites et payantes (modules, ressources multimédia)
- 🔐 Classrooms sécurisées avec codes d'accès et gestion des permissions
- 🤖 IA intégrée : analyse de contenu, surveillance des chats, quiz adaptatifs
- 📊 Tableau de bord de progression avec statistiques détaillées
- 🛡️ Système d'infractions progressif (avertissement → suspension → bannissement)
- 💳 Paiement intégré et génération automatique de certificats

---

## 📐 Diagrammes UML réalisés

| # | Diagramme | Description |
|---|-----------|-------------|
| 1 | **Cas d'utilisation** | Interactions acteurs / système |
| 2 | **Classes** | Structure statique (6 domaines fonctionnels, 25+ classes) |
| 3 | **Objets** | Instantané concret du système en fonctionnement |
| 4 | **Séquences** | 3 scénarios : publication filtrée par IA, chat surveillé, quiz adaptatif |
| 5 | **Paquetages** | Architecture modulaire en 7 paquetages |
| 6 | **Composants** | Architecture 3-tiers du système |
| 7 | **États-transitions** | Cycle de vie complet d'un cours |
| 8 | **Activités** | Processus global d'apprentissage (inscription → certification) |

---

## 🏗️ Architecture modulaire

```
Utilisateur       →  Apprenant, Formateur, Administrateur
Formation         →  Modules, Ressources (Vidéo, PDF, Audio, Image)
Évaluation        →  Quiz adaptatifs, Questions, Résultats
Communication     →  Chat surveillé, Publications, Bibliothèque
Suivi             →  Progression, Inscription, Paiement, Recommandations
IA & Sécurité     →  SystemeIA, Infractions, Liste de surveillance
```

---

## 🛠️ Technologies et outils

- **Langage de modélisation** : UML 2.x
- **Logiciel** : Visual Paradigm CE (Community Edition)
- **Implémentation de référence** : C++ (code fourni pour chaque classe)
- **Méthodologie** : Conception orientée objet

---

## 📄 Document

📎 [`NassiraHamich-prjUml.pdf`](./NassiraHamich-prjUml.pdf) — Rapport complet (34 pages)

---

## 👩‍💻 Auteure

**Nassira Hamich**
Filière : Informatique et Intelligence Artificielle
Faculté Pluridisciplinaire de Nador — Université Mohammed Premier
Année universitaire : 2025–2026

Supervisé par : **Pr. Anas EL ANSARI**

---

## 📝 Licence

Projet académique — tous droits réservés © 2025 Nassira Hamich
