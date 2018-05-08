					
					![I love Markdown](http://mikemclin.net/mmwp/wp-content/uploads/2013/03/markdown-syntax-language.png)




Markdown est un système d’édition et de formatage de texte ; c’est à la fois une syntaxe, un script de conversion texte → HTML et un format de fichier. Il est couramment utilisé pour les fichiers de documentation d’un projet ou d’un jeu de données -souvent nommé readme.md. Il est stocké au format texte classique et est plus léger que sa version interprétée puisqu’il ne contient pas les balises html.

La philosophie du système veut que le texte écrit soit lisible sans interpréteur particulier en mode texte. Il est léger et épuré de l’essentiel de la verbosité d’un language balisé. Les éléments de syntaxe sont des caractères de ponctuation qui font sens visuellement même non convertis. Une fois converti, le navigateur web (qui joue alors le rôle d’interpréteur) en rendra la lecture plus claire.

Les fichiers sont généralement enregistrés avec l’extension .md (ou .markdown ) pour indiquer aux interpréteur la nature du texte qu’il vont lire ; mais ça n’a rien d’obligatoire.

Comme le résultat sera exporté en HMTL, vous pouvez tout à fait introduire directement des balises HTML dans votre texte ; mais celui-ci deviendra moins lisible et ne pourra plus être édité par quelqu’un ne maîtrisant pas le HTML. Attention, le formatage markdown ne sera pas appliqué à l’intérieur de ces balises.

#                                La synthaxe de markdown

# Headers

# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag


# Emphasis

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

# Lists

Unordered

* Item 1
* Item 2
  * Item 2a
  * Item 2b

Ordered

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

# Images

![Becode Logo](/images/logo.png)
Format: ![Alt Text](url)

# Links

http://github.com - automatic!
[GitHub](http://github.com)

# Blockquote


> This is a quote

# Inline code

Inline code

I think you should use an
`<addr>` element here instead.












