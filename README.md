# Newsletter Parfums d’Olive

Ce dépôt contient une première version simple et propre d’une page d’acceptation newsletter pour Parfums d’Olive.

## Fichiers créés

- `index.html` : page principale avec le bouton **J’accepte de recevoir la newsletter**.
- `confirmation-newsletter.html` : page de confirmation visuelle.

## Fonctionnement actuel

Le bouton ouvre un email prérempli vers :

`contact@parfumsdolive.com`

Objet :

`J’accepte de recevoir la newsletter Parfums d’Olive`

Ce fonctionnement permet d’obtenir une trace claire du consentement sans base de données ni automatisation complexe.

## Limite importante

Cette version ne connecte pas encore automatiquement l’inscription à Brevo ou à un CRM.

Pour une vraie automatisation, il faudra ensuite connecter le bouton/formulaire à l’un de ces systèmes :

- formulaire Brevo intégré ;
- Google Form + Google Sheet ;
- formulaire du site web ;
- outil type Zapier / Make ;
- mini backend ou fonction serverless.

## Charte graphique utilisée

- Vert olive profond : `#2d4a3c`
- Or / ocre doux : `#c4a158`
- Crème / ivoire : `#f5efe7`
- Blanc : `#ffffff`
- Anthracite : `#2c3e3f`
