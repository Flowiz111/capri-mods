# Mods pour Capri FR

> **Annuaire de mods de [Capri FR](https://github.com/Flowiz111/capri-fr), la version française non officielle de Capri.** Ce dépôt est un fork de [lachydotmcg/capri-mods](https://github.com/lachydotmcg/capri-mods). Il n'est ni géré ni approuvé par le projet Capri.

## ⚠️ Avant d'installer un mod

- **Ces mods ne sont pas vérifiés par ce dépôt.** Ils ont été copiés depuis l'annuaire d'origine, sans contrôle supplémentaire.
- **Les mods de code (`.capri-code`) ont un accès complet à ton PC.** Capri demande avant de les lancer. N'accepte que ceux en lesquels tu as confiance.
- **Les mods appartiennent à leurs auteurs**, indiqués dans chaque dossier. Si tu es l'auteur d'un mod et que tu veux le voir retiré d'ici, [ouvre une issue](../../issues).

## Types de mods

| Type | Extension | Ce qu'il fait |
| --- | --- | --- |
| **Réglages** | `.capri-mod` | Ajoute des noms, des couleurs ou d'autres réglages. |
| **Code** | `.capri-code` | Exécute du code C# compilé par Capri. Peut tout faire sur ton PC. |
| **Apparence** | `.capri-skin` | Un zip d'images qui remplacent ses dessins. |
| **Compétence** | `.capri-skill` | Des connaissances sur un jeu. Nécessite Capri 0.8.4 ou plus récent, donc Capri FR ne les affiche pas pour l'instant. |

## Utiliser un mod

Dans Capri FR, ouvre le Mainframe, appuie sur **Mods**, puis sur **Parcourir les mods**. **Installer** ajoute le mod et l'active. Tu peux aussi télécharger un fichier de mod ici et utiliser **Importer un mod**.

## Proposer un mod

1. Forke ce dépôt.
2. Dans `mods/`, ajoute un dossier au nom de ton mod. Mets-y le fichier du mod, un court `README.md` qui dit ce qu'il fait et qui l'a créé, et une image `preview.png` d'environ 16:9.
3. Ouvre une pull request. Le responsable de ce dépôt décide s'il publie ton mod.

## Pour le responsable du dépôt

Après un ajout ou une modification de mod, il faut mettre à jour `index.json` et `tree.json`. L'application utilise `tree.json` quand la limite de GitHub est atteinte, et chaque téléchargement est vérifié avec l'empreinte de cette liste. Relis aussi le code de tout mod proposé avant de l'accepter.

## Sécurité

- N'installe que des mods d'ici ou de personnes en qui tu as confiance.
- Télécharge Capri FR uniquement depuis [sa page officielle](https://github.com/Flowiz111/capri-fr/releases/latest).

## Crédits

Annuaire d'origine : [lachydotmcg/capri-mods](https://github.com/lachydotmcg/capri-mods), par Lachy et les auteurs de chaque mod. Les descriptions de ce dépôt ont été traduites en français.
