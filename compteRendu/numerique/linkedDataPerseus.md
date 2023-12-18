--- 
title: Linked data in the Perseus Digital Library - Compte Rendu
--- 

Ce que concerne Perseus est d'avoir des URIs estables et diférenciables. 

> we have released URIs for texts, citations and bibliographic catalog records. \[...] All Perseus data URIs are published under the *http://data.perseus.org* URI prefix, followed by one or more path components indicating the resource type, then a unique identifier for the resources, and an optinal path component identifying a specific output format for the resource. 

Syntax pour les citations et les textes
- Citation
    - http://data.perseus.org/citations/<CTS PASSAGE URN>[/format]
- Texte
    - http://data.perseus.org/texts/ <CTS TEXT URN>[/format]

Iliade (l'œuvre, *notional work* est le terme utilisé)
- http://data.perseus.org/texts/urn:cts:greekLit:tlg0012.tlg001

La version TEI XML de l'Illiade à Perseus (*l'expression*)
- http://data.perseus.org/texts/urn:cts:greekLit:tlg0012.tlg001.perseus-grc1

Citation (le *notinal work* de la citation)

- http://data.perseus.org/citations/urn:cts:greekLit:tlg0012.tlg001:1.100

Citation (avec *l'expression*, c'est à dire l'édition de Perseus)
- http://data.perseus.org/citations/urn:cts:greekLit:tlg0012.tlg001.perseus-grc1:1.100

> Note that, per the CTS standard, if you request a URN for a notional work without including an edition or translation specifier, then we return the default edition for that work in our repository, which in this case happens to be the perseus-grc1 edition

On peut ajouter le format TEI XML au texte choisi

- http://data.perseus.org/citations/urn:cts:greekLit:tlg0012.tlg001.perseus-grc1:1.100/xml

Le paragraphe 32  du texte est important à ma recherche. Mon travail à la plateforme AP est en connexion avec ce but de Perseus.

> In our efforts to connect with other groups in the scholarly and library communities, the Perseus Digital Library has made our authority record data for classical authors available to the Virtual International Authority File. The contribution of names from our author records will expand the VIAF name clusters, adding different forms of a given author’s name, and assist in VIAF’s goal of building truly international authorities that are useful to libraries and scholars. This relationship will also help the catalog to provide links to the VIAF clusters so as to make as much information about an author available and forward the further development of the Semantic Web.