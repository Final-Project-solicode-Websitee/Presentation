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
    left: 60px;
    right: 60px;
  }
  .logo-header img { height: 140px; margin: 0; }
  h1 { color: #088dc7; font-size: 2.8em; margin-top: 100px; }
  h2 { color: #088dc7; font-size: 2em; border-bottom: 2px solid #088dc7; margin-bottom: 40px;}
  
  /* Nouveau Style Sommaire Moderne */
  .sommaire-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin-top: 20px;
  }
  .sommaire-item {
    display: flex;
    align-items: center;
    background: #f4faff;
    border-radius: 12px;
    padding: 15px 20px;
    border-left: 5px solid #088dc7;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
  }
  .sommaire-num {
    background: #088dc7;
    color: white;
    width: 35px;
    height: 35px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
    font-weight: bold;
    margin-right: 15px;
    flex-shrink: 0;
  }
  .sommaire-text {
    font-size: 1.1em;
    font-weight: 600;
    color: #3d3d3d;
  }
  .highlight { color: #088dc7; font-weight: bold; }
---

<div class="logo-header">
  <img src="images/ofppt-logo.png" alt="Logo Left">
  <img src="images/logo-solicode.png" alt="Logo Right">
</div>

# **Présentation Fin Foarmation**

**Réalisé par :** <span class="highlight">Ben Taleb Mehdi</span>  
**Encadré par :** <span class="highlight">M. ESSARRAJ Fouad</span>  
**Date :** 20 / 02 / 2026

---

## Sommaire

<div class="sommaire-grid">
  <div class="sommaire-item">
    <div class="sommaire-num">1</div>
    <div class="sommaire-text">Introduction et Contexte</div>
  </div>
  <div class="sommaire-item">
    <div class="sommaire-num">2</div>
    <div class="sommaire-text">Analyse des Besoins</div>
  </div>
  <div class="sommaire-item">
    <div class="sommaire-num">3</div>
    <div class="sommaire-text">Conception & Architecture</div>
  </div>
  <div class="sommaire-item">
    <div class="sommaire-num">4</div>
    <div class="sommaire-text">Réalisation Technique</div>
  </div>
  <div class="sommaire-item">
    <div class="sommaire-num">5</div>
    <div class="sommaire-text">Démonstration (Live)</div>
  </div>
  <div class="sommaire-item">
    <div class="sommaire-num">6</div>
    <div class="sommaire-text">Conclusion & Perspectives</div>
  </div>
</div>

---

## 1. Introduction & Contexte

Le projet consiste en la création d'une plateforme **Mini E-Commerce** permettant la gestion fluide d'un inventaire.

* **Problématique** : Comment organiser efficacement des produits par catégories ?
* **Solution** : Une interface CRUD liée à une base de données relationnelle.

---



## 3. Conception : Architecture du Système

Le développement de l'application repose sur les piliers suivants :

1. **Backend** : Création des APIs robustes pour les Produits et Catégories.
2. **Frontend** : Interface de gestion dynamique et responsive.
3. **Relation** : Mise en place d'une liaison **Many-to-One**.