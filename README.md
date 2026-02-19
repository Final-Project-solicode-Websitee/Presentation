---
marp: true
theme: default
_class: lead
paginate: true
backgroundColor: #ffffff
style: |
  section {
    font-size: 22px;
    color: #333;
    line-height: 1.6;
    padding: 60px 80px;
  }
  .logo-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: absolute;
    top: 40px;
    left: 40px;
    right: 40px;
  }
  .logo-header img { height: 70px; margin: 0; }
  h1 { color: #088dc7; font-size: 2.8em; margin-top: 100px; }
  h2 { color: #088dc7; font-size: 2em; border-bottom: 2px solid #088dc7; margin-bottom: 40px;}
  
  /* Style spécifique pour le sommaire */
  .sommaire ol {
    list-style: none;
    counter-reset: item;
    padding-left: 0;
  }
  .sommaire li {
    counter-increment: item;
    margin-bottom: 20px;
    font-size: 1.3em;
    font-weight: 500;
  }
  .sommaire li::before {
    content: counter(item) ". ";
    color: #088dc7;
    font-weight: bold;
    margin-right: 15px;
  }
  .highlight { color: #088dc7; font-weight: bold; }
---

<div class="logo-header">
  <img src="https://via.placeholder.com/150x70?text=LOGO+1" alt="Logo Left">
  <img src="https://via.placeholder.com/150x70?text=LOGO+2" alt="Logo Right">
</div>

# **Présentation Projet-technique**
### Mini E-Commerce (Product, Categories)

**Réalisé par :** <span class="highlight">Ben Taleb Mehdi</span>  
**Encadré par :** <span class="highlight">M. ESSARRAJ Fouad</span>  
**Date :** 05 / 01 / 2026

---

## 📋 Sommaire

<div class="sommaire">

1. Introduction et Contexte du Projet
2. Analyse des Besoins (Cahier des charges)
3. Conception et Architecture (MCD/MLD)
4. Réalisation Technique (Stack & Code)
5. Démonstration de l'Application
6. Conclusion et Perspectives

</div>

---

## 🎯 1. Introduction & Contexte

Le projet consiste en la création d'une plateforme **Mini E-Commerce** permettant la gestion fluide d'un inventaire.

* **Problématique** : Comment organiser efficacement des produits par catégories ?
* **Solution** : Une interface CRUD (Create, Read, Update, Delete) liée à une base de données relationnelle.

---



[Image of E-commerce database schema diagram]


## 🛠️ 3. Conception : Architecture du Système

Le développement de l'application repose sur les piliers suivants :

1. **Backend** : Création des APIs robustes pour les Produits et Catégories.
2. **Frontend** : Interface de gestion dynamique et responsive.
3. **Relation** : Mise en place d'une liaison **Many-to-One** (Plusieurs produits pour une catégorie).