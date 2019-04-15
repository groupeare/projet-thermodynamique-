A travers cet atelier de recherche encadré Dynamic nous avons cherché à modeliser l'evolution complexe d'un systeme composé de plusieurs  élements chimiques dont le deplacement est régit par les lois de la thermodynamique . Pour cela nous avons imaginé deux elements chimiques succeptibles de réagir entre eux pour forthmer un nouvel element, ces elements chimiques peuvent etre assimilés à n'importe quels atomes ou molecules( par exemple dihydrogene H2 et oxygene O pour former de l'eau H2O).

La formation d'un  nouvel element chimique n'est pas évidente. En effet, il faut tout d'abord que les deux elements chimiques entre en collision  et il faut de plus que leur collision soit "efficace" car ce n'est pas parce qu'ils entrent en contact qu'ils vont forcement reagir.

Pour modeliser ce systeme nous faisons intervenir differentes variables : la pression et la temperature, ces deux facteurs cinetiques vont avoir une influence sur la vitesse des elements chimiques et sur leur probabilités de reagir lorsqu'il y a une collision.
Nous avons choisi de mettre les elements chimiques dans un espace clos et de considerer que les chocs entre eux et sur les parois sont elastiques c'est a dire qu'il n'y a pas de perte de vitesse. 

Dans notre modèle nous considérons un système à deux dimensions dans lequel on place N molécules. Ces molécules constituent un gaz qui n’est pas parfait car il en détient toutes les caractéristiques sauf une.
En effet un gaz parfait est constitué de particules qui n’interagissent pas entres elles.

Il s’agit d’observer l’évolution du modèle en fonctions de caractères cinétiques.
Dans le domaine de la chimie, un facteur cinétique désigne un paramètre physique capable d'influencer la vitesse d'une transformation chimique.

En conséquence, un facteur cinétique modifie la durée d’évolution d’un système chimique.
Plusieurs facteurs cinétiques peuvent être envisagés comme la température, la pression et la concentration des réactifs. 
Nous axerons notre modèle sur deux facteurs : La pression et la température.

   Historiquement, la température du milieu réactionnel a été le premier facteur cinétique envisagé et précisément étudié. C'est encore, de nos jours, le facteur cinétique le plus souvent utilisé pour modifier la durée d’une transformation.
En général, plus la température du milieu réactionnel est élevée, plus la durée de la transformation est courte et par conséquent plus la réaction est accélérée. Une élévation de température du milieu trouve son application lorsque l’on veut accélérer ou parfois déclencher une transformation lente voire cinétiquement inerte.

   En tant que facteur cinétique, la pression n'a réellement une influence que lors de réactions en phase gazeuse, les phases condensées étant peu sensibles aux différences de pression.
À l'instar de la température et de la concentration des réactifs, augmenter la pression (en phase gazeuse) augmente la probabilité de chocs efficaces et ainsi provoque une augmentation de la vitesse de réaction.
Dans le cadre de considérations thermodynamiques, cette influence est liée au fait que l'augmentation de la pression partielle d'un gaz augmente son activité le rendant ainsi plus réactif.

Afin de décrire l’évolution de notre système nous nous sommes appuyés sur 2 principes ou phénomènes physiques : 

   La théorie cinétique des gaz : c’est une théorie physique dans laquelle on place N particules d’un gaz parfait dans un cube, les particules sont en mouvement dans ce cube, elles détiennent toutes une vitesse initiale avec un vecteur vitesse dont la norme est unitaire pour toutes les particules mais de directions différentes données aléatoirement.

 Dans cette théorie le gaz est parfait et les seuls échanges entre molécules sont des collisions, les particules détiennent des collisions avec les parois du cube ainsi qu’avec les autres particules. 
 
Les chocs sont tous élastiques, il y a donc lors de l’évolution du système une conservation de l’énergie cinétique. 
Le cube est issue d’un axe orthonormée X, Y, Z dans lequel chaque particule a des positions initiales Vx, Vy, Vz. La théorie cinétique des gaz parfait met en évidence le fait qu’on peut établir des formules qui lient les caractères macroscopiques (pression, température, volume du cube) ainsi que les caractères microscopiques qui sont les coordonnées initiales de chaque particule. 
En effet les masses étant constantes et les chocs étant élastiques il existe une formule liant la vitesse la pression le volume et le nombre de particules. La norme du vecteur vitesse étant donnée grâce aux coordonnées initiales de la particule on lie les caractères microscopiques et macroscopiques du système. 

![](https://upload.wikimedia.org/wikipedia/commons/6/6d/Translational_motion.gif)


   Le deuxième phénomène physique est la fission nucléaire :
La fission nucléaire est l'éclatement d'un noyau instable en deux noyaux plus légers et quelques particules élémentaires. Cet éclatement s'accompagne d'un dégagement de chaleur, c'est à dire d'énergie.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Kernspaltung.gif/208px-Kernspaltung.gif)

Notre modèle s’inspire des deux principes évoqués ci dessus : 

Dans notre modèle nous avons fait l’hypothèse que les particules dans le système pouvaient former une autre molécule après une collision. 
Cette formation après collision est régit par une probabilité variable et donnée aléatoirement tout en dépendant des paramètres cinétiques fixés au départ de l’expérience.

En effet, la pression, un des paramètres fixés par l’observateur au début de l’expérience va déterminer la vitesse initiale de chaque particules et donc les caractères microscopiques que sont les positions de chaque particule, plus la pression est importante plus l’agitation des particules est importante.

Lorsqu’il y a collision les particules peuvent se coupler et former une molécule, cette molécule va ensuite se séparer selon le phénomène de fission nucléaire, car au départ il existe des électrons dans l’espace.

 Ces électrons vont entrainer la fission de la molécule qui elle même en se séparant va rejeter des électrons afin de perpétuer le phénomène de fission nucléaire tout au long de l ‘évolution du système.
 Lors de l’éclatement de cette molécule, les deux particules (similaires à celles qui se sont collisionnées) vont apparaître à des points aléatoires dans l’espace avec des vitesses sensiblement différentes pendant un moment pour illustrer le phénomène « d’éclatement », ce qui en résulte est une production d’énergie sous forme thermique.
 
Ainsi nous remarquons que plus les molécules sont formés après collision plus la chaleur est crée après fission de la même molécule, donc plus la probabilité de formation après collision est importante plus la température est élevée.

Afin de représenter cela nous avons décidé de laisser le choix de la température et de la pression à l’observateur au départ, il pourra ensuite observer la vérification de ces phénomènes alors qu’il aura lui même choisi les facteurs cinétiques. Si la pression est importante le système sera plus agitée et plus la température fixée sera élevée plus les molécules fusionneront puis fissionneront. 



# Analyse du programme

L’objectif de notre programme était de modéliser une l’évolution de deux éléments chimique, susceptibles de réagir ensemble, dans un espace clos. 
Les éléments chimiques sont représentés par des boules de différentes de couleurs, les boules rouges et vertes sont les réactifs et les boules bleus les produits, et le lieu de la réaction une fenêtre de dimension 480x320.

Dans notre programme nous avons arbitrairement choisit le rayon des boules et de la fenêtre mais l’utilisateur peut le modifier s’il le souhaite.  Afin d’afficher cela nous a utilisé la bibliothèque tkinter de python 3.  
Notre programme s’est construit autour de différentes fonction dont l’objectif étaient de symboliser les étapes clefs suivantes :


•	Le déplacement de chaque élément chimique dans un espace clos en 2D

Pour répondre à cela nous avons créé la fonction déplacement qui va modéliser la position de N balles (N choisit par l’utilisateur) à partir de sa vitesse et direction initial tout en tenant compte des rebonds sur les parois.  


	position initiale
 	X = []
	Y = []
	for i in range(n):
	X.append(LARGEUR*random.uniform(0.1,0.9))
	Y.append(HAUTEUR*random.uniform(0.1,0.9))


	direction initiale aleatoire
	DX = []
	DY = []
	for i in range(n):
	vitesse = random.uniform(1.8,2)*5
	angle = random.uniform(0,2*math.pi)
	DX.append(vitesse*math.cos(angle))
	DY.append(vitesse*math.sin(angle))

	def deplacement():
	""" Deplacement de la balle """
	global X,Y,DX,DY,RAYON,LARGEUR,HAUTEUR

	for i in range(n):
	if X[i]+RAYON+DX[i] > LARGEUR:
	X[i] = 2*(LARGEUR-RAYON)-X[i]
	DX[i] = -DX[i]

	rebond< a gauche
	if X[i]-RAYON+DX[i] < 0:
	X[i] = 2*RAYON-X[i]
	DX[i] = -DX[i]

	rebond en bas
	if Y[i]+RAYON+DY[i] > HAUTEUR:
	Y[i] = 2*(HAUTEUR-RAYON)-Y[i]
	DY[i] = -DY[i]

	rebond en haut
	if Y[i]-RAYON+DY[i] < 0:
	Y[i] = 2*RAYON-Y[i]
	DY[i] = -DY[i]

	X[i] = X[i]+DX[i]
	Y[i] = Y[i]+DY[i]
	
! [] (gif 2 balles)

En répétant cette fonction dans notre programme et en créant une nouvelle liste de N’   éléments (variable choisit par l’utilisateur) on va créer de nouvelles bouler de couleurs qui modéliseront un second élément chimique.  Il est intéressant de remarquer que dans notre programme final nous avons choisit de modéliser une réaction simple avec seulement 2 éléments chimiques mais pour une réaction plus complexe faisant intervenir plus d’éléments il aurait fallu rajouter cette fonction dans le programme pour chaque autre réactif.


•	La collision de deux éléments chimiques différents 

On parle de collision lorsque la distance entre deux boules est inférieure à leur rayon c’est-à-dire que cela répond à cette condition :

					math.sqrt((Xr[i]-xv[j])**2+(Yr[i]-yv[j])**2)<=2*

En cas de collision deux situations peuvent alors avoir lieu : un rebond, autrement dit chaque balle part dans sa direction opposée. Sur le programme on exprime cela de la manière suivante :

	Dxv[j]=-Dxv[j]
 	DXr[i]=-DXr[i]
 	Dyv[j]=-Dyv[j]
 	DYr[i]=-DYr[i]


Dans le cas contraire cela signifie que les éléments chimiques ont réagis entre eux pour former un autre élément, pour modéliser cette situation on fait disparaitre les deux boules en collision et on fait apparaitre une nouvelle boule à leur position.

	Canevas.delete(BallesRouges[i])
  	Canevas.delete(BallesVertes[j])
	BallesBleues.append(Canevas.create_oval(xv[j]-RAYON,yv[j]-RAYON,xv[j]+RAYON,yv[j]+RAYON,width=1,fill='blue'))
                        del BallesVertes[j]
                        del BallesRouges[i]



Ces deux cas de figures interviennent selon une certaine probabilité déterminer par les facteurs cinétiques choisit au départ.



•	La fission d’un élément chimique 
Lorsqu’à l’issue d’une collision un nouvel élément est créé sa durée de vie n’est pas infini, en effet sa durée de vie est limitée et il va se désintégrer pour redonner les deux éléments initiaux.  Du point de vue de notre programme nous avons modélisé ce phénomène par le fait qu’au bout d’une durée t la boule bleue allait disparaitre et les boules rouges et vertes réapparaitre.


	def fission():
    global Xr,Yr,DXr,DYr,RAYON,LARGEUR,HAUTEUR

  	for c in range (len(BallesBleues)):
        t=random.expovariate(0.2)
        if tp-0.1<t<tp+0.1:

 	  Canevas.delete(BallesBleues[c])
          del BallesBleues[c]

	  BallesRouges.append(Canevas.create_oval(Xr[j]-RAYON,Yr[j]-RAYON,Xr[j]+RAYON,Yr[j]+RAYON,width=1,fill='red'))
 	 BallesVertes.append(Canevas.create_oval(xv[j]-RAYON,yv[j]-RAYON,xv[j]+RAYON,yv[j]+RAYON,width=1,fill='green'))



•	Enfin les facteurs cinétiques Pression et Température qui sont des variables choisit par l’utilisateur en entrée vont déterminer le comportement général du système. En effet ces facteurs cinétiques vont avoir une influence d’un point de vue microscopique sur les éléments car ils déterminent leur vitesse la probabilité que leur collision entraine une transformation ainsi que la durée de vie du nouvel élément. 

