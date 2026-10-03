<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./logo-dark.svg">
    <img src="./logo-light.svg" alt="Kledg" width="64" height="64">
  </picture>
</p>

<h1 align="center">Kledg</h1>

<p align="center">
  Le logiciel comptable open source pour produire le bilan et le compte de résultat de votre société chaque année.<br>
  Auto-hébergé, gratuit, avec un serveur MCP pour travailler avec Claude ou ChatGPT.
</p>

<p align="center">
  <a href="https://www.kledg.com">Site</a> ·
  <a href="https://www.kledg.com/fr/docs">Documentation</a> ·
  <a href="https://demo.kledg.com">Démo</a> ·
  <a href="https://www.kledg.com/fr/blog">Blog</a>
</p>

---

Kledg tient la comptabilité des petites sociétés françaises (SASU, EURL, SARL, SAS, SCI à l'IS, holdings) selon le plan comptable général 2026 : saisie en partie double, synchronisation bancaire et rapprochement automatique, clôture de l'exercice, bilan, compte de résultat, grand livre et export FEC conforme. Vous l'hébergez vous-même (Vercel et Neon en un clic, ou Docker) : vos données restent chez vous.

## Les dépôts

| Dépôt | Rôle |
| --- | --- |
| [**kledg**](https://github.com/kledghq/kledg) | L'application : comptabilité, banque, états financiers, FEC et serveur MCP. Licence AGPL-3.0. |
| [**website**](https://github.com/kledghq/website) | Le site [www.kledg.com](https://www.kledg.com) : présentation, documentation et blog. |
| [**kledg-demo**](https://github.com/kledghq/kledg-demo) | L'instance de démonstration [demo.kledg.com](https://demo.kledg.com), un fork de kledg avec des sociétés fictives. |

## Démarrer

- **Essayer** : [demo.kledg.com](https://demo.kledg.com), sans inscription, avec quatre sociétés fictives.
- **Installer** : le guide [Installer Kledg](https://www.kledg.com/fr/docs/installer-kledg) (Vercel et Neon) ou [Héberger avec Docker](https://www.kledg.com/fr/docs/heberger-avec-docker).
- **Connecter un assistant** : [Claude ou ChatGPT](https://www.kledg.com/fr/docs/connecter-claude-ou-chatgpt), avec le choix des sociétés et du niveau d'accès.

## Contribuer

Les contributions sont les bienvenues : corrections, fonctionnalités, interface et relectures par des experts-comptables. Chaque règle comptable ou fiscale s'accompagne de tests et de sa source (article du PCG, BOFiP, notice de formulaire). Commencez par le [guide de contribution](https://github.com/kledghq/kledg/blob/main/CONTRIBUTING.md) et le [code de conduite](https://github.com/kledghq/.github/blob/main/CODE_OF_CONDUCT.md).

## Sécurité

Kledg manipule des données comptables et bancaires. Pour signaler une vulnérabilité, n'ouvrez pas d'issue publique : écrivez à **security@kledg.com** ou utilisez le signalement privé de GitHub. Voir la [politique de sécurité](https://www.kledg.com/fr/securite).
