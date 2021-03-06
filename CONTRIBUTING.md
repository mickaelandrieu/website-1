# Contribuez !

Chez Putain de Code, on te laisse l'opportunité d'apporter ta pierre à
l'édifice, comme on te l'explique en détails [sur un article dédié sur le
site](http://putaindecode.fr/posts/comment-contribuer/).

Tu trouveras ici un condensé des bonnes pratiques pour pouvoir participer.

Avant tout, on te précise que comme le site et le public du site sont
francophones, tu peux te permettre (et on préfère même) que les issues et les
messages de commit soient en français. Voilà c'est dit merci tu peux lire la
suite !

## Crée ton fork

C'est l'étape la plus simple, utilise l'interface de GitHub pour ça.

![github-fork](src/pages/posts/comment-contribuer/fork-button.jpg)

## Soumettre un post

* Crée une branche avec un nom de la forme `post.<nom du post>` (ex.
  `post.contribuer-a-p`)
* Écris ton post dans `pages/posts/` en respectant bien la convention du
  nom de fichier `titre/index.jade|md` (genre `contribuer-a-p/index.jade` et `contribuer-a-p/index.md`)
  en t'inspirant des autres posts que tu devrais trouver sans mal.
* Une fois que tout est prêt, fais une demande de pull-request de ta branche
  vers notre branche `master` en mettant en titre `Post: Le titre de ton post`
  (évidemment tu remplaces ce qu'il y a après `Post:` par le vrai titre hein)
* On va passer ton post en revue, éventuellement te demander de corriger deux
  trois trucs, et au bout d'un moment l'accepter (sauf s'il est nul, évidemment)
* De notre côté on va lui mettre une date de publication pour le publier.

## Apporter un correctif

Si tu remarques qu'il y a une grosse *fôte* dans un article, ou que certains
points peuvent être plus détaillés, libre à toi de nous proposer tes corrections
!

* Il faut que tu aies un fork comme on a expliqué plus haut
* Crée une branche `fix.<nom du post>` (genre `fix.contribuer-a-p`)
* Fais tes modifications sans nous pourrir l'article
* Fais une *Pull Request* comme pour un nouveau post MAIS avec en titre
  `Fix: Le titre du post corrigé` (là aussi, remplace en conséquence)
* De notre côté on va passer en revue la modification, puis éventuellement on
  l'acceptera

**Tu peux aussi faire beaucoup plus simple en utilisant l'interface de
GitHub pour éditer un fichier (qui reproduira les étapes précédentes).**

## Pull-Requests

N'oublie pas de bien détailler et d'expliquer le contenu de tes *Pull Request*,
y'a un champ exprès pour ça, autant t'en servir !

Si jamais on trouve qu'une PR n'est pas complète, on va te la tagguer `[WIP]`
jusqu'à ce que tout soit bon. À ce moment là, on enlèvera le tag et on *mergera*
dans notre branche `master`.
