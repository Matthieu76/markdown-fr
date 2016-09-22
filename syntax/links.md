# Liens

Le Markdown autorise deux types de liens: les liens en ligne et les références.

Dans les deux types, le texte du lien est délimité par des [crochets].

Pour créer un lien en ligne, utilisez un ensemble de parenthèses classiques immédiatement après la fermeture des crochets délimitant le texte du lien. A l'intérieur des parenthèses, mettez l'URL à laquelle vous voulez que le lien pointe, avec un titre falcultatif pour le lien, entouré de guillemets. Par exemple:
```markdown
[Je suis un lien de type en ligne](https://www.google.com)

[Je suis un lien de type en ligne avec titre](https://www.google.com "Page d'accueil Google")

[Je suis un lien de type référence][Texte de référence arbitraire insensible à la casse]

[Je suis une référence relaive à un fichier de dépot](../blob/master/LICENSE)
```

Les liens de type référence utilisent un deuxième ensemble de crochets, à l'intérieur desquels vous placez une étiquette de votre choix pour identifier le lien:
```markdown
Voivi [un exemple][id] de lien de type référence.
```

Vous pouvez éventuellement utiliser un espace pour séparer les ensembles de crochets:
```markdown
Voici [un exemple] [id] de lien de type référence.
```

Ensuite, n'importe où dans le document, vous définissez votre étiquette de lien comme ceci, sur une ligne isolée:
```markdown
[id]: http://example.com/  "Titre optionnel ici"
```

**GitHub** et **GitBook** supportent l'autoredirection URL. Ils redigigent automatiquement vers les URL standard, donc si vous voulez créer un lien vers une URL (au lieu de mettre le texte du lien), vous pouvez tout simplement cliquer sur l'URL et il sera transformé en lien vers cette URL.


---

Here's a quiz about markdown links.

Select the valid links:
- [x] `[a link](http://google.fr)`
- [ ] `(a link)[http://google.fr]`

> The link text is delimited by [square brackets].

What are the correct informations from this link: ```[a link](http://google.fr "google")```
- [ ] the link is https://google.fr
- [x] the title of the link is "google"
- [ ] it'll show the text "google"
- [x] it'll show the text "a link"

> Links can have 3 parts: the text, the url and a title.

---

