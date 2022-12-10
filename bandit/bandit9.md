Utiliser grep pour trouver

grep --text -e =.* data.txt

grep = trouve un patterne dans un texte

--text = pb de mort genre c'est pas du texte

-e = dire qu'on va utiliser des regex

=.* = la regex en question

data.txt = le file à fouiller

code = G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s



POUR UN TRUC ENCORE MIEUX

grep --text -E "={2,5}.*" data.txt

-E = autre version de regex

={2,5}.* = va chercher entre 2 et 5 = d'affilés