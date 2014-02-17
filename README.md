#Objectif
Mettre en place un systeme de vote de type :
- appréciation (ex. choix d'un nombre d'étoile)
- oui/non (thumb up/down)

Pour éviter les votes multiples/tricherie : c'est impossible :)
- traiter par le vote via une autehntification utilisateur
- oublier le vote/sondage public sans authentification (il suffit de supprimer le cookie pour pouvoir revoter indéfiniement)


#Ressources
Plusieurs Gem de disponible pour effectuer le job :
<dl>

##Systeme de d'étoiles :
	<dt>[letsrate](https://github.com/muratguzel/letsrate)<dt>
		<dd>>gem simple, n'apparaît pas avoir besoin d'explications particulières<dd>


##Systeme oui / non
	<dt>[activerecord-reputation-system](https://github.com/twitter/activerecord-reputation-system/)</dt>
	<dd></dd>
	<dt>[thumbs_up](https://github.com/bouchard/thumbs_up)</dt>
	<dd></dd>
	<dt>[acts_as_votable](https://github.com/ryanto/acts_as_votable)</dt>
	<dd>est compris dans la gem thumbs_up</dd>
	<dt>[likeable](https://github.com/schneems/likeable)</dt>
		<dd>rien de neuf depuis 2 ans... il semble que ce soit pour du rails 3</dd>

</dl>

#Methodo