# Images

```markdown
# Inline
![Alternative text](/path/to/img.jpg "Optional title")

# Reference
![Alternative text][id]
[id]: url/to/image  "Optional title"
```
Comme vous avez dû le remarquer, les images en Markdown sont très semblables aux liens.  
La différence est la suivante :
* les crochets doivent être précédés par un point d'exclamation ;
* ils peuvent contenir un texte alternatif, qui s'affiche quand l'image ne peut être chargée.

---

VOici un quizz à propos des images dans markdown.

Choisissez des images valides:
- [ ] `[Google logo](https://www.google.ru/logo.png)`
- [x] `![](https://www.google.ru/logo.png)`

> Les images doivent être précédées d'un point d'exclamation.
Le titre et le texte alternatif sont optionnels.

Qu'est-ce qui est vrai dans la ligne suivante: ```![Funny cat](http://cats.ru/funny.png "Partager ça")```
- [x] si l'url est 404, "Funny cat" sera affiché
- [ ] le point d'exclamation n'est pas nécessaire dans ce cas
- [ ] Si l'url est 404, "Partager ça" sera affiché
- [x] si la souris est sur l'image, "Partager ça" sera affiché

> Comme pour les liens, les images peuvent avoir 3 parties: le texte alternatif, l'url et le titre. Un point d'exclamation est requis.

---
