# Déclaration d'accessibilité

Chez **Ally Organization**, l'accessibilité n'est pas une option : c'est notre métier. Nous construisons des outils qui aident les équipes à rendre le web accessible, et nous appliquons à nos propres dépôts les standards que nous recommandons.

## 🎯 Notre engagement

- Nos interfaces et documentations visent la conformité **WCAG 2.2 niveau AA**.
- Référentiel européen de référence : **EN 301 549 v4.1.1** ; référentiel français : **RGAA 4.1.2**.
- Chaque nouveauté doit être utilisable au clavier, restituable par les lecteurs d'écran et respecter les ratios de contraste.

## 📦 Périmètre

Cette déclaration couvre :

- la documentation de l'organisation (README, guides, wiki) ;
- les interfaces web publiées par nos projets ;
- les sorties texte de nos outils en ligne de commande.

Nos dépôts sont en phase alpha : la conformité est un objectif de progression, pas encore un état constaté. Nous préférons le dire honnêtement que le survendre.

## ⚠️ Obstacles connus

- Certaines documentations sont incomplètes ou en cours de rédaction.
- Les livrables générés par nos outils évoluent rapidement : des régressions peuvent apparaître entre deux versions.

Un obstacle absent de cette liste ? Signalez-le (voir ci-dessous) : il sera documenté ici.

## 🐛 Signaler un obstacle

1. Ouvrez une [issue](https://github.com/ally-organization/.github/issues) sur ce dépôt, idéalement avec le label `accessibility` ;
2. ou démarrez une [discussion](https://github.com/orgs/ally-organization/discussions).

Pour un obstacle lié à un dépôt précis, ouvrez l'issue directement sur ce dépôt. Les signalements venant d'utilisateurs de technologies d'assistance sont traités en priorité.

## 🤝 Attentes envers les contributeurs

Toute PR touchant une interface ou de la documentation doit :

- utiliser du HTML sémantique (ou ARIA quand nécessaire) ;
- garantir une navigation clavier complète et un focus visible ;
- fournir un texte alternatif pour chaque image porteuse d'information ;
- respecter les contrastes WCAG AA.

## 🧭 Maintenance

- **Responsable** : [@maelemiel](https://github.com/maelemiel)
- **Révision** : à chaque release majeure des projets de l'organisation, et au minimum une fois par semestre.
- Site du produit : [ally.ovh](https://ally.ovh)

*Dernière mise à jour : octobre 2026.*
