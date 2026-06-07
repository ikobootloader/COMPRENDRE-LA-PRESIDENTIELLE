# Comprendre l'election presidentielle

Application statique en une page qui explique, de facon neutre et accessible, le fonctionnement de l'election presidentielle francaise.

L'objectif est pedagogique : aider un lecteur a comprendre le scrutin, le role reel du president, les grandes familles politiques, les conditions pour voter et les demarches d'inscription, sans recommander de candidat ni de parti.

## Apercu

Le projet repose sur une page HTML autonome avec CSS et JavaScript integres. Il ne necessite ni compilation, ni dependances, ni serveur applicatif.

La page principale contient notamment :

- une introduction editoriale sur la presidentielle 2027 ;
- un compte a rebours vers la fenetre previsionnelle du premier tour ;
- des sections explicatives sur le scrutin et les pouvoirs du president ;
- une presentation synthetique des grandes familles politiques ;
- un module "vrai ou faux" sur quelques idees recues ;
- des rappels pratiques sur l'inscription, les parrainages et le jour du vote ;
- une liste de sources officielles pour verification.

## Structure

- [comprendre-la-presidentielle.html](C:/Users/fredm/Desktop/COMPRENDRE-ELECTION/comprendre-la-presidentielle.html) : version principale de l'application.
- [older/comprendre-la-presidentielle.html](C:/Users/fredm/Desktop/COMPRENDRE-ELECTION/older/comprendre-la-presidentielle.html) : version anterieure conservee en archive.

## Lancer localement

Comme il s'agit d'une page statique, il suffit d'ouvrir le fichier HTML principal dans un navigateur :

1. Ouvrir [comprendre-la-presidentielle.html](C:/Users/fredm/Desktop/COMPRENDRE-ELECTION/comprendre-la-presidentielle.html).
2. Verifier le rendu sur desktop et mobile si des modifications sont apportees.

Si besoin, un petit serveur local peut aussi etre utilise, mais il n'est pas obligatoire.

## Choix de conception

- Application mono-fichier facile a diffuser.
- Ton volontairement neutre et informatif.
- Design editorial, lisible sur mobile comme sur ordinateur.
- Sources institutionnelles mises en avant pour encourager la verification.
- Date de scrutin traitee comme previsionnelle tant qu'aucun decret officiel n'est publie.

## Points d'attention

- Le projet contient actuellement des traces d'encodage a surveiller dans l'affichage de certains caracteres accentues selon l'environnement d'ouverture ou d'edition.
- Les informations liees au calendrier electoral et au paysage politique devront etre revalidees avant publication a l'approche du scrutin.
- La version du dossier `older/` peut servir de reference lors de futures evolutions editoriales ou graphiques.

## Evolutions possibles

- Corriger et normaliser completement l'encodage des contenus.
- Extraire les styles et scripts dans des fichiers dedies si le projet grossit.
- Ajouter une section FAQ ou un comparatif des institutions.
- Ajouter des verifications editoriales datees pour faciliter les mises a jour.

## Licence et usage

Aucune licence explicite n'est presente dans le projet a ce stade. Si cette page doit etre diffusee publiquement ou reutilisee, il est recommande d'ajouter une licence et des mentions de maintenance.
