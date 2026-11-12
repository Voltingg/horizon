# Horizon

Launcher pour BlablaFantasy.

## Installer

**[Télécharger Horizon](https://github.com/Voltingg/horizon/releases/latest/download/Horizon-Setup.exe)** (dernière version, Windows)

Lancer le fichier téléchargé : l'installation se fait pour l'utilisateur, sans droits administrateur. Les versions précédentes et leurs notes sont dans les [releases](https://github.com/Voltingg/horizon/releases).

Horizon se met ensuite à jour tout seul : à chaque lancement, il vérifie la dernière version publiée ici et l'installe.

## « Windows a protégé votre ordinateur »

Au premier lancement de l'installeur, Windows SmartScreen peut afficher un écran bleu « Windows a protégé votre ordinateur ». Pour continuer :

1. Cliquer sur **Informations complémentaires** (sous le texte).
2. Vérifier que l'application s'appelle bien `Horizon-Setup.exe` (l'éditeur affiché est « Éditeur inconnu » : c'est normal, voir plus bas).
3. Cliquer sur **Exécuter quand même**.

Si le navigateur bloque le téléchargement (Edge : « n'est pas fréquemment téléchargé »), ouvrir le menu `...` du téléchargement, puis **Conserver**, puis **Afficher plus** et **Conserver quand même**.

### Pourquoi cet avertissement ?

SmartScreen ne dit pas qu'Horizon est dangereux : il dit qu'il ne le connaît pas. Windows juge un programme sur deux choses :

- **Sa signature numérique.** Pour qu'un programme soit « reconnu », son auteur doit acheter un certificat de signature de code auprès d'une autorité reconnue par Microsoft, après vérification de son identité. Ces certificats coûtent plusieurs centaines d'euros par an (et la version qui supprime l'avertissement immédiatement, dite « EV », encore plus, avec une clé matérielle). Pour un launcher gratuit, fait sur du temps libre, ce n'est pas raisonnable.
- **Sa réputation.** Sans signature, SmartScreen attend qu'un grand nombre de personnes aient téléchargé et lancé le fichier sans problème. Chaque nouvelle version repart de zéro, donc l'avertissement revient régulièrement.

Les mises à jour automatiques, elles, s'installent sans cet écran.

Horizon est publié uniquement ici, sur ce dépôt. Ne téléchargez pas d'installeur venant d'ailleurs.
