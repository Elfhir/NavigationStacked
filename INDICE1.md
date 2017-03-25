# INDICES

## INDICE 1

On a un test à faire dans tous les cas :
Vérifier si on est sur mobile.

Pour cela, les media queries CSS permettent de vérifier notamment la largeur de l'écran.

En Javascript, on peut aussi vérifier la largeur de l'écran, ou bien regarder le User Agent du navigateur.



Notre CSS est **"mobile first"** si on regarde bien :
le style s'applique à tous, puis des media queries s'applique pour tablette,
pour desktop, etc.

En js, on peut faire une condition sur la largeur de l'écran :

*jQuery*
`
if ( $(window).width() > 480) {
	// not mobile
}
else {
	// mobile
}
`

*Vanilla JS*
`
if (window.innerWidth > 480) {
	// not mobile
}
else {
	// mobile
}
`
