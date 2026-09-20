# UppSkill — coaching bureautique

Site vitrine statique (HTML / CSS / JS, sans build) hébergé sur GitHub Pages,
domaine `uppskill.shop`.

> Généré depuis `C:\Users\souha\coaching-sites-factory` (fichier `sites/uppskill.mjs`).
> Pour une modification de contenu, éditez ce fichier puis relancez `node build.mjs uppskill` :
> une modification faite directement ici serait écrasée à la prochaine génération.

## À compléter avant de communiquer sur le site

| Priorité | Quoi | Où |
|---|---|---|
| 🔴 Bloquant | Mentions légales : identité de l’éditeur, SIREN, adresse, médiateur. Obligatoire en France. | `mentions-legales.html` |
| 🟠 Important | Adresse `contact@uppskill.shop` : créer une redirection e-mail chez Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Formulaire : remplacer `VOTRE_ID_FORMSPREE` (sinon repli automatique en `mailto:`). | `contact.html` |
| 🟠 Important | Présentation de la personne qui coache (nom, parcours réel, photo). | `a-propos.html` |
| 🟡 Plus tard | Tarifs (35 / 89 / 179 €) et contenu des formules à ajuster à votre offre réelle. | `index.html` `#tarifs` |
| 🟡 Plus tard | Témoignages : n’en ajoutez que des vrais, avec l’accord des personnes. | — |

## Description de l’activité (Stripe, annuaires…)

```
Coaching en bureautique, 100 % en ligne : séances individuelles en visioconférence et ateliers en petit groupe portant sur Excel (des bases aux tableaux croisés dynamiques et aux formules de recherche), Word et la mise en forme de documents longs, et PowerPoint et la conception de présentations. Les participants suivent un programme de 6 à 10 semaines construit sur leurs propres fichiers, avec des retours écrits sur les documents qu’ils envoient. Aucune licence logicielle n’est vendue. Les prestations sont vendues sous forme d’abonnements mensuels sans engagement, de 35 € à 179 € par mois, résiliables à tout moment. Aucun produit physique n’est vendu ni expédié. Site : uppskill.shop
```

## Structure

```
index.html            Accueil : hero, programmes, méthode, tarifs, approche, FAQ
programmes.html       Détail des 4 programmes
a-propos.html         Notre approche et principes
contact.html          Formulaire de prise de contact
mentions-legales.html Mentions légales, confidentialité, CGV
404.html              Page d’erreur (chemins absolus)
assets/css/style.css  Couleurs de la marque en tête de fichier, puis styles communs
assets/js/main.js     Menu, thème, animations, formulaire
```

## DNS (Namecheap → Advanced DNS)

Supprimer les enregistrements de parking, puis :

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
