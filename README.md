# Relecture

Relecture est un plugiciel de bureau pour relire un texte dans ChatGPT, commenter un passage et examiner des corrections. L’atelier **La dernière balise** permet de l’essayer avec une scène fictive.

## Relecture Texte dans ChatGPT

Une édition **Relecture Texte** est en préparation pour ChatGPT. Elle propose des corrections et commente les passages que vous fournissez dans la conversation. Vous choisissez quelles propositions retenir.

[Assistance](SUPPORT.md) · [Confidentialité](PRIVACY.md#relecture-texte-dans-chatgpt) · [Conditions de la bêta](TERMS.md)

## Installer la bêta

1. Téléchargez [Relecture 1.14.1 pour ordinateur](https://github.com/NathanOtano/Relecture/releases/download/v1.14.1/Relecture-1.14.1-desktop.zip) et décompressez le ZIP.
2. Installez [Node.js 22 ou plus récent](https://nodejs.org/) si nécessaire. Ouvrez un terminal dans le dossier décompressé et lancez `node scripts/install.mjs` pour prévisualiser l’installation, puis `node scripts/install.mjs --apply` pour inscrire le plugiciel au catalogue local.
3. Redémarrez ChatGPT pour ordinateur. Dans le répertoire des plugiciels, sélectionnez la source locale et installez **Relecture bêta**. Votre application doit autoriser les catalogues locaux et les serveurs MCP locaux.
4. Dans un nouveau chat local, mentionnez **Relecture bêta** et demandez « Ouvre *La dernière balise*. » Le premier lancement crée l’atelier. Sélectionnez une phrase pour ajouter un commentaire.

Sur Windows, le paquet a été installé dans un profil de test isolé. L’activation dans l’interface de ChatGPT dépend de la prise en charge du catalogue local par votre installation.

## Vos textes et vos invitations

Relecture garde localement les espaces déclarés. Les contenus qu’un outil renvoie au chat peuvent être accessibles à ChatGPT. Le partage par lien est facultatif. Voir la [notice de confidentialité](PRIVACY.md) et les [conditions de la bêta](TERMS.md).

[Notes de version et somme SHA-256](https://github.com/NathanOtano/Relecture/releases/tag/v1.14.1)

Développé par Nathan Otaño.
