# rails-voting [![Build Status](https://travis-ci.org/simplonco/rails-voting.svg?branch=master)](https://travis-ci.org/simplonco/rails-voting)

## Objectif

Mettre en place un systeme de vote de type :
- appréciation (ex. choix d'un nombre d'étoile)
- oui/non (thumb up/down)

Pour éviter les votes multiples/tricherie : c'est impossible :)
- traiter par le vote via une autehntification utilisateur
- oublier le vote/sondage public sans authentification (il suffit de supprimer le cookie pour pouvoir revoter indéfiniement)

## Ressources

Plusieurs Gem de disponible pour effectuer le job :

### Systeme de d'étoiles :

* [letsrate](https://github.com/muratguzel/letsrate) > gem simple, n'apparaît pas avoir besoin d'explications particulières

### Systeme oui / non

* [activerecord-reputation-system](https://github.com/twitter/activerecord-reputation-system/)
* [thumbs_up](https://github.com/bouchard/thumbs_up)
* [acts_as_votable](https://github.com/ryanto/acts_as_votable) est compris dans la gem thumbs_up
* [likeable](https://github.com/schneems/likeable) rien de neuf depuis 2 ans... il semble que ce soit pour du rails 3
