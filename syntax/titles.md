# Titles
# Titres

As we started writing a markdown document, we need to add a title and some sub-headers.
Comme nous avons commencé la rédaction d'un document de démarques, nous avons besoin d'ajouter un titre et certains sous-en-têtes.

Markdown supports two styles of headers, Setext and atx.
Markdown supporte deux styles d'en-têtes, Setext et atx.

Setext-style headers are “underlined” using equal signs (for first-level headers) and dashes (for second-level headers). For example:
les en-têtes Setext-style sont "soulignées" en utilisant le signe égal (pour les en-têtes de premier niveau) et des tirets (pour les en-têtes de second niveau). Par exemple:

```
This is an H1
=============
`` `
Ceci est une H1
=============

This is an H2
-------------
```
Ceci est un H2
-------------
`` `

Any number of underlining =’s or -’s will work.

Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:

```
# This is an H1

## This is an H2

###### This is an H6
```


Optionally, you may “close” atx-style headers. This is purely cosmetic — you can use this if you think it looks better. The closing hashes don’t even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :

```
# This is an H1 #

## This is an H2 ##

### This is an H3 ######
```


---

Here's a quiz about markdown titles.

Select the valid headers:
- [x] `# hello`
- [ ] `#hello`

> Headers need space between the hash characters and the text.

Select the valid headers:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Only '=' and '-' are accepted for underlining an header.

---


