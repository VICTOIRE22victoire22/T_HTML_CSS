# Progression du module HTML/CSSS

## Iconographie

* cours: 📘
* théorie: 📖
* exercice: ✏️
* supports & documents: 📚
* méthodologie : 📝
* configuration: ⚙️
* objectifs : 🎯
* concept: 💡
* projet: 📦
* dossier : 📁
* fichier : 📄
* tp: 🛠️

### 📅 ***SEMAINE 1 (17.03.25 au 21.03.25)***

⏳ `lundi 17.03.25`

🕒 **Matin (09h00 - 13h00)**

* ⚙️ Paramétrage du nuage `Pcloud` utilisé pour héberger dossiers + fichiers du module de formation.
* ⚙️ Installation de `Visual Studio Code` et des extensions nécessaires pour le développement web.
* ⚙️Configuration d'un compte sur `github.com`
* ⚙️ Présentation de la syntaxe `Markdown` :
  * 📁 `html_css_methodologies`
  * 📄 markdown.md

🕒 **Après-midi (14h00 - 17h00)**

---

⏳ `mardi 18.03.25`

🕒 **Matin (09h00 - 13h00)**

* 💡**balises sémantiques**
  * `<section>`, `<article>`,

🕒 **Après-midi (14h00 - 17h00)**

* 💡**box-model**
  * `box-sizing: border-box`
  * `box-sizing: box-content`

---

⏳ `mercredi 19.03.25`

🕒 **Matin (09h00 - 13h00)**

* sélecteurs css (`id`, `class`, `>`, `+`, `~`)
* 💡**positionnement**
  * `relative`
  * `absolute`
* implémentation d'un `reset.css`

🕒 **Après-midi (14h00 - 17h00)**

* 💡 **tableaux**
  * `caption`, `colgroup`, `col`
  * `thead`,`th`, `tr`, `td`, `tbody`, `tfoot`	

* ✏️Codage d'un composant hero (hero.html)

---

⏳ `jeudi 20.03.25`

🕒 **Matin (09h00 - 13h00)**

* 🛠️ TP
  * codage d'un site statique sans flexbox ni css grid.
  * reset css
  * nomenclature BEM
  * sélecteurs css
  * balises sémantiques
  * positionnement (relative, absolute)

🕒 **Après-midi (14h00 - 17h00)**

* 🛠️ TP
  * codage d'un site statique sans flexbox ni css grid.
  * reset css
  * nomenclature BEM
  * sélecteurs css
  * balises sémantiques
  * positionnement (relative, absolute)

---

⏳ `vendredi 21.03.25`

🕒 **Matin (09h00 - 13h00)**

* 📘 Correction du TP (1h30)
  * focus sur les points bloquants
  * correction html, css
  * disposition, design
  * bonnes pratiques

* ✏️ Formulaire : design un formulaire from scratch
  * balises `<form>`, `<fieldset>`, `<legend>`, `<input>`, `<label>` 
  * sélection css d'un attribut en fonction du type de champ.

🕒 **Après-midi (14h00 - 17h00)**

* ✏️ Formulaire : design un formulaire from scratch
  * balises `<form>`, `<fieldset>`, `<legend>`, `<input>`, `<label>` 
  * attributs `type`, `name`, `value`, `placeholder`, `required`, `disabled`, `readonly`, `checked`, `for`
  * pseudo-classes `:focus`, `:hover`, `:active`

### 📅 ***SEMAINE 3 (24.02325 au 28.03.25)***

⏳ `lundi 24.03.25`

🕒 **Matin (09h00 - 13h00)**

* 📖 -  **FLEXBOX**
  * Propriétés appliquées sur le **parent** (flex-container)
    * `display : flex`
    * `flex-wrap`
    * `justify-content`
    * `align-items`
  * Propriétés appliquées sur l'**enfant**  (flex-item)
    * `align-self`
* ✏️ :  codage d'une barre de navigation en flexbox

🕒 **Après-midi (14h00 - 17h00)**

* ✏️ : card en Flexbox
  * card en `flex-direction: column`
  * positionnement avec `align-self`
  * conteneur flex pour 3 cards.

---

⏳ `mardi 25.03.25`

🕒 **Matin (09h00 - 13h00)**

* 📘  Cours interactif **FLEXBOX** (résumé et synthèse de la journée d'hier)
* 📖  **CSS GRID** 
  * `display : grid`
  * `grid-template-columns : 100px repeat(4, 1fr)`
  * `grid-template-rows : auto`
  * `grid-row`, `grid-colums`, `grid-area`
* ✏️ : codage d'un layout (de site web) simple (**layout1.html**)  en css grid avec `grid-template-columns`
* ✏️ : codage d'un layout (de site web) plus complexe (**layout2.html**) en css grid avec `grid-area`

🕒 **Après-midi (14h00 - 17h00)**

* 📖  **CSS GRID** 

  * `grid-template-areas`

  ✏️ : codage d'un layout (**layout3.html**) avec les zones de grille `grid-template-areas`.

  ✏️ : codage d'une galerie d'images en css grid (galerie du site [ikea.fr](https://www.ikea.fr)).

---

⏳ `mercredi 26.03.25`

🕒 **Matin (09h00 - 13h00)**

* Correction de la galerie d'images en CSS grid.

* 📖  **RWD (Responsive Web Design)**

  * hack `font-size : 62.5%` pour **l'accessibilité** web + utilisation des unités `rem`

  * `media-queries`

    * approche **desktop-first** :

    ```css
    @media screen and (max-width:500px) {
    /* Code css qui sera interprté par le navigateur par tous les écrans dont le viewport est d'AU-PLUS 500px */ 
    }  
    
    @media screen and (max-width:800px) {
    /* Code css qui sera interprté par le navigateur par tous les écrans dont le viewport est d'AU-PLUS 800px */ 
    }
    
    @media screen and (max-width:1200px) {
    /* Code css qui sera interprté par le navigateur par tous les écrans dont le viewport est d'AU-PLUS 1200px */ 
    }
    ```

* approche **mobile-first**

  ```css
  @media screen and (min-width:500px) {
  /* Code css qui sera interprté par le navigateur par tous les écrans dont le viewport est d'AU-MOINS 500px */ 
  }
  
  @media screen and (min-width:800px) {
  /* Code css qui sera interprté par le navigateur par tous les écrans dont le viewport est d'AU-MOINS 800px */ 
  }
  
  @media screen and (min-width:1200px) {
  /* Code css qui sera interprté par le navigateur par tous les écrans dont le viewport est d'AU-MOINS 1200px */ 
  }
  ```
  
  * ✏️ Codage d'un template de site avec l'approche **desktop-first**.
  
  🕒 **Après-midi (14h00 - 17h00)**
  
  * ✏️ Codage du même template de site avec l'approche  **mobile-first**.
  * 📖 Bonnes pratiques en Responsive Web Design :
    * image responsive : `max-width: 100% et height: auto`
    * Utiliser les `CSS Grid` pour la structure du site
    * Utiliser `Flexbox` pour la structure des composants.
    * font-size: 62.5% sur la balise `<html>`.
    * `font-size: font-size: clamp(16px, calc(14px + 1.2vw), 40px);`
    * media-queries avec des unités `em`
    * Adopter de préférence l'approche **mobile-first** pour le code css.

---

⏳ `jeudi 27.03.25`

🕒 **Matin (09h00 - 13h00)**

* 🛠️ TP
  * codage d'un site statique responsive avec CSS GRID + FLEXBOX

🕒 **Après-midi (14h00 - 17h00)**

* 🛠️ TP
  * codage d'un site statique responsive avec CSS GRID + FLEXBOX

---

⏳ `vendredi 28.03.25`

🕒 **Matin (09h00 - 13h00)**

* Correction du TP
* 💡**grille auto-responsives**
  * auto-fit : `grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));`
  * auto-fill : `grid-template-columns: repeat(auto-fill, minmax(230px, 1fr));`

* 📝 : publier son site sur internet
  * github :  https://www.github.com
  * netlify : https://www.netlify.com


🕒 **Après-midi (14h00 - 17h00)**

* 💡**Boostrap**
  * implémentation rapide
  * 