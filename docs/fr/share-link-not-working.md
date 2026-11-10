# Lien de partage Baidu Pan qui ne fonctionne pas : ce que veut dire chaque message

Vous ouvrez un lien `pan.baidu.com` et, au lieu d’une liste de fichiers, un court message en chinois s’affiche. Cette page vous explique ce qu’il signifie et ce que vous pouvez faire.

## D’abord, vérifiez l’adresse

Un lien valide a la forme `https://pan.baidu.com/s/1…`, avec une longue suite de lettres et de chiffres après le `1`. Une fois la page ouverte, le navigateur peut afficher `https://pan.baidu.com/share/init?surl=…` à la place. Il s’agit du même partage.

Si le lien a été tronqué lors de la copie, il ne s’ouvrira pas. Copiez-le de nouveau depuis le message d’origine, jusqu’au tout dernier caractère.

## Ce que la page vous dit

| Ce que vous voyez | Ce que ça signifie | Qui peut régler le problème |
| --- | --- | --- |
| Un champ qui demande quatre caractères | Le partage est protégé. Il vous faut le [code d’accès](extraction-code.md) | Vous, avec le code fourni par le propriétaire |
| Un message disant que vous arrivez trop tard et que le partage a été annulé | Le propriétaire a cessé de partager, ou Baidu a supprimé les fichiers | Le propriétaire |
| Un message qui parle d’atteinte aux droits ou de contenu interdit | Baidu a bloqué le partage | Personne : le partage reste bloqué |
| Une liste de fichiers avec une note indiquant que certains fichiers ont été filtrés | Une partie du partage enfreint les règles de Baidu et est masquée | Le propriétaire |
| Un message indiquant que le partage n’est plus valide | Le partage a expiré | Le propriétaire |

La fonction de traduction de votre navigateur vous aide à distinguer ces messages.

## Que faire

- **Le code est refusé :** comparez-le avec le message d’origine, caractère par caractère. Voir [Code d’accès](extraction-code.md).
- **Le partage est annulé ou expiré :** demandez au propriétaire de partager à nouveau les fichiers et de vous envoyer le nouveau lien et le nouveau code.
- **Le partage est bloqué :** il n’y a rien à télécharger. Demandez au propriétaire si les fichiers sont disponibles ailleurs.

## Vérifiez avant de payer quoi que ce soit

Testez le lien dans le [vérificateur de lien PanPull](https://panpull.com/fr?utm_source=github&utm_medium=tutorial#link-checker). La vérification est gratuite. Un partage lisible s’affiche avec son nombre de fichiers, sa taille totale et son prix. S’il ne peut pas être lu, vous obtenez un message d’erreur à la place, et rien n’est facturé.

Aucun service ne peut faire revenir un partage supprimé, annulé ou bloqué. Si un partage échoue sur PanPull alors qu’il s’ouvre sans problème chez le propriétaire, réessayez un peu plus tard : la cause peut être passagère.

Pour aller plus loin, sur le blog PanPull : [Lien de partage Baidu qui ne fonctionne pas : que vérifier](https://panpull.com/fr/blog/baidu-share-unavailable-checklist?utm_source=github&utm_medium=tutorial).

---

**Vous avez un lien Baidu ? [Vérifiez-le sur PanPull](https://panpull.com/fr?utm_source=github&utm_medium=tutorial#link-checker)** et voyez d’abord la taille et le prix. Gratuit jusqu’à 150 MB.

[Tous les tutoriels](README.md) · [Autres langues](../README.md#languages)
